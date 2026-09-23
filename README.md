# Confidential gpt-oss-safeguard-120b

Tinfoil configuration for serving `gpt-oss-safeguard-120b` (OpenAI gpt-oss-safeguard-120b) with vLLM in a secure enclave. Used as the safety classifier for Tinfoil's safeguards.

The model, image digest, and serving flags are pinned in `tinfoil-config.yml` and measured at release time so clients can verify exactly what code the enclave is running.
