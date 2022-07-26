---
description: >-
  Liquidity는 유동성 풀(Liquidity Pool)입니다. 사용자는 원하는 풀에 암호 화폐를 예치할 수 있고, 우리는 이러한 생태계
  참여자를 유동성 공급자(LP, Liquidity Provider) 라고 부릅니다.
---

# Liquidity

## 개요

유동성(Liquidity)을 추가하면 기여자가 제공한 쌍에서 0.2%의 Swap 수수료를 얻을 수 있습니다.

본인이 제공한 Liquidity가 Farm 목에 포함되어 있다면 훨씬 더 많은 보상을 받을 수 있습니다!

유동성을 제공하면 기여의 증거로 LP 토큰(유동성 제공자 토큰)을 받게 됩니다. 예를 들어, 사용자가 $MMT와 $ETH를 Pool에 예치하면 MMT-ETH LP토큰을 받게 됩니다.

LP토큰을 Farm에서 Staking하여 IVY를 얻을 수 있습니다.

## 유동성 풀(Liquidity pool)이 무엇인가요?

누군가가 자신이 가진 토큰 중의 일부를 이더리움으로 교환하고 싶다면, 중앙거래소에서 암호화폐를 구매하기 위해 이더리움 매수 주문을 등록하고, 거래에 응해줄 상대방이 나타날 때까지 기다려야 할까요? 또한 거래할 만큼 충분한 수량을 보유하고 있어야 원하는 거래를 완료할 수 있습니다.

즉, 암호화폐 시장에서의 유동성은 내가 거래하고자 하는 암호화폐를 얼마나 빠르고 쉽게 교환할 수 있는지를 의미합니다. 그러므로 풍부한 유동성은 쉽고 편리한 암호화폐 교환을 위해 필수적인 요소이며, IvorySwap을 비롯한 DeFi, Dentralized Finance에서는 이를 해결하기 위해 거대한 규모의 암호화폐가 예치된 스마트 컨트랙트 자산 풀(Pool)을 기반으로 암호화폐 교환이 가능하도록 설계되어 있습니다.

## 유동성 풀의 예치 방법, 특징이 무엇인가요?



유동성 풀에는 두 개의 암호화폐 자산을 쌍(Pair)으로 예치할 수 있으며, 자산이 예치된 스마트 컨트랙트를 '풀(Pool)'이라고 부릅니다.

1. 스마트 컨트랙트 풀에 자산을 예치하는 사용자를 유동성 공급자(Liquidity Provider)라고 부릅니다. XRP+ETH 풀이 있다면, 시장의 누구나 풀에 원하는만큼 XRP과 ETH을 예치할 수 있습니다.\

2. 예치 시 동등한 가치의 토큰 수량을 예치하게 됩니다. 만일 IVY와 ETH의 현재 가격이 각각 $1, $2,000일 경우 상황에서 100 IVY를 예치하고자 하는 사용자는 $100 IVY 동일한 가치의 이더리움을 예치해야 하므로, 0.1ETH를 함께 예치해야 합니다. \
   (100/2000) 이때 암호화폐의 가격은 외부 거래소 가격이 아니라, Ivoryswap의 컨트랙트 풀의 예치된 두 자산의 교환 비율(가격)을 기준으로 합니다.\

3. 자산 예치를 완료한 시점부터 매 블마다 보상이 분배되며, 풀에 예치한 자산은 원한다면 언제든지 다시 출금할 수 있습니다.

## **새 풀에 유동성(Liquidity) 추가**

유동성을 제공하고자 하는 풀이 존재하지 않더라도 풀을 생성할 수 있습니다. 첫 번째 유동성 공급자는 Pool에 공급하는 토큰 중 하나가 IvorySwap에 아직 존재하지 않는 경우 초기 교환 비율(가격)을 설정합니다. 이는 종종 차익 거래와 풀에 추가되는 유동성 공급자를 통해 자체적으로 수정됩니다.

## **기존 pool에 유동성(Liquidity) 추가**

유동성 풀**(Liquidity Pool)**에 대해 1:1 가치 비율로 토큰을 제공해야 합니다.&#x20;

즉, IVY-ETH 풀에 유동성을  추가하려 할 때 1000 IVY 가치의 유동성을 제공하려면 동일한 가치의 ETH를Pool에 제공해야 합니다.  &#x20;

## Liquidity(유동성) 추가하는 방법

#### 요구 사항

* MetaMask 지갑
* Gas Fee로 사용될 MMT



1.지갑을 연결하고 Ma

mmoth Chain에 연결되어 있는지 확인합니다.

![](<../.gitbook/assets/image (8) (2).png>)

2.Liquidity로 이동&#x20;

&#x20;

![Create a Liquidity 선](<../.gitbook/assets/image (3) (1) (1).png>)

3."Select Pair" 클릭하여 "Select Token"에서 추가할 토큰을 선택합니다.

![](<../.gitbook/assets/image (9) (1).png>)

4.목록에서 토큰을 선택합니다. 목록에 없으면 주소를 검색하여 목록에 추가할 수 있습니다.

![](<../.gitbook/assets/image (19).png>)

5.두 번째 토큰을 선택합니다.

6.원하는 수량 입력합니다. "MAX"를 클릭하여 최대 수을 설정할 수도 있습니다.&#x20;

![](<../.gitbook/assets/image (3) (2).png>)

7."Approve"를 클릭합니다.

![](<../.gitbook/assets/image (16).png>)

8\. Approve 후 트랜잭션 메시지를 승인하면  "Supply"가 활성화 됩니다. "Supply"를 클릭합니다.

![](<../.gitbook/assets/image (5) (2).png>)

9."Supply" 클릭 후 Liquidity 생성에 대한 정보를 확인할 수 있습니다. "Add"를 클릭합니다.&#x20;

![](<../.gitbook/assets/image (17).png>)

10\. "Add"후 "Transaction Submitted"가 나오면 Liquidity 생성을 완료한 것입니다.      &#x20;

&#x20;

![](<../.gitbook/assets/image (6) (1).png>)



11."View on Explorer"를 클릭하시면 MMTscan에서 트랜잭션 내역을 확인할 수 있습니다.   &#x20;

10."My Liquidity"에 유동성이 잘 추가 되었는지 확인하고, 관리할 수 있습니다.

&#x20;

![](<../.gitbook/assets/image (2) (2).png>)

