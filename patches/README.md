# Patches

- `lora-training-in-comfy_compat.patch`: current consolidated compatibility patch for the working tree. Apply this one on a clean upstream checkout.
- `lora-training-in-comfy_python312_torch210.patch`: earlier compatibility snapshot kept for provenance. Do not apply it after the current consolidated patch.

From the repository root:

```bash
git apply --check patches/lora-training-in-comfy_compat.patch
git apply patches/lora-training-in-comfy_compat.patch
```
