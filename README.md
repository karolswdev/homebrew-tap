# karolswdev/tap

Homebrew tap for [Delivery Workbench](https://github.com/karolswdev/delivery-workbench) — evidence-first rails for agentic software delivery.

```bash
brew tap karolswdev/tap
brew install delivery-workbench
```

Then adopt any repository:

```bash
dw install /path/to/repo --skip-bootstrap
```

The formula's source of truth lives in the main repository at
[`Formula/delivery-workbench.rb`](https://github.com/karolswdev/delivery-workbench/blob/main/Formula/delivery-workbench.rb);
this tap mirrors it at each release.
