# FAQ

<details>
  <summary>How do I easily format my Certificate and Private Key pem into for a C config file</summary>
  Choose one of the following options depending on your preference:

- <details>
  <summary>Option 1 - Using an LLM online:</summary>
    Most LLMs (ChatGPT, Gemini, DeepSeek etc.)can help format your pem files into C *#defines*.
    A prompt like this can be used:
      
      ```
      convert this cert and key into C #define IOTCONNECT_CERT and IOTCONNECT_KEY:
      -----BEGIN CERTIFICATE-----
      MIIDWjCCAkKgAwIBAgIVAM95lTd9FQAGT86d51fgC74w3a74MA0GCSqGSIb3DQEB
      ...
      hDLZ65M7DrQICUBZvcjJeYE8OIY/F9KMn79bFlyZdUmHmqtiU5OzPEus/zkndw==
      -----END CERTIFICATE-----
      -----BEGIN RSA PRIVATE KEY-----
      MIIEpAIBAAKCAQEAovcw3KITgud+bv4eYHrV9aPbFyjevmubCCOQrmJP37ay0EPF
      ...
      JcG1nAezEOxpzFll1Fi9D33DhJyNN/bLGotBv1VTSjrKTpdHTd4JxA==
      -----END RSA PRIVATE KEY-----    
      ```

  </details>

- <details>
  <summary>Option 2 - Using Column Edit mode:</summary>
  
  The certificate and private key can be pasted into an advanced editor and 
  *Column Edit Mode* can be used to quickly insert double quotes and other special characters vertically across text:
  The following key combinations enable column mode selection:

  * Notepad++: Hold ALT while dragging with mouse vertically to select multiple columns.
  * VSCode: Hold ALT+SHIFT while dragging with mouse vertically to select multiple columns.
  * JetBrains products (CLinon, PyCharm etc.): Press ALT+SHIFT+Ins key to enable column mode. Drag with mouse vertically to select multiple columns. Press ALT+SHIFT+Ins again to disable column selection mode.

  </details>
</details>

<details>
  <summary>How do I find the IP address of my device?</summary>
  Choose one of the following options depending on your preference:
  ...
</details>

<details>
  <summary>How do I transfer my files with SSH?</summary>
  Choose one of the following options depending on your preference:
  ...
</details>
