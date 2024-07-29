## Amms-Rs Checkpoints

Checkpoints for uiswap v2 syncing to save rpc calls

```rust
    // The the checkpoint file to resume from the recent sync.
    // Sync pairs
    sync::sync_amms(factories, provider, Some("/storage/utils/amms-rs/examples/checkpoint-file-name.json"), 500).await?;
```
