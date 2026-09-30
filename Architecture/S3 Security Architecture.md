                    ┌──────────────────────┐
                    │      AWS Account     │
                    └──────────┬───────────┘
                               │
                        ┌──────▼──────┐
                        │     IAM     │
                        │ Least       │
                        │ Privilege   │
                        └──────┬──────┘
                               │
                               ▼
                  ┌────────────────────────┐
                  │       Amazon S3        │
                  │                        │
                  │  Private S3 Bucket     │
                  │  ─────────────────     │
                  │  • Block Public Access │
                  │  • SSE-S3 Encryption   │
                  │  • Versioning          │
                  │  • Bucket Policy       │
                  └───────────┬────────────┘
                              │
                       API Activity
                              │
                              ▼
                  ┌────────────────────┐
                  │   AWS CloudTrail   │
                  │ Activity Logging   │
                  └────────────────────┘
