## action-cargo
A docker container for GH actions containing `cargo contract` and `cargo build`

### Usage:

To run cargo contract test for a subdir in a monorepo
```
      - name: Test example contract
        uses: open-actions-rs/action-cargo@v0.0.3
        with:
          working-directory: smart-contracts/example
          cargo-cmd: test --verbose
```
