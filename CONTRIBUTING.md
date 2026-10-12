# Contributing

1. Open an issue first for non-trivial changes.
2. Fork, branch from `main`, keep PRs focused.
3. Run the project's checks before pushing:
   - Rust: `cargo fmt`, `cargo clippy -- -D warnings`, `cargo test`
   - Go: `gofmt -l .`, `go vet ./...`, `go test ./...`
   - Others: see the repo's README / CONTRIBUTING.
4. Use clear commit messages (Conventional Commits preferred).
5. PRs are squash-merged.

By contributing you agree your work is licensed under the repository's license.
