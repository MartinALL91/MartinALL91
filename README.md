### Hi, I'm Martin 👋

Python software engineer in Barcelona. I build open-source SDKs and tools that talk to industrial hardware: communication protocols, test automation with device simulators and hardware-in-the-loop, and the CI/CD that ships them to PyPI.

#### What I work on

- **[ingenialink-python](https://github.com/ingeniamc/ingenialink-python)** and **[ingeniamotion](https://github.com/ingeniamc/ingeniamotion)**: Novanta's open-source Python SDKs for configuring, commissioning and monitoring Ingenia servo drives. Core developer, **515 merged pull requests** across the organization's repositories.
  - Communication protocols: EtherCAT (SDO, PDO mapping, FoE firmware updates, EoE), CANopen, Ethernet/UDP and FSoE (Safety over EtherCAT).
  - Migrated the communications layer from a legacy C library to pure Python, adding Linux support and removing native build dependencies.
  - Virtual drive simulators that enable hardware-free testing in CI and for customers.
  - Release owner on rotation: Jenkins pipelines with hardware-in-the-loop tests, nightly builds, Docker images, Poetry packaging and ruff/mypy static analysis.
- **[pysoem](https://github.com/bnjmnp/pysoem)**: contributor to the Python EtherCAT master (~65k PyPI downloads per month): free-threaded (no-GIL) support for SDO reads and overlapped process data, emergency message callbacks and watchdog timeout retrieval.

#### Tools I use

Python · pytest · mypy · ruff · Poetry · Cython · C · Docker · Jenkins · GitHub Actions · Git · Linux · PyQt5

#### Contact

[LinkedIn](https://www.linkedin.com/in/martin-acosta-llano-9509a093) · martinacostallano@gmail.com
