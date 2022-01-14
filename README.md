## DappSmartContract_DSC

<br />

<img src="https://user-images.githubusercontent.com/70872563/148680784-6a1dacb1-8f39-4f41-9b48-3a6c6c20e82a.png"  width="500" height="300"/>

### 🚀 프로젝트명

이더리움 플랫폼에서의 Dapp 개발

### 🏁 목표

Solidity 언어를 이용하여 스마트 컨트랙트 프로그램 개발

### 🛠️ 필요기술

- Dapp 개발 동향 분석 후 관심 있는 분야의 스마트 컨트랙트 개발
- 오라클 기술 및 영지식 증명 적용
- web3를 이용한 Dapp 연동

---

<br />

### 스마트 컨트랙트란

계약 당사자가 사전에 협의한 내용을 미리프로그래밍하여 전자 계약서 문서 안에 넣어두고, 이 계약 조건이 모두 충족되면 자동으로 계약 내용이 실행되도록 하는 시스템이다. 기존의 블록체인 1.0 기숭이 **'과거에 일어난일'** 을 기록한다면, 스마트 계약 기능을 구현한 블록체인 2.0 기술은 **'미래에 일어날 일'** 을 미리 기록해둘 수 있다.

_스마트 컨트랙트란 중간에 제3의 보증기관을 끼우지 않고 개인간의 원하는 계약을 체결할 수 있도록 해주는 디지털 전자계약 기능이다._

### 비트코인 기술의 발전 <<이더리움>>

기존의 비트코인이 블록체인의 기술을 활용하여 가치의 저장과 전달이 가능한 _암호화폐_ 를 만들었다면, **이더리움** 은 한 단계 더 나아가 블록체인 기술을 활용하여 인간이 상상할 수 있는 모든 종류의 계약을 자동으로 실행할 수 있는 스마트 계약 플랫폼을 개발했다. 중요한건 블록체인 기술을 비트코인과 같은 암호화폐에서만 사용하는 것이 아닌, **위변조 방지가 필요한 각종 계약서 작성** 등에 활용할 수 있게 되었다.

### 스마트 계약 설계의 기본 원칙 4가지

> 1.  **관측가능성(observability)** : 스마트 계약은 서로의 계약 이행 가능석을 관찰하거나 성과를 입증할 수 있어야 한다.
> 2.  **검증 가능성(verifiability)** : 계약을 이행 또는 위반했을 때 이를 알 수 있어야 한다.
> 3.  **사생활 보호(privacy)** : 계약 내용은 계약에 관련된 당사자들에게만 알려져야 한다.
> 4.  **강제 가능성(enforceability)** : 계약을 강제로 이행할 수 있는 구속력이 있어야 한다. 단, 강제 가능성은 최소화해야 한다.

### 이더리움

- 비트코인 스크립트 시스텝의 튜링 불완전성이라는 한계를 극복하고자 나온 스마트 컨트랙트 플랫폼
  ++ 스마트 컨트랙트를 구현하기 위한 컨트랙트 코드(contract code)는 이더리움 가상머신(EVM; Ethereum Virtual Machine)이라는 독립된 실행 환경에서 실행된다.
  ++ 이더리움에서 스마트 계약을 처리하기 위한 가상 머신(EVM)은 모든 형태의 알고리즘을 처리할 수 있는 튜링 기계
  ++ 먼저 들어온 데이터를 우선적으로 처리하는 스택 구조
  ++ EVM은 저수준의 기계어에 가까운 바이트 코드만을 실행할 수 있기 때문에 고급 프로그래밍 언어를 실행하기 위해서는 바이트 코드로 컴파일 과정을 거쳐야함
  ++ 가상 머신을 이용하기 위해서는 '가스'라는 대가를 지불
  
## GAS 란?
  ++ 이더리움 생태계에서 구현되는 여러가지 알트코인들이 있다. 더 정확히 말하면 dApp인데, 그 중 반드시 필요한 것이 GAS라는 어플리케이션이다!
  ++++ 이더리움 플랫폼에서는 이더(ether)라는 자체 화폐토큰이 있고 이더를 가지고 가스(GAS)라는 어플리케이션을 구입해 이더리움이 Smart Contract를 하는데 연산력과 저장공간 제공의 '연료'로서 쓰이게 된다. 그렇게 되면 명령어에 따라 특정 조건에서 **자동적이고 강제적인 계약이 이행된다.**

## Smart Contract란?

*Smart Contract는 이더리움의 꽃이라고 할 수 있따!!*
++ Smart Contract는 온라인상에서 **특정 계약조건을 이행하는 것**이다.
++++ 예를들어, 성민이가 마세라티를 구입할게 될 경우 계약금으로 100ETH를 마세라티 딜러에게 제공한다는 조건을 세우면, 진짜로 성민이가 마세라티를 구입하게되는 상황이 발생했을 때 '상태변환함수'를 생성해 특정 조건을 만족하게 되어 100ETH를 마세라티 딜러에게 **강제적이고 자동적으로** 송금하게 된다.


