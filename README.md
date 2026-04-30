gital Basic Implementation


## 🍕 구성은 다음과 같아요
1. **RTL Design**
* VerilogHDL을 이용하여 Combinational/Sequantial Logic을 설계합니다

2. **Functional Verification**
* Xcelium Simulator를 사용하여 RTL 로직을 검증합니다

3. **Synthesis**
* Genus를 사용하여 RTL코드를 Gate Level Netlist로 합성합니다

4. **Equlvalence Checking**
* Conformal LEC를 사용하여 Logic의 등가성을 검증합니다
5. **Post Synthesis Verification**
* Xcelium을 이용하여 Gate의 Delay가 반영된 Simulation을 수행합니다
6. **Auto Place and Route(PNR)**
* Gate Level Netlist를 실제의 회로 패던으로 구현합니다.


## 🛠️ 도구 모음 및 개발 환경
- GPDK045 : gsclib045, giolib045
- Cadence Xcelium : Logic Simulator
- Cadence Genus : Synthesis Solution
- Cadence Conformal : Logical Equivalence Check
- [Cadence Innovus] : Auto Place and Route
 - [GIT](https://git-scm.com/) : Source Control Management(SCM)
- [GitHub](https://github.com/) : Git Cloud Server
