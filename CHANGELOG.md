# Changelog

## 0.6.0 (2026-05-31)

Full Changelog: [v0.5.0...v0.6.0](https://github.com/cellect-ai/cellect-sdk-python/compare/v0.5.0...v0.6.0)

### Features

* **api:** api update ([15fdcf9](https://github.com/cellect-ai/cellect-sdk-python/commit/15fdcf9c0dba68a9211d4ec1be432c0a96c60631))
* **api:** api update ([fe4ceb2](https://github.com/cellect-ai/cellect-sdk-python/commit/fe4ceb25795e20c2e144aef185726341ceeacead))
* **api:** api update ([fc99dab](https://github.com/cellect-ai/cellect-sdk-python/commit/fc99dab197f2893bf59f07dc8b21439ac3587727))
* **api:** api update ([ce3bb46](https://github.com/cellect-ai/cellect-sdk-python/commit/ce3bb4685d6413ab752890789d07769307db42ed))
* **api:** api update ([e44ec75](https://github.com/cellect-ai/cellect-sdk-python/commit/e44ec75ae7788a9741803bfa153a1a77b7276673))
* **api:** api update ([d3e7a12](https://github.com/cellect-ai/cellect-sdk-python/commit/d3e7a125cc2458caede09e2469056de4f687ee75))
* **api:** api update ([581590f](https://github.com/cellect-ai/cellect-sdk-python/commit/581590fa615d9cca264c63fa9a1486bcfc55eff2))
* **api:** api update ([e3d008b](https://github.com/cellect-ai/cellect-sdk-python/commit/e3d008b2377aa3044091804fa9941f637e751c9e))
* **api:** api update ([1bac7b0](https://github.com/cellect-ai/cellect-sdk-python/commit/1bac7b078bec50c0f13d4480a72245afb4bdf621))


### Bug Fixes

* **client:** close streams without requiring full consumption ([0dbe601](https://github.com/cellect-ai/cellect-sdk-python/commit/0dbe6019962b20a0354ce736cbdba5c277ac9ca7))
* compat with Python 3.14 ([a9f5a40](https://github.com/cellect-ai/cellect-sdk-python/commit/a9f5a4023efc7a6a71d050a2a2fbfabea026c7b3))
* **compat:** update signatures of `model_dump` and `model_dump_json` for Pydantic v1 ([61b4ffb](https://github.com/cellect-ai/cellect-sdk-python/commit/61b4ffb45afd719edf57b3bc8d9bd5f3bca65995))
* ensure streams are always closed ([ed713b7](https://github.com/cellect-ai/cellect-sdk-python/commit/ed713b76ef6e535394a39d57923127984a7de070))
* **types:** allow pyright to infer TypedDict types within SequenceNotStr ([792f149](https://github.com/cellect-ai/cellect-sdk-python/commit/792f1492381f3f36fc2227ef199a1187466c0a45))
* use async_to_httpx_files in patch method ([7c0478b](https://github.com/cellect-ai/cellect-sdk-python/commit/7c0478baedcc66f80aaf4e16d44e7a4245ced57b))


### Chores

* add missing docstrings ([f53bf96](https://github.com/cellect-ai/cellect-sdk-python/commit/f53bf9687f507072ce2727cc1ff013023f0f0c5f))
* add Python 3.14 classifier and testing ([c05a3d5](https://github.com/cellect-ai/cellect-sdk-python/commit/c05a3d5e1610a681d80f42c4dc50389a6ec8fe95))
* **deps:** mypy 1.18.1 has a regression, pin to 1.17 ([db98d88](https://github.com/cellect-ai/cellect-sdk-python/commit/db98d881672b6bc14ea64118d982a05a36c21e16))
* **docs:** use environment variables for authentication in code snippets ([d5c0c68](https://github.com/cellect-ai/cellect-sdk-python/commit/d5c0c6860ac7449db4fdbab650f6785d0808339f))
* **internal/tests:** avoid race condition with implicit client cleanup ([652a870](https://github.com/cellect-ai/cellect-sdk-python/commit/652a870e3c4ac3b7b4d2959bc6f28c2ccd9c2534))
* **internal:** add `--fix` argument to lint script ([b8534cf](https://github.com/cellect-ai/cellect-sdk-python/commit/b8534cfd75771c6de590a0360ea142ecbcd6c30f))
* **internal:** add missing files argument to base client ([eeabc26](https://github.com/cellect-ai/cellect-sdk-python/commit/eeabc2640f97b2ac7b0f930f8af1c4f7d88589b0))
* **internal:** codegen related update ([cabf5f0](https://github.com/cellect-ai/cellect-sdk-python/commit/cabf5f00fb68ce0e48deb5baa2adb26a087b1e7f))
* **internal:** codegen related update ([3d82851](https://github.com/cellect-ai/cellect-sdk-python/commit/3d8285190191bc3a10ae48506d6fe754df6235b5))
* **internal:** codegen related update ([62d4e14](https://github.com/cellect-ai/cellect-sdk-python/commit/62d4e1467872b7c41fe221803f63969e5f875c07))
* **internal:** codegen related update ([ef64aaf](https://github.com/cellect-ai/cellect-sdk-python/commit/ef64aaf1b9a54632c698db0182ca499b557b3c1f))
* **internal:** codegen related update ([fbf460b](https://github.com/cellect-ai/cellect-sdk-python/commit/fbf460b4ade8eff970a63bd5c7a416b056de9e67))
* **internal:** codegen related update ([27030c0](https://github.com/cellect-ai/cellect-sdk-python/commit/27030c0cf10a0af213756153861c6b60a7b2e1e9))
* **internal:** grammar fix (it's -&gt; its) ([90201c5](https://github.com/cellect-ai/cellect-sdk-python/commit/90201c5b5468e703dbb5ddf3f682c7d2b37593d5))
* **internal:** update `actions/checkout` version ([3c67625](https://github.com/cellect-ai/cellect-sdk-python/commit/3c6762594d984f3f1d5b4fb079533a110c96902b))
* **package:** drop Python 3.8 support ([c18c5b2](https://github.com/cellect-ai/cellect-sdk-python/commit/c18c5b24c9d725c0f04ee6e1bbf26f16adfacf7b))
* speedup initial import ([74367d2](https://github.com/cellect-ai/cellect-sdk-python/commit/74367d24661abb1d795eeb9d790765e7b1241beb))
* update lockfile ([0a51148](https://github.com/cellect-ai/cellect-sdk-python/commit/0a51148534e3428f85424adba9cad2e5c585f7eb))

## 0.5.0 (2025-10-22)

Full Changelog: [v0.0.2...v0.5.0](https://github.com/cellect-ai/cellect-sdk-python/compare/v0.0.2...v0.5.0)

### Chores

* update SDK settings ([8031a39](https://github.com/cellect-ai/cellect-sdk-python/commit/8031a3963d7bc27286e39d3ac1ee3fcbe65dbd23))
* update SDK settings ([06c0d37](https://github.com/cellect-ai/cellect-sdk-python/commit/06c0d37f66cdfdf7407cd72b3d63cd65f296e6d8))

## 0.0.2 (2025-10-22)

Full Changelog: [v0.0.1...v0.0.2](https://github.com/cellect-ai/cellect-sdk-python/compare/v0.0.1...v0.0.2)

### Chores

* update SDK settings ([8031a39](https://github.com/cellect-ai/cellect-sdk-python/commit/8031a3963d7bc27286e39d3ac1ee3fcbe65dbd23))
* update SDK settings ([06c0d37](https://github.com/cellect-ai/cellect-sdk-python/commit/06c0d37f66cdfdf7407cd72b3d63cd65f296e6d8))

## 0.5.0 (2025-10-22)

Full Changelog: [v0.0.1...v0.5.0](https://github.com/cellect-ai/cellect-sdk-python/compare/v0.0.1...v0.5.0)

### Chores

* update SDK settings ([8031a39](https://github.com/cellect-ai/cellect-sdk-python/commit/8031a3963d7bc27286e39d3ac1ee3fcbe65dbd23))
* update SDK settings ([06c0d37](https://github.com/cellect-ai/cellect-sdk-python/commit/06c0d37f66cdfdf7407cd72b3d63cd65f296e6d8))
