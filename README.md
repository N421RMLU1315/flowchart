```mermaid
flowchart TD
    A[Start] --> B[Pemilihan Arsitektur Model]
    B --> B1[Transfer Learning]
    B --> B2[Custom Model]
    B1 --> C[Pengaturan Parameter Model]
    B2 --> C[Pengaturan Parameter Model]
    C --> C1[Hyperparameter Tuning]
    C --> C2[Loss Function]
    C --> C3[Optimizer]
    C1 --> D[Pelatihan Model]
    C2 --> D[Pelatihan Model]
    C3 --> D[Pelatihan Model]
    D --> D1[Training]
    D --> D2[Validation]
    D --> D3[Early Stopping]
    D1 --> E[Evaluasi Model]
    D2 --> E[Evaluasi Model]
    D3 --> E[Evaluasi Model]
    E --> E1[Accuracy and Loss]
    E --> E2[Confusion Matrix]
    E1 --> F[End]
    E2 --> F[End]
