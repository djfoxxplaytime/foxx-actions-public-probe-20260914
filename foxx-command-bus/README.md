# FOXX Encrypted Command Mailbox

This public repository contains ciphertext only.

Commands are hybrid-encrypted for FOXX Sovereign using RSA-OAEP-SHA256 + AES-256-GCM. Command payloads, device identifiers, and receipt decryption keys are never stored here in plaintext.

FOXX Sovereign polls only `queue.json`, decrypts commands locally, executes through Commander governance, and publishes encrypted receipts over its HTTPS receipt endpoint.

Do not place plaintext commands, credentials, tokens, or results in this repository.
