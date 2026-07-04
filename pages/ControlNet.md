# Fine-Grained Layout Control

Detailed info on ControlNet.

```mermaid
graph TD;
 A[Base Model] --> B[Locked Weights];
 A --> C[Trainable Copy];
 C --> D[Conditioning];
```