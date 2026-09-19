# Web Resilience Korea

Integration repository for the Seoul FTO hackathon. It combines the web resilience testing tools, Korean traffic lists, test results, and profile generator as Git submodules.

## Submodules

- `web-resilience-test` — testing and analysis tools
- `web-resilience-test-profile` — static result page generator
- `web-resilience-test-result` — test result dataset
- `top-traffic-list-korea` — Korean website traffic rankings

## Clone

```bash
git clone --recurse-submodules https://github.com/irvin/web-resilience-kr.git
```

If the repository was cloned without submodules:

```bash
git submodule update --init --recursive
```

## License

This integration repository is dedicated to the public domain under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/), to the extent permitted by law. See [LICENSE](LICENSE).
