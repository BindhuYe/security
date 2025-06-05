

1. **Connection Request**: The browser requests a secure connection to a website (e.g., `https://www.google.com`).
2. **SSL Certificate Sent**: The web server responds by sending its **SSL certificate**, which includes its **public key**.
3. **Certificate Verification**: The browser checks the SSL certificate's validity using a **Certificate Authority (CA)**.
4. **Shared Secret Creation**: After verifying, the browser creates a **shared secret** (session key) and encrypts it with the server’s **public key**.
5. **Shared Secret Decryption**: The server uses its **private key** to decrypt the shared secret.
6. **Encrypted Communication**: Both the browser and server now use the shared secret to **encrypt and decrypt** data, ensuring secure communication.

**Key Concepts Illustrated:**

* **Public Key & Private Key** encryption
* **SSL/TLS Certificate** verification
* **Encrypted data transmission** using a shared secret

This process ensures data privacy, integrity, and authentication during online communication.
