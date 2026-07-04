# DDIM

Detailed info on DDIM.

```mermaid
graph TD;
 A[Noise] --> B[Deterministic Reverse Step];
 B --> C[Skipped Steps];
 C --> D[Image];
```