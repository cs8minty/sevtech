**SevTech 팁과 트릭**

Sevtech 현재 버전은 3.1.2 Hotfix 1 : [여기서 얻으세요 !](https://www.curseforge.com/minecraft/modpacks/sevtech-ages/files/2752761)

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_0.png)

여기에 웹뷰가 있다 [https://cs8minty.github.io/sevtech/](https://cs8minty.github.io/sevtech/) 

팁을 제안할 생각이 없는 경우 이것을 사용하십시오.

언제든지 의견을 추가하고 [여기](https://docs.google.com/document/d/1CSVTuVD59676TQkjwyPqY8zjTPCpKONYXtxenJ-qub8/edit#)에 변경 사항을 제안하십시오.

### 버전 히스토리

1. Diff between [October 31 and October 7](https://drive.google.com/open?id=1YArnaRjxNOVYz-yO4Gmmv6_HtFlYlIqG)

2. Diff between [August 8 and October 7](https://drive.google.com/open?id=1vHraaoosT4qYSL5fPMntIgqf94a89YIJ)

3. Diff between [July 17 and August 8](https://drive.google.com/open?id=1iUIK6yUnpyqcd9cGvM_ZW00OHIgbBZoA)

4. Diff between [June 25 and July 17](https://drive.google.com/open?id=1WudKOZ9BO6hl960VTAg3v11yVvKeC15O)

5. Diff between [June 14 and June 25](https://drive.google.com/open?id=1X7BmdhedgI2tPnKT8XdV4W7ixEHz7SEC)

6. Diff between [June 10 and June 14](https://drive.google.com/open?id=15xDmxcEqxKuvyDR0GRiyzHIRCUTDb4fN)

7. Diff between [June 6 and June 10](https://drive.google.com/open?id=1Xw0065eIW0yck-Wbetml00HROXfRxvII)

8. Diff between [May 18 and June 6](https://drive.google.com/open?id=1j2IXmzuFCeosuq07z-pMCv4WxBzikRT4)

9. Diff between [May 12 and May 18](https://drive.google.com/open?id=1QyL_zWwchtsIxUAdLIy4wPisX5TplQJa)

10. Diff between 3.0.6 and [May 12 2018](https://drive.google.com/open?id=1KQ2RqrPF2Kuze9beV3ZEdSWoC4y9Su4-)

### 성능 팁:

* 모드팩 제작자는 4 GB의 램만 할당하면 된다고 하지만, 당신의 생각은 다를 수 있습니다.

* 가비지 컬렉션을 위한 커스텀 자바 인수: -XX:+UseG1GC -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=51 -XX:G1HeapRegionSize=32M

* 특정 모드를 사용하지 않도록 설정하면 성능이 향상될 수 있음:

    * Better foliage - 이 모드는 나뭇잎과 잔디를 더 복잡하게 보이게 한다.

    * Fancy block particles - 파괴되는 블록을 3D로 변형시킨다.

    * Smooth font - 기본 글꼴을 교체한다.

* 원하는 그래픽 환경을 조정하려면 옵티파인(optifine)을 설치(최대 D3버전)하세요: [https://optifine.net/downloads](https://optifine.net/downloads)

    * 옵티파인을 사용할 시 블록이 보이지 않는다면 **config/thebetweenlands/config.cfg**의 **B:fullbright_blocks=true**를 **false**로 변경한다.

* 황혼의 숲(Twilight Forest) 트윅 (config/twilightforest.cfg) :

    * FPS 스터터링을 줄이려면 **B:leavesFullCube=true**을 **false**로 설정하십시오.

* PrimalCore의 나무를 Cyclic block placer에 넣지 마십시오. 이로 인해 '타일 엔티티'가 충돌하고 저장 파일이 손상될 수 있다.

* BloodMagic Router에 "Ore Dict Filter" + Hemp Seeds도 마찬가지다 -> 타일 엔티티 오류

### 시드

-1717583552609621523 (3.1.2 Hotfix 1) 넓은 들판에 스폰한다. 4개의 쇼고스 둥지가 근처에 있고, 뼈 구조물, 락 크리스탈 그리고 용암이 조금 떨어진 곳에 있다. 강 너머에 마을이 있고 주변에 필요한 모든 금속이 있다. 다크랜드 X=-1500,Z=-750 (뗏목으로 하룻밤 여행)과 다크랜드 조약돌 마을. 벚꽃 나무와 오일 3500 양동이.

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_1.png)

-7757505388919135334  (3.0.7) Spawn in Village, next to flat plains, Large bone structure and Shoggoth lair within 200 blocks of spawn. Rock Crystals just outside of town. Lava. 

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_2.jpg)

-115227398    (pre 3.0.5)  Start in AbyssalCraft biome, close village to NW (Another South of that one), nice open area to the east with river biome, large forest and lots of animals. Another village north on other side of tall hills across grassy plains with lots of streaming water..

-8872794606572219902   (3.0.4)  Spawn next to Laketown (village in middle of lake). High flat mountain at your back for strong star light with a tin vein. On other side of lake is a large flat area with **large **bone structure VERY nearby, Eucalyptus and a Mulberry tree, 2 coal, 2 copper veins, 1 gold. Lapis on island next to village. Majority of lake is only 1 block deep, making easy access to gravel, salt, sand, and clay. Nearby big hole(y=51 @ base) with Copper cluster. Snow mountain nearby (Build up 20+ blocks on peak for easy access to ceiling of The Beneath).

-3822593286363813618 3.0.6 Very strong, Amazing map. Everything you need to play within 200 blocks from spawn

# Age 0

## 일반 팁

* L을 누르면 메인 퀘스트 가이드에 접근할 수 있다. 보라색 퀘스트는 당신을 에이지의 끝으로 이끈다(색상이 없다면, 이것은 두 개의 둥근 면을 가진 것에 대해 말하고 있는 것이다. 별은 현재 에이지의 최종 퀘스트이다).

* 땅에 있는 바위가 한 번 클릭으로 부서지지 않거나 **부딪힐 때 흙/잔디처럼 들린다면**, 그것을 그대로 놔둬라. 그것은 광석 샘플이 변신한 것이다.

* Carry-On은 모드팩에 있고, 대부분의 비선공 몹(마을 주민, 버팔로, 말, 또는 더 큰 몹)을 들 수 있다. 오른쪽 클릭보다 도달 범위가 작다는 점에 유의하십시오. 또한 대부분의 상자와 이와 같은 다른 타일 엔티티들을 집을 수 있다.

* **조약돌에 불을 붙이면** 목탄을 굽는 첫 가마(Kiln)가 흙/잔디보다 조금 더 오래 갈 것이다.

* Quark의 인벤토리 정리 버튼을 통해 unfamiliar 아이템을 근처 상자/호퍼에 넣을 수 있으므로 스테이지의 제한을 피할 수 있다.

* 아이템을 즐겨찾기함으로써 아이템을 [떨어뜨리는 것](https://quark.vazkii.us/#module-management)을 막을 수 있다. Alt + 아이템을 마우스 오른쪽 버튼으로 클릭하면 "즐겨찾는 아이템"이 된다. Inventory tweaks settings(오른쪽 위 점3개)으로 이동하여 단축키를 끄십시오.

* 월드는 **논리적 열 지도**로 생성된다.[ (Breakdown of the heatmap and where to find biomes.)](https://www.reddit.com/r/feedthebeast/comments/8crpq4/sevtech_heatmap_breakdown/) 눈이 필요한가? 사막이 필요한가? 찾을 때까지 북쪽이나 남쪽을 여행하라! 아래의 열 지도 섹션을 참조하십시오.

* 당신의 인벤토리에서 당근은 당신이 당신의 **영양 수준**을 볼 수 있는 곳이다. 만약 당신이 영양 수준을 충분히 높인다면 당신은 **버프**를 얻을 것이다. 그것을 너무 낮게 놔두면 디버프를 얻게 될 것이다. 아래 영양을 참조하여 건강한 식사를 하십시오.

* 당신은 삽으로 만든 잔디 길과 같은 특정 블록에서 **더 빨리** 움직일 수 있다.

* F7을 사용하여 지상의 **밝기 수준**을 확인하고 F9를 사용하여 **청크 경계**를 확인하십시오.

* 일부 블록은 다른 블록으로 **변장**하고있다. 그것은 올바른 단계에서 드러난다. 항상 돌아가서 이미 탐색한 영역을 확인하여 새로운 것을 확인하십시오.

* **뗏목(Rafts)**은 수상 교통 수단의 초기 형태이다. 그것은 단지 조금 더 약하고 느릴 뿐이다.

    * 때때로 그것은 가라앉는다. Carry On'(쉬프트+우측 클릭)을 사용하여 들어올리세요.

* 일단 당신의 기지를 위한 장소를 고르고 나면, 스폰포인트를 재설정하고 약간의 음식을 먹고, 기둥을 세우고, 당신을 다시 **기지로 인도하는 해골 나침반**을 얻기 위해 죽어라, 내 말은, 데스 포인트라는 뜻이다.

* 무덤에서 쉬프트/움크리기를 하여 아이템을 되찾아라.

* 안장을 얻으면 말을 길들이고(반복해서 다시 타려고 해라) 속력을 내서 세계를 횡단하라. 말은 돌로 된 울타리를 뛰어넘을 수 있지만, 오직 너만이 탈 수 있다. 그렇지 않으면 바다 근처에 살면 뗏목을 이용하여 새로운 곳을 방문해라. 해안가에 도착하면 공격하는 상어와 피라냐가 반겨준다.

* 상어를 사냥하는 것은 쉽다; 만약 여러분이 서 있을 수 있는 한 블록의 깊은 물줄기가 있다면, 여러분은 상어들이 여러분에게 닿지 않고 그들을 창으로 찔러 죽일 수 있다.

* 벚꽃, 유칼립투스 또는 짙은참나무를 주시하라. 워크스텀프를 mk2 버전으로 업그레이드하려면 목재가 필요할 것이다. 그것은 반복적인 제작템을 만들기 위해 물건을 가득 넣을 수 있고, 더 적게 칠 수 있다.

* 몹들에게 피해를 입히기 위해 펀지 스틱(사탕수수로 제작한 것)을 사용할 수 있다. 수집을 위해 호퍼 위에 놓고, 거미를 막기 위해 벽에 붙일 수 있다.

* Lit fibre 횃불은 바닐라 횃불보다 좋지 않다. 그것은 10의 낮은 밝기 수준밖에 제공하지 않는다. 즉, 몹들은 여전히 3블록 떨어진 곳에서 스폰 될 수 있다는 뜻이다. 훨씬 더 좋은 조명을 위해 두 개의 막대기를 사용하여 토템 횃불을 제작하십시오. 토템 횃불은 숯/석탄을 필요로 하지 않기 때문에 많은 공급이 필요할 것이다. 부싯돌 작업칼을 사용하여 잎에서 막대를 즉시 얻고 풀에서 fibre를 얻는다. 많이 생산하고 싶으면 작업칼 3개를 가지고 와라.

* fire hopper에 필요한 붉은 삼나무는 모든 종류의 묘목을 붉은 삼나무 묘목으로 변환하기 위한 토템 의식을 필요로 한다.

* 상어가 발견되지 않으면 survivalist’s strainer와 함께 상어 이빨를 채취하기 위해 strainer를 사용한다. (10분에 5%가 나올 확률이 거의 보장된다).

* 무덤이 제거되면(예: 히드라에 의해) Tomb Many Graves 모드의 **/tmg_restore** 명령을 사용하여 무덤을 복구할 수 있다.

* 방향을 잡는 데 어려움이 있으십니까? 태양을 사용하라! 해와 달이 동쪽에서 뜨고 서쪽으로 진다. 이것은 당신이 어느 방향으로 여행하고 있는지 찾기에 좋은 게임 초반의 나침반이 된다.

* drop off 버튼은 당신의 인벤토리를 근처 상자로 병합한다. 만약 당신이 이 드롭오프 버튼과 함께 근처에 상자가 있다면, 당신이 가지고 있는 모든 조약돌도 그 상자로 밀어넣을 것이다. 아직 저장하지 않은 경우 인벤토리에 보관하십시오.

* FindMe를 사용하면 JEI의 아이템 위에 마우스를 올려놓고 'Y'를 누르면 해당 아이템이 있는 근처의 모든 상자에 연기가 피어 오른다.

* 아틀라스(지도)는 사서를 찾을 수 없을 때 퀘스트를 완료할 수 있도록 이제 제작이 가능하다.

* 당신의 오프핸드 슬롯에 목재/나무판자를 놓고 오른쪽 클릭으로 배치하여 훨씬 더 빨리 자르도록 할 수 있다. 이것은 나중에 stone anvil에도 효과적이다.

* 선인장은 사탕수수와 인접해 자랄 수 있고, 농장을 더 컴팩드하게 만들 수 있다.

## 스텝 어시스트 vs 자동 점프

자동 점프는 끔찍하다, 우리 모두 알고 있어. 그것은 세브테크에서 기본적으로 켜져 있지 않다. 대신 처음부터 Cyclic의 스텝 어시스트 기능이 있다. 피의 제단을 만든 후 에이지 1에는 특별한 사과(Lofty Stature의 사과)를 만들어 이 기능을 전환할 수 있다. 비활성화하는 더 빠른 방법은 아래를 참조하십시오.

다음은 자동 점프에 대한 스텝 어시스트 수정 사항: 

* 1.25블록 전체를 점프하는 것이 아니라 필요한 1개의 수직블록을 즉시 이동시킨다.

* 점프도 하지 않고 착지도 하지 않아 오르는 시간 단축.

* 몹들은 여전히 점프를 해야 하고, 등산을 현실적인 탈출 전략으로 만든다.

* 물에서 올라올 때 밭을 망치지 않는다.

* 마치 달리는 것처럼 산을 뛰어오를 수 있다.

* 걷는 것보다 배고픔을 더 많이 사용하지 않는다.

* When digging diagonally down you don't have to make the pathway 3 tall. A 2 tall stairway allows for fast travel up. Still the same jerkiness going down. But now you don’t have to jump going up.

이 기능이 게임에 방해되고 설정을 조정할 수 있는 경우 cyclic 설정으로 이동하여 stepheightdefault을 사용하지 않도록(disable) 설정하고 새 문자를 만드십시오. 이미 있는 경우 관리자가 사과를 치트할 수 있는지 확인하십시오.

## 첫 번째 기지 선택 시기 및 장소

### 무엇을 찾아야 하는가

* 첫 번째 도구를 만들기 위한 자갈, 막대기, 섬유. 그리고 나서 부싯돌 곡괭이, 작업용 칼, 가위, 돌 곡괭이, 도끼로 업그레이드한 다음 스텀프를 제작한다.

* 플리스(Fleece): 작업용 칼은 이것을 실로 바꾸므로, 목화를 찾을 필요가 없다. 플리스를 위해 양을 죽이는 대신 부싯돌 가위를 사용하여 도망가지 않도록 하십시오. 가능한 한 빨리 침낭을 만들어라.

* 사탕수수: 토템 도구를 충분히 사용할 수 있도록 6개 이상 심어야 할 겁니다.

* 먹물: 흰코트의 마을 주민과 거래할 수 있는 아틀라스(지도)에는 깃털과 먹물이 필요하다.

* 깃털: 아틀라스 말고도 야생개 부츠에 16개가 필요할 겁니다. 닭 한 마리당 깃털을 4개씩 얻기 위해 가위를 사용하여 도망치지 않고 그 과정에서 죽인다.

* [선택] Hemp:  hemp를 사용하여 각각 8개의 깃털로 2 묶음을 만든다. 어려운 점은 다 자란 hemp를 찾는 것이다.

* [선택]Dog Pelt Boots: Dog Pelt Boots를 위해 모든 wild dog의 가죽을 보관한다(**더 빨리 달리고**, 훨씬 더 높이 점프하고, 좋은 갑옷, 낙상 피해 없음).

* 뼈 블록: 뼈 화석은 평원에서 쉽게 발견된다. 빠른 농사와 홈스테딩을 위해 최소 10-30블록의 블록을 얻으시오.

* 검은 연꽃, 민들레, 장미: fluid bladder는 이 3개의 가루가 필요하다.

* 점토: 에이지 0을 통과하려면 30개 정도가 필요할 겁니다.

* 뼈 4-7개: 토템은 이것들을 필요로 한다. 동물들과 좀비들은 때때로 뼈를 떨어뜨린다는 것을 주목하라.

* 이 모든 것을 수집할 때 초기 인벤토리가 부족하기 때문에 고기와 가죽을 위해 한 종류의 동물을 얻도록 하라.

* 마을에는 돌 반블록과 대장간이 있다. 지루한 과정을 생략하고 가죽끈을 교환할 가죽장이를 찾아라. 네가 여기 있는 동안 플리스와 실을 거래해라.

### 어디에 기지를 만들어야 하는가

* 폭포는 물고기가 그 안에서 생성되게 할 것이고, 물 가장자리에서 튀어나와 땅에서 소멸할 것이고, 단백질을 쉽게 얻을 것이다.

* 물: 강과 해양 바이옴은 무한 물을 가지고 있다. 호수의 물을 끌어내는 것은 귀찮고 소용돌이치는(흐르는) 결과를 낳는다. 배치 가능한 물은 에이지 2에서 나오므로, 어떤 농장도 기존 물, 즉 수로 주변에 배치되어야 할 것이다. 당신은 또한 당신의 사탕수수를 심고 그 근처에 항상 자라도록 하기를 원할 것이다. 그에 따라 자신의 기지를 계획하십시오.

* 숲: 나무를 꽤 오래 많이 쓸 테니, 나무에 빨리 접근할 수 있는 곳을 골라라.

* 가죽(Hide)과 가죽(Leather)을 교환할 수 있는 마을을 찾아라. 그래야 긴 가죽을 만드는 과정을 건너뛸 수 있다.

* 또한 양모(Fleece)를 실로 교환하는 것은 작업용 칼로 변환하는 것보다 더 나은 결과를 얻을 수 있다.

* 소: 소들을 버팔로로 바꾸는 것은 진행을 위해 필요하다. 당신은 그것들을 얻는 세 가지 방법이 있다: 밀로 유인하는 것, 줄로 손수 끌고오는 것, 또는 그것들을 천천히 운반하기 위해 carry-on을 쓰는 것. 소 떼에서 그리 멀지 않은 기지를 골라라.

* 에이지 1이 되면 인벤토리를 보관하는 상자를 만들어 훨씬 쉽게 이동할 수 있다. 그러니 완벽한 장소를 찾을 필요는 없다. 에이지 2는 팅커의 목재 도끼가 잠금해제 되어 주변의 숲을 덜 위험하게 만든다.

### 기지로 설정하지 말아야 하는 곳

* 진흙 패치(mud patches)가 있는 영역. 진흙은 삽으로도 채굴에 오래 걸린다.

* 평원: 게임 초반은 나무를 많이 사용한다.

    * 반면에, 직접 나뭇잎을 깰 때, 묘목은 구하기 매우 쉽다. 큰 나무 농장을 만들어라.

## 도구

* 모종삽(Trowel): 자갈을 초고속으로 판다.

* 부싯돌 손도끼: 엄밀히 말하면 crafting stump로 들어가는 관문이다. 빨리 돌도끼로 업그레이드해.

* 부싯돌 곡괭이: 조약돌로 들어가는 관문. 가능한 한 빨리 돌로 만든 곡괭이로 업그레이드하십시오.

* 부싯돌 창: 4의 피해를 주는 근접 장거리 무기, 그러나 그것을 던지는 것은 깨질 위험이 있다.

* 조각칼(토테믹): 토템을 만드는 데만 사용하라. 토템 동물을 전환하려면 허공에다 마우스 스크롤하거나 우클릭하십시오.

* 조약돌 작업칼:

    * 풀과 나뭇잎을 각각 노끈(twine)과 막대기로 즉시 자르는 데 사용할 수 있다.

    * 흙/나무/돌에 쉬프트-우클릭하여 사다리를 만드십시오. 동물 우리로 좋다.

        * 블록 당 임의의 횟수를 시도해야 만들어 진다

        * 사다리쪽에 붙어 있어야 한다는 것을 명심해라 그렇지 않으면 떨어진다.

    * 나무를 쉬프트-우클릭(원목은 위를 향해 있어야 한다)하여 나무껍질을 얻는다.

    * 잔디길에 쉬프트-우클릭하여 잔디길 계단을 만든다.

    * 많은 것을 만들기 위해 제작창에서 사용하라(목록을 보려면 인벤토리에서 "u"를 누르십시오).

    * 다른 부싯돌 도구들처럼 수리할 수 없다.

    * 좋은 초반 무기

* 돌 곡괭이/도끼/검/괭이/삽: 조약돌을 사용해 돌로 만든 도구를 수리할 수 있다.

* 게임 초반: 가능한 한 많은 곰 발톱을 모으도록 노력하라. 그것은 당신이 0-1단계에서 최고의 무기인 곰 발톱 팍셀(bear claw paxel)을 만들 수 있게 해줄 것이다. 그것은 또한 돌로 된 도구보다 더 빠른 곡괭이/도끼/삽이다. 곰 발톱으로 수리할 수 있다(그래서 더 많이 모아야 한다). 그것은 나중에 광산 도구로서 매우 유용하다.

* 부싯돌 가위: 잎을 자른다(토템 풍경을 더 음악적으로 만든다), 덩굴을 자른다(에이지 1 때 바이옴 디텍터에 유용하다). 크리퍼의 폭발을 방지한다. 닭에 사용하는 것은 깃털을 떨어뜨려 닭을 해칠 수는 있지만 겁을 주지는 않는다. 닭고기를 얻기 위해 쫓을 필요 없다.

* 블록 회전: 아직 블록을 회전하는 도구에 접근할 수 없는 동안, K를 눌러 블록을 배치할 때 방향을 결정하는 방법을 전환할 수 있다. 집을 짓는데 유용하다.

* 물주머니(bladder): 가죽 제작에 필요한 것. 물을 배치하지도 용암을 뜰 수도 없다. stirring pot에 물을 넣을 수 있다.

* 모종삽(Trowel): 삽과 같다, 그러나 풀 블록을 파면 종종 벌레들을 떨어뜨려, 물고기를 스트레이너에 넣는데 도움이 된다.

* 돌 몽둥이: 그것은 평균적인 피해를 주며, 매우 빠르게 타격할 수 있는 무기로 곡괭이보다 더 빨리 조약돌을 캐낼 수도 있고, 삽보다 더 빨리 흙과 자갈을 파낼 수도 있다. 하지만 당신은 greenschist나 limestone 같은 특별한 돌들을 위해 곡괭이가 여전히 필요하다.

## 토템

기지를 정했으면 조각칼을 만들어 높은 6칸 높이의 토템을 만들어라. 그들은 13x13x13 내에서 비컨(신호기)처럼 작동한다(note: 구역은 무한대가 아니라 큐브 모양이다). 이것들이 작동하기 위해서 토템 음악은 필요하지 않다. 아래에 있는 의식들을 보라. 조각칼을 손에 든 상태에서 스크롤하거나 오른쪽 버튼을 클릭하여 옵션을 순환하십시오.

아래부분은 토템 베이스부터 시작해야하여, 위쪽 나무를 선택해 배치한다. 유사한 모든 토템은 서로 겹쳐 쌓아야 한다. 즉, 1개 높이의 늑대 토템 5개는 힘I만 주는 반면 5높이 늑대 토템은 힘III을 준다.

* 박쥐 - 낙하 데미지 무효(1초)

* 블레이즈 - 화염 저항(3초)과 타는 동안 작은 회복

* 버팔로 - 신속(헤이스트)

* 소 - 느려짐과 저항 II

* 엔더맨 - 나이트 비전(14초): 깜박거린다면 나이트비전이 곧 끝난다는 경고이다.

* 말 - 속도

* 오셀롯 - 크리퍼 폭발 방지

* 돼지 - 행운 (엔더맨과 몹의 드롭에 영향을 준다)

* 토끼 - 점프 강화

* 거미 - 벽타기 (블록을 사다리가 있는 것처럼 처리한다.)

* 오징어 - 수중 호흡

* 늑대 - 힘

### 토템 팁

* 6개의 말과 1개의 엔더맨 + 1개의 오셀롯을 당신의 베이스 전체에 놓아라. 6칸 높이 늑대와 6칸 높이 소를 기지의 입구에 놓아 적을 막아라.

* 밤중에 그림자 생명체을 사냥할 때에는 토템 베이스와 엔더맨 토템을 근처 나무로 조각하여 나이트비전이 일정하도록 하라. 속도 향상을 위해 그 지역이 늪지대라면 말 토템을 추가하라. 아니면 늑대 토템을 사용하여 그림자 야수와 싸우거나.

* 점토, 소금 등을 캐기 위해 물속에서 채굴할 때는 나무 원목을 가져와 오징어, 엔더맨, 버팔로 토템을 만든다. 당신은 정상적으로 숨을 쉬고, 보고, 평범하게 채굴하는 것을 볼 수 있을 것이다.

## 농사

* 퀘스트를 위해 농지를 얻기 위해 농부와 뼛가루를 교환할 필요가 있을 때, 그것을 한 번으로 제한하라. 농지를 더 쉽게 얻기 위해 흙과 뼛가루를 조합하라.

* 에이지1이 이제 열렸으니 작게 보관하고 뼛가루를 쓰면 된다는 것을 상기하고, 나중에 큰 농장으로 떠나면 된다. 또한, 마을들은 종종 이미 땅을 갈아놨다. 비록 당신이 그곳에 도착했을 때 이미 일부가 사라졌을지라도, 키 큰 잔디/다른 식물들이 그 위에 있는 것들은 여전히 농지로 유지되어 있을 것이다. 식물을 부수고 즉시 씨앗을 심으면 식물이 튀지 않는다. 또한 에이지 1 이전에 말 끝에 쟁기를 달고 땅을 갈 수 있다.

* 부싯돌 작업칼을 사용하여 관목(shrubs)을 즉시 제거

* 흐르는 물도 농지를 기름지게 한다

* 강과 해양 바이옴에만 물이 무한하다.

* 삽으로 귀찮게 하지 마라: 대신 정원용 모종삽을 만들어라. fisherman's strainer에 넣은 미끼를 물 때가 되면, 네가 한 걸 보고 기뻐할 거야.

* 거대한 뼈 골격(단순하게 한 줄로 누워 있는 뼈 덩어리들)을 찾아다니며 그것을 갈아서 뼛가루를 많이 얻어라.

* 농장 근처에 드럼을 치고 **자프키엘 왈츠(Zaphkiel Waltz)**를 해서 **반경 6칸** 내의 식물이 미친듯이 빨리 자라도록 하라.

* 동물을 기르고 끈을 여우롭게 확보하는 것은 매우 중요하므로 밀과 목화 씨앗에 집중하라.

* 당신은 목화 씨앗을 땅에 던질 수 있고 그것은 약간의 시간이 지나면 씨앗이 떨어지는 새로운 목화 식물을 재배할 것이다. 농지 없이 큰 목화농장을 만드는 쉬운 방법이다.

## 홈스테딩

* 빈손으로 동물을 쉬프트+우클릭하여 주워서 운반할 수 있다. (마을주민, 말 또는 다 큰 버팔로는 들 수 없음, 1⁄2초간 오른쪽 클릭)

* 땅 위에 뗏목을 놓고 그 근처에서 두 마리의 동물을 유인하거나 배치하면 뗏목을 탈 것이다. 이렇게 하면 아직 번식할 수 있는 상태에서 움직이는 것을 막을 수 있다.(경고: 이것은 약간의 렉을 일으킬 수도 있고 그렇지 않을 수도 있다.)

* 동물 우리를 위한 울타리 치기

    * 와일드베리 덤불(Wildberry bushes) (참고: 때때로 동물들은 덤불 속을 미끄러지듯이 지나갈 수 있다.)

    * 2개의 흙으로 흙 반블록을 만들어라. 한블록 아래로 파고 우리 주변에 반블록을 놓는다

    * 돌 담장(Stone walls)

    * 나뭇잎 블록

* 집어든 달걀을 떨어뜨리고(던지지 않고) 자프키엘 왈츠(Zaphkiel Waltz)를 수행하면 100%로 부화를 할 수 있다.

* 봄의 의식(Rite of spring)은 마을주민, 동물, 식물을 위해 사방으로 8블록 떨어진 곳까지 효과를 준다.

* 닭 드롭아이템의 수집은 닭 밑에 나무 호퍼 + 상자을 넣어 자동화할 수 있다.

* 버팔로는 밀로 번식할 수 있기 때문에 당신은 계속해서 소를 찾고 의식을 행할 필요가 없다.

* 소와 돼지를 몇 마리 찾은 후, 빨리 밀을 공급받기 위한 많은 양의 뼛가루을 얻기 위해 군집된 뼈 블록을 탐험해보라.

* 생가죽(Pelts)은 에이지 1 때 접착제(glue)를 위해 유용하다.

## 자동화

* 나무 호퍼를 쵸핑 블록 반대편에 놓고 자동으로 나무를 놓기 위해 아이템을 던져 넣어라. 이것은 stone anvil에도 효과가 있다.

* 나무 호퍼를 사용하여 가죽(나중에는, 종이 등 또한)을 건조 랙에 넣고 뺄 수 있다. 출력을 단일 상자으로 "체이닝"하거나 "파이핑"할 경우, 즉 입력을 위한 하나의 상자가 있는 경우, MK2 호퍼를 사용해야 한다.

* 건조 랙을 자동화하기 위해 호퍼를 사용하는 대신, 수동으로 가죽을 교체하는 수고를 들여 호퍼를 병렬화하여 처리량을 늘릴 수 있다. 그냥 건조 랙 벽을 만드세요.

* 나무 호퍼는 초기에 구할 수 있으며, 에이지 0, 에이지 1의 완전 자동화를 위해서는 10-20개 정도가 필요할 것이다. Mk2 호퍼는 상자로 부터 아이템을 가지고 올 필요가 없다. 왜냐하면 상단에 4개의 스택까지 놓을 수 있기 때문이다. 2개의 호퍼만 체이닝으로 묶어 일종의 파이프(pipe)를 만들 수 있다.

* 그릴은 최대 16개의 아이템을 처리할 수 있다. 자동 추출을 위해 에이지 1을 기다리면 똥 파이프(Dung Pipe)가 가열 및 당기는 작업을 수행하는 플레임 호퍼 대신 측면으로 물건을 꺼낼 수 있다.

* 더 적게 치고 각 슬롯에 스택을 보관할 수 있는 craft stump mk. 2로 업그레이드하십시오. 비우려면 빈 손으로 각 아이템을 우클릭하십시오.

* 여러분이 홀스 파워(horse power)의 동물에 얻길 원할 때, 말/버팔로/라마가 필요로 하는 7x7 구역 주위에 9x9 벽이 있어야 한다. 돌 울타리, 베리 덤불 또는 2블록의 높은 벽을 사용하라. 그렇지 않으면 일을 끝낸 후에, 길을 잃고 헤매며 줄을 끊는다.

* horse grindstone이 7x7x2 영역의 위쪽에 있는지 확인하십시오(눈높이에 있도록 그 아래에 블록을 하나 더 넣으십시오). 약간의 조작이 필요하지만 당신은 mk2 호퍼와 상자로 chopper, grinder, 그리고 pressing block의 입력과 출력을 자동화할 수 있다. 단지 그것이 말을 타고 다닐 때 그 길에 있지 않도록 해라.

* 바닐라 늑대들과 버팔로는 빠른 말로 작동되는 당신의 기계를 작동시키는데 가장 좋다.

* 짐승이 일을 더 빨리 하기 위해서는 흙이나 잔디에 삽으로 우클릭하여 잔디길을 깔아라.

* press와 grindstone은 판자와 막대기를 많이 공급받는 데 원재료가 보다 훨씬 덜 필요하다. 호퍼 입력 및 추출로 chopper의 우선순위를 정한다.

* 가죽은 wooden basins(?)으로 좀 더 빨리 만들지만 여전히 수동이다. 그러나 당신은 각각이 휘젓는 애니메이션을 거치기를 기다리는 동안 6개의 basins을 병렬로 저을 수 있다.

* basin에서 가죽을 만들 때는 만들 때마다 소금 1개 생가죽 3개만 있으면 된다. 나중에 무두질할 때(tanned)도 마찬가지야; 건조한 가죽 3개당 resin 1개면 돼.

## 영양

영양 모드는 균형 잡힌 식사를 하도록 장려하며, 음식을 먹는 데 의미있는 버프를 제공한다. 재료의 공급 방법은 농사와 홈스테딩을 보라.

* 영양을 빨리 끌어올리려면 밀스톤[BetterWithMods]과 함께 핸드크랭크를 사용하여 배를 고프게 하여 남는 음식을 줄인다. 이 속도를 높이기 위해 여러 개의 크랭크를 사용할 수 있다.

* 영양 바를 최대치로 만들기 위해 어떤 음식을 먹어야 하는지 확실하지 않다면, JEI에 카테고리를 입력하여 음식 유형을 필터링할 수 있다. 예를 들어, 과일(fruit)을 찾는 것은 여러분이 과일 바를 증가시키는 것에 해당되는 모든 아이템을 보여 줄 것이다.

* 쌀빵(Rice bread)은 배가 불러도 먹을 수 있어 싸움 중 배부름 상태를 유지하거나 곡물 영양을 끌어올리는 데 매우 유용하다.

* 가죽을 만드는 것과 같은 방식으로 basin으로 더 쉬워지는데, 반죽은 1개당 도우(밀가루) 3개, 소금 1개씩이다.

* 이것은 당신이 치킨 스튜를 위해 많은 접시들을 만들기 위해 가마솥(cauldron)과 더 큰 식사를 만들고 싶을 때 유용하다. 이것들은 쌓이지(stack) 않기 때문에, 인벤토리 공간을 절약하기 위해서, 여러분이 기지에 있을 때만 먹어야 한다.

### 만들기 좋은 음식:

* Pork dinner: 구운 고기 + 구운 감자 + 당근 **3% Vegetable, Protein**

    * 가마솥이 여분의 당근을 요리할 때 최소한의 당근만 넣도록 조심해라. 

    * 몇몇 유튜버는 솥에 불을때기 위해 파란 불꽃이 필요하다는 것을 보여준다. 이것은 사실 (대부분?/모든?) 조리법에는 필요하지 않다.

* Tasty Sandwich: 모든 종류의 구운 고기 + 빵 **3% Grain, Protein**

* 쌀(Rice) **(매우 많이 먹을 수 있음): 1% Grain**, 무시해도 될 정도의 배고픔, 0 포화도

* Cooked Shark Meat: 비록 이것이 **Protein (3.5%)**만 채울지라도, 그것은 포화 한도가 없고 당신의 영양바가 가득 차 있더라도 언제든지 먹을 수 있다. 전투에서 지속적인 HP 회복이 필요할 경우 좋다.

## 전투

* 만약 평화롭지 않은 플레이를 하는 것에 너무 스트레스를 받는다면, 당신은 에이지 1 부분을 제외한 모든 부분을 평화로움 단계로 바꿀 수 있고 여전히 에이지 4까지 갈 수 있다. 아비셜 바이옴에서 생성된 아비셜 몬스터로 부터 그림자 보석이 필요할 겁니다.

* 크리퍼에 가위를 사용하면 폭발하는 것을 막을 수 있다.

* 몹은 이 모드팩을 통해 진행함에 따라 견고하게 성장합니다.

* 불붙은 횃불(lit torch)로 적에게 불을 질러 공격하라.

* 가장 좋은 무기는 6의 피해와 5의 공격 속도(높은 것이 좋다)를 가진 곰 발톱 팍셀(Bear Claw Paxel)이다.

* 2위는 3의 피해와 5의 공격 속도의 돌 몽둥이다. 채굴에도 빠르다.

* 3위는 검처럼 좋은 부싯돌 작업칼이다.

* 진흙은 적당한 게임 초반용 범위 무기를 만들 수 있다.

* stone-braced wooden shield를 만들면 다크랜드에서의 대처가 훨씬 쉬워질 것이다.

* 토템 조각칼은 에이지 0을 열자마자 사용할 수 있다. 토템 베이스와 오셀롯 토템을 내려놔라 그것은 각 방향 5블록에서 크리퍼로 부터 보호할 수 있다. 크리퍼는 사정거리 내에서 폭발하지 않는다.

* 뛰는 것을 좋아하는 사람들은 영양과 농사에 주목해라. 속도 3, 힘 1, 저항 1을 얻을 수 있으며, 회복을 위해 버프(nourished)를 받을 수 있다. 4개의 영양 바를 모두 갖추면 20개의 하트를 얻을 수 있다.

* Totemic의 보스 Baykok을 무찌르는 건 가능한 한 빨리 하는 것이 바람직하다. 그의 행동양식은 대부분의 표준 몬스터와 비슷해서 1블록의 틈새에서 다리를 공격하면 쉽게 화를 낸다. 앵무새는 Jungle, Swamp, Savannah 생물에서 발견된다. 만약 당신이 독수리뼈 휘파람을 불어야 할 앵무새를 찾을 수 없다면, 에이지 1까지 기다렸다가 어비셜크래프트 의식을 이용하여 앵무새를 소환하라.

* 그림자 보석을 얻을 때, 6칸 높이의 돼지 토템(토템 베이스 1개 + 토템 5개), 말 토템(속도 3개), 늑대 토템(힘 3개)을 설치한다. 각각 1개씩만 필요한 오셀롯(크리퍼 무력화)과 엔더맨(나이트비전) 토템을 추가한다.

* 희생 단검(sacrificial dagger)과 피의 제단을 함께 사용하면 대부분의 적을 즉시 죽일 수 있다.

## 인벤토리 팁

* 상자(chests) 대신 선반(shelves)을 만들어라. 그것은 12개 대신에 16개 아이템을 가질 수 있고, 인벤토리 벽에 좀 더 친절하다. 참고: 현재 Quark의 Drop-off 버튼과 함께 작동하지 않음 (아래 참조).

* 가죽을 만들 수 있을 때 소지품을 보관할 수 있도록 백팩을 제작하십시오.

* 백팩을 받은 후 36개의 슬롯의 돌 백팩에 으로 바로 연결하십시오. 나무로 업그레이드한 가죽 백팩을 제작한 후 돌로 제작하여 업그레이드 하십시오.

* 카트(Cart)는 당신이 쉬프트 우클릭할 때 더블상자 역할을 하므로, 단연코 최고의 에이지 0 스토리지 옵션(부피가 큰 경우)이 된다.

    * Astikoor 단축키로 말에 부착하십시오. 기본적으로 R키.

    * 참고: 탐사 후 Drop off를 사용하려면 인벤토리를 여십시오.

    * 멀티플레이어의 클레임 보호에 의해 카트가 **보호되지 않는 것**에 유의하십시오.N

* 근처에 이미 상자에 있는 물품은 시프트를 누르고 인벤토리에서 드롭오프 버튼을 클릭하면 넣을 수 있다. 여기 드롭오프 버튼을 참조하십시오. https://quark.vazkii.us/ 이것은 당신의 상자에서 이미 찾은 물건들을 정리하기 위한 것으로 탐험 후 아주 좋다.

    * 제한된 아이템도 보관할 수 있다. 핫바나 인벤토리에서 선택하려고 하지 마십시오.

* 스트레이너 박스는 호퍼가 붙어 있는 일반 상자의 역할을 하므로 말 그대로 무엇이든 던질 수 있다.

## 토템 

토템 의식은 다양한 효과를 얻기 위해 타이머가 끝나기 전에 악기를 만들어 음악를 연주해야 한다.

튜토리얼 비디오: [https://www.youtube.com/watch?v=NXXumiUuZlw](https://www.youtube.com/watch?v=NXXumiUuZlw) 

**악기 근처에 토템이 필요하다**, 그렇지 않으면 의식은 결코 시작되지 않는다.

특정한 순서로 악기를 누르는 것으로 의식을 시작한다. 의식이 시작된 후에는 올바른 순서로 악기를 치십시오.

* 의식을 활성화할 때 각각의 악기는 그것이 만들 수 있는 정해진 양의 음악을 가지고 있으며, 대부분의 의식을 완성하기 위해서는 여러 개의 악기가 필요하다(즉 6개 이상의 드럼과 2개 이상의 풍경을 만들 것). 독수리 뼈 > 징글 드레스 = 드럼 > 짤랑이 = 풍경 > 플루트

* 몇 번 연주된 후에도 그 악기는 '보링'이 되지만, 그 후에도 여전히 그것의 최고 '음악'의 3⁄4에 기여한다.

* 여러분이 해야 할 첫 번째 의식은 주입된 플루트를 주는 의식인데, 이것은 여러분이 연주할 때마다 드럼이나 짤랑이뿐만 아니라 무작위로 연주하게 만든다.

* 각각의 악기는 다시 연주하기 전에 쿨다운이 있다. 3개 이상의 플루트/짤랑이을 저글링하는 것은 가능하지 않지만, 다른 것들의 쿨다운을 기다리는 동안 여러 개의 드럼을 둘 수 있다.

* 짤랑이로 드럼을 연주하면 두 악기를 동시에 작동시킬 수 있다. 동시에 당신은 즉시 플루트를 사용할 수 있다.

* **농장 근처에 악기 세트를 놓고 미친 듯이 빠른 식물 성장을 위한 자프키엘 왈츠 의식을 행하라.**

* 징글 스커트착용 하여 크게 향상시키십시오. (3개의 뼈, 3개의 사탕수수!) 움직임과 함께 작동하므로 드럼을 일렬로 놓고 스트래핑을 하는 것이 가장 좋다. 당신은 또한 정말 원시 부족 처럼 뛰어다니는 것을 느낄 수 있다.

* 일단 뼈와 사탕수수를 충분히 얻으면, 풍경을 만들고 나뭇 잎 아래에 놓아라(부싯돌/뼈 가위는 잎을 자른다).

* 비가 싫어? 드라코닉 에볼루션 블록을 기다리거나 관리자 명령어로 치트를 치는 대신 마른 의식(dry ritual)을 행하라. 시끄러운 비를 막을 수 있는 기막힌 낮은 수준의 기술(low tech)이다.

* **말**을 포함한 대부분의 동물들은 **봄의 의식**으로 번식할 수 있다. 동물을 기르는 데 황금 당근이나 사과를 사용할 수 없다.

* 새로 만들어진 버팔로는 다 자라지 않아서 바로 번식할 수 없다.

## 어비셜크래프트(Abyssalcraft)

* 다크랜드 참나무는 4개의 다크랜드 바이옴에서 발견되는데, 각각 남쪽으로 5000블록 이상에서 발견된다.

* 낮 동안 가서 토템을 만들고, 늑대 토템으로 가득 채우고, 가급적 돼지 토템을 만들어 드롭율을 높여라.

* 그림자 괴물의 어둠 능력은 실명이다. 벙커로 유인해서 무릎을 공격하는게 최선이야.

# Age 1

이 시대는 청동의 탐사, 두 가지 마법 모드, 즉 블러드 매직과 아비셜크래프트, 그리고 최소한의 Better With Mods의 구성에 초점을 맞추고 있다. 물건을 넣을 수 있는 공간이 있는 좋은 기지를 계획하는 아이디어를 원한다면 다음을 살펴봐라. [Asgard 서버 둘러보기](https://www.youtube.com/watch?v=Lowt8ttvr8Q)

## 지금 무엇을 할 수 있는가?

* 제작대가 추가 되었다.

* 바닐라 상자가 열렸으니 이제 네 물건을 다시 정리할 시간이다. 위의 드롭다운 버튼을 다시 불러오면 정리 작업과 개인 인벤토리 정리를 유지하는 데 도움이 될 수 있다. 크레이트와 저장 서랍은 드롭오프 기능을 지원하지 않는다.

* 헌팅 디멘션을 열었군. 헌팅 디멘션 들어가려면 쉬프트를 사용하라. 이끼가 끼면 생성되는 몬스터가 변한다. 위의 방음 블록을 사용하여 배경음을 없애거나 기지에서 멀리 떨어진 곳에 만들 수 있다.

* 주석 주괴로 Chisel and Bits의 조각칼을 제작한다.

* 얼음을 찾아 조각을 가져가고 배치함으로써 chisels and bits로 물을 놓을 수 있다.

* 수로(Aqueducts) 튜토리얼: [https://www.youtube.com/watch?v=S7lRbhtiluw](https://www.youtube.com/watch?v=S7lRbhtiluw) 

* 3개의 수로 블록을 일렬로 세우고 각 끝에 수원을 배치하면 무한 물을 만들 수 있다. 가운데가 수원이 될 것이다.

* 기어와 같은 몇 가지 아이템은 현재 제작법이 더 쉬워졌으므로, 제작하기 어려웠던 이전 시대의 아이템에 대한 제작법을 다시 한 번 확인해 보십시오.

* 돌 완드(Stone wand)를 사용하면 플랫폼을 신속하게 구축할 수 있다.

* 빠르게 돌아다니기 위해 말을 와일드 도그 펠트 부츠로 교체할 수 있다(스피드 부스트, 점프 높이 추가, 낙하 피해 없음, 방어력 2-3개)

* 도가니(crucible)는 썩은 살점과 생가죽을 접착제(Glue)로 바꿀 수 있다. 횃불을 던질 수 있게 만들고, Better with Mods 나무 기어와 슬라임 부츠를 제작하는 데 유용하다. 블러드 매직은 피의 오브를 만들기 위해 주조 대야로 혈액 블록을 만드는 데 사용할 수 있으므로 16개의 살점을 가지고 있어야 한다.

* 저장 상자(나무 상자와 혼동하지 말 것) 또한 조용하고 쉬프트 우클릭을 사용하여 모든 아이템과 함께 모을 수 있다. 제한된 버전의 배낭으로 사용할 수 있다. 리소스 처리 또는 빌드에 이상적임. 드롭오프 버튼은 이 버튼과 함께 작동하지 않으므로 Primary chest에 사용해서는 안 된다는 점에 유의하십시오.

    * 또 다른 문제: 쉬프트 우클릭으로 대신 선택되므로 표지판을 부착하기가 어려움. 표지판을 다른 곳에 붙인 다음 Carry On을 사용하여 상자 위로 옮겨야 한다.

* 나무판자에 한 조각(chisel & bits)를 빼면 불이 붙지 않는다. 벽난로 옆 바닥이 불타는 것을 막기 위해 유용하다.

## 자동화

* 똥 파이프는 옆으로 아이템을 뽑아 떨어뜨릴 수 있다. 이것을 화염 호퍼 대신 그릴에 사용해라. 그냥 똥 파이프로 아이템을 떨어뜨려 나무 호퍼에 넣어라.

    * 이중 상자 양쪽에 똥 파이프가 작동함

* 눈사람과 멜터를 사용하여 많은 대야를 빠르게 채우는 작업을 자동화하십시오.[https://m.imgur.com/a/A21bgOM](https://m.imgur.com/a/A21bgOM)

* 괭이를 만들고, 정원을 가꾸어라. 당신이 풀에서 괭이질 하여 찾은 벌레들은 시간이 지나면 죽게 되므로 그것들이 제공하는 수분은 일시적이라는 것을 기억하라.

    * **목화(실)과 Hemp(Hemp Fiber)** 및 **당근/밀(좋아하는 단백질)**의 우선 순위 지정

## 헌팅 디멘션(Hunting Dimension)

8개의 나무를 돌 검으로 다듬어 포탈 프레임 블록을 얻는다. 포탈을 만들고 칼로 작동시켜라. 이 월드는 선택된 유형의 몹들만을 생성한다. 포탈에 진입한 후 **움크려서 입장**하라.

참고: 여기의 몹들은 좀 더 건강하다.

### Creeping Moss

Creeping moss is a craftable item that allows the player to change the type biome of a chunk in the hunting dimension. Creeping moss can be crafted by surrounding a block of mossy cobblestone (just cobble crafted with vine) with 8 vines, leaves(use flint shears) or saplings. Once you have crafted the creeping moss, you can sneak and right click to set the moss to the biome you are currently standing in. Once the desired biome has been set, you can go into the hunting dimension and right click with moss (without sneaking) to apply the biome changes. Keep in mind that creeping moss can only change the biome of a chunk in the hunting dimension. Also some of the biomes that are harder to find, like ice plains, can be obtained using some special crafting recipes.

Additionally, you can use the moss to **find out what biome you are currently in**, as it spits out the selected biome into chat. This can be helpful because the F3 screen does not show biome in age 1.

* Make a mob grinder by placing a spider + ocelot totem, 1 layer for you to walk, then a wall of fence, with punji sticks the next layer out. The spider totem lets you climb up the walls of your tower![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_3.jpg)

* Punji sticks (sugar cane) make effective mob killer. They can be placed on the sides of blocks to prevent spiders from climbing over, as [well as hoppers](https://i.imgur.com/VP5pTO9.png) to automate collection

* **Surround this base with 1 layer of Mk2 hoppers, then a layer of wooden hoppers to collect the drops**

* If breeding a bunch of animals for pelts isn't your thing you can AFK and Farm for quite a bit of zombie flesh, melt it down to blood (16 flesh per block) and get some slime boots.

## Prospecting

* Having trouble finding ore? If you have a desert nearby, every stone you find on surface is a ore cluster. Mine it with a pickaxe to get the underlying cluster. Find the center of the chunk and dig down.

* Every ground stone in a desert or under water is an ore sample. Remember that deserts are north/south.

* The Ore is setup in large veins, think 16x16ish. Locate the chunk a vein is in by finding a Sample on the surface. F9 to see the chunk borders. Use the prospectors ore and right click on a block. If an interesting ore is within 48 blocks straight down, then the prospector's tool tells you how many it encountered along that path. Mine in that direction and prospect around to hone in on where the ore is.  As of 3.0.4 ores are positioned in any of the four corners of the chunk.  To find the ore more easily, look up the max Y position it can spawn at, and mine out the chunk at that level. (Use the depth meter.)  Then point the dowsing rod straight down in the four corners until you get  hit on the ore.

* Make a 6 high **buffalo totem** when you find a vein to get **haste 3.**

* To make Tin, Copper, and Bronze you can either make a porcelain melter or a seared melter, the former is easier. You need to pour them into either type of casting basin, then use the stone anvil to get ingots. These melters don't make alloys and can be automated with hoppers, to the point of only manual activation of the faucet.

* Place a hopper above the stone anvil to automate placing ingots.

* Bronze leggings give armor 5 over leather's 2. But bronze chestplate has diminishing returns, only improving leather’s 3 to a mere 4.

    * You do not need to go ahead and mine every ore sample you find. If your inventory is full, or you have another plan in your head, then mark the sample using your Atlas for future collection.

## Blood magic

Blood magic mod is based on Life Points earned through sacrifice by blood. Initially you'll use your own HP to power it, and if you continue further into Blood Magic you can set up animal grinders.

* After crafting the Blood Altar, make a sacrifice dagger and stab yourself to fill altar with blood.

* You can put rotten flesh in the Melter to get liquid blood, 16 rotten flesh gives you a block which crafts into 4 blood balls. This is helpful bootstrapping in to Blood Magic as you don't need to create a full smeltery to stand in.

* If you want to store Life Essence in buckets later on, you are able to transfer, store & pour blood out of wooden barrels with faucets.

* When crafting the blank runes to upgrade the blood altar, the weak blood orbs don't get consumed when crafting. So you only need one block of congealed blood.

* Place the 8 blank runes 1 block lower than the altar and around it. This makes a tier 2 alter.

* If you want to continue further in Blood Magic follow the steps in this [lets player's video](https://youtu.be/Q0GNRxIy-1Y?t=27m57s)

* To automate crafting blank slates place a wooden hopper under the altar feeding into a primal chest where all slots are filled with other things (cobble for example) other than 1 slot which has a blank slate. Thus when you place stone in the altar the hopper fails to pull the smooth stone out, and instead only pulls blank slates. You can now feed the altar with a chest+hopper that inserts smooth stone. Know that the altar has a cap on blood but it is automation nonetheless.

* Advancing into Blood magic requires having tartaric gems with lots of will. You'll want to make a sentient sword which acts like a snare to capture will. This sword does more damage when you have captured more will, so expect a bit of investment at first. 

* When you upgrade to higher tier tartaric gems you can pour the old will into the bigger gem by holding and right clicking the smaller gem. This sucks out the will and places it into any available tartaric gem you have in your inventory.

* Know that the sentient bow can do great damage, but uses normal arrows. Follow this path if you feel comfortable with your supply of feathers and inventory space.

* The Beneath is a great place to farm mobs. Use totems to offset their doubled health.

## AbyssalCraft

AbyssalCraft is a large mod opening 4 dimensions, growing knowledge about the great old gods. As you progress through the mod item's names will unlock. Its power source is received from statues that direct power into firstly your necronomicon, then later you can store it into containers.

* First and easiest is finding an abyssal biome (head north) and killing shadow monsters for the gem shards.

    * To make farming these gem shards easier bring wood for 3-4 totems, each 6 tall.

    * You can also use your hunting dimension with some creeping moss to quickly access an Abyssal biome.

* Next is finding and farming a Shoggoth lair. They seem more likely around river and swamps

* Alternatively there is a villager trade to get you shoggoth flesh

.![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_4.png)

* Shoggoths break blocks of less than 4 hardness. Make some sturdy stone to block the in 4 cobble + 4 stone = 4 sturdy stone.

* They seem to climb similar to spiders. They don't deposit their sludge on bottom half slabs or string. They require a 3x3 hallways to move. However a bunch of them can shove one into a 2x3 hallway. If you are quick you can build a wall right at the bottom of the stairs leading into their lair before they manage to escape. You will get hit at least once since they can hit through a 1 block thick wall but focus on establishing a wall first and pretty it up later. You can build a 3x3 killing chamber at the top of your wall. Use bottom half slabs for the floor and don't bust the wall leading to the lair until your ready for them to come through. Opposite of the wall you can build a 2 block thick wall with a 1 block high slit to slash at them through it. To collect the drop swing underneath and bust out one slab, replace it and repeat until you have all the drops. Mk2 hoppers can suck the items through the slabs for a much safer alternative.

* As long as you don't go in far enough to attract the attention of the Shoggoth in the back, you should have a endless supply of them. My first attempt I went for a killing hole in the floor and it didn't work out very well since that angered all of them which meant no new Shoggoth could spawn after they were all dealt with.

* Punji sticks don't work on them since they climb walls. Lighting them on fire with fiber torches is very slow. Slashing them is slow and consumes roughly 6 swords to get 1 stack of their drops.

* If you're playing on a server and the Shoggoth lairs have been emptied, you can trade for flesh with villagers, or with the Farming for Blockheads Market

* Dealing with Shoggoth

    * Since they spit acid, which can possible destroy your grave it is best to deal with them in water

    * Make a squid totem and lure them into the depths where their slime has no effect.

    * Spear has a bigger range than other weapons and it can be used to punch them without being touched even once. Combined with wolf totem it does a massive damage.

* There is a common bug where Shoggoth either do not spawn or spawn unhittable. If this happens, you can craft the Market block cheaply, and then mine their bases to trade for Sloggoth Flesh. 24 Monolith Stone will get you one flesh, and with 8 Shoggoth Flesh you can craft a statue.

* When there are six shoggoths outside, they will erect a monolith with a statue on top. Beware! These towers will summon shoggoths on their own! You can break the statues on top to stop this.

* After crafting the statue place it **away from your base** and hold the necronomicon. The statue will send power into your necronomicon at 5 PE / 5 seconds taking about 15 minutes to get the 1000 needed. Randomly you may get struck by lightning and even explosive lightning, and sometimes wither effect. After getting 1000 points that area will have gotten tainted and will produce abyssal mobs. A shovel can quickly remove sludge produced by Shoggoths. They don't poop ooze on half slabs or Abyssalcraft blocks.

* The negative effects increase with how much charge is in the necronomicon. Crafting an energy pedestal so you don't need to be around the statues while charging is recommended.

* The lightning effect destroys weak blocks like the shoggoth. Build a cage around your statue setup out of monolith stone.

* Need to collect a lot of shadow gems, but hunting shadow monsters is too slow? One of the negative effects of charging your Necronomicon causes many such creatures to spawn. If you built your energy pedestal in a hole in the ground, some monsters might even spawn inside the walls and suffocate. Their drops will then bubble to the surface, where you can collect them for free!

* To find Corallium look around for a biome looking like this or in a water biome and at least 40 ground level or below and then use a Weak Dowsing rod until it reports with finding Corralium.

*  ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_5.png)

* Another trick is to look out for bits of solid land that the Atlas reports as being Ocean. The Atlas looks at the biome of the chunk, and those bits of land are actually Ocean biomes, where Coralium spots, but that you can nonetheless safely explore and dowse on foot.

* When progressing in Abyssalcraft, beware the second dimension, the Dreadlands. Mobs there apply Dread Plague on hit, which while painful, will also convert the biome of the x/z point you are standing on to Dreadlands whenever it does damage to you. It also likes to refresh itself often. Try to avoid bringing the Dread Plague out of the Dreadlands, as if you bring it to the overworld and dreadlands enemies spawn in an un-torched spot, you might have a problem. For this reason, I would not recommend making Tinker's weapons out of dreadium, as that’ll spread the plague to enemies on a critical hit.

* The dreadlands infused powerstone require a refined coralium pickaxe to mine.

## The Beneath

Your goal is to get a handful of Black Quartz (for actually additions) and Aquamarine (for Astral Sorcery)

* To get the needed Bronze Block know that the Melter can't alloy tin and copper. You can however use the kiln to get bronze, then melt it down in the Melter, and pour into a block.

* Darkness in the beneath hurts, so take a couple stacks of torches. Take a flint workblade to shrubs and leaves to get loads of twine and sticks. Craft fibre torches, light them on a fire, then craft with 2 sticks to make Totem torches (brighter). You'll also want a fair bit of throwable torches (Glue + normal torch).

* It can be helpful to keep multiple totem whittling knives on your hotbar in dangerous areas like The Beneath. Keep each one set to a different aspect. Being able to make wolf and cow totems quickly and easily while kiting mobs around can be a life saver.

* Your "Beneath" teleporter can be moved. Either dig down or pillar up before placing and entering the Beneath. See next note to know when to stop.

    * It is better to pillar up in the Overworld rather than the beneath as spirits can push you off ladders and pillars.

    * Remember to use cobblestone for your pillar as you can use a Flint Workblade to carve out a ladder when you climb back up. Obviously you can drop into water for a quick decent or carve a totem base and bat totem five or more blocks above the floor (to give it time to activate before impact)

    * You can pin torches to a side of ladder blocks making it safe from pushing you off by spirits. It's better than pillaring up in the Overworld.

* Black Quartz can be found from y = 2 to y = 100, Aquamarine can be found from y = 150 to y = 246 

* Before digging to a set Y area dig up till you see a cave. On the top of the caves you have a good chance of finding a few patches of ores. Aquamarine comes in veins of 12. Use a Night Vision totem to more easily see the patches on the ceiling.

* When you first get into the beneath, mark your spot on your atlas, because it is a pain finding your way back.

* You can speed down a strip mine by running and jumping the whole way

* 11 Black quartz can be used to make black quartz AIOT

    * It is all the tools combined and the best age 1 weapon. 

    * Has **1100 durability**

    * **Can be repaired** with 3 Black quartz, a real bargain!

* Upgrade your chestplate and helmet to black quartz, and if you didn't get Bronze leggings, upgrade those too.

* Don't convert all of your Crushed Black Quartz into Black Quartz.  You’ll need some of the dusts later to create Black Iron Ingots.

* If you have a problem in finding caves on bottom of beneath while searching for black quartz just dig down below y=20 and do the normal branch mining. You can save some digging if you use your dowsing rod to target your branch mining.

* In age 2 you'll have access to the Astral Sorcery Cave Illuminator (doesn’t require anything more than the luminous crafting table and some resources). It places light source with some radius, which don’t go away if the illuminator gets moved.

## Better With Mods

* Before we get into Astral Sorcery we need a BetterWithMods Saw to get the bark off of Mulberry wood.  Here is what a Mulberry tree looks like:

 ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_6.png)

* After making the Saw you'll need to get started on the water wheel, as the hand crank doesn’t work on the saw. You’ll need ~36 hemp. Get the top of hemp plant but leave the base planted. 

    * You can use a half stack of bonemeal. Know that breaking the hemp plant in the bone mealed state has 100% of dropping 1 seed and 0% chance of 2 seeds.

    * Or take advantage of Totemic "Zaphkiel Waltz" Ceremony to grow a long-lasting supply of them

    * Gears are really cheap now. Simply saw planks -> panel -> siding -> corner -> gear

* Follow the main quest Guide to a waterwheel and gearbox and make 3 wooden axles (1 for the water wheel to be based on, which can connect directly to the gearbox (image shows an axel between them, useful later on), one to deliver power to the saw.

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_7.png)

* Completing the saw also makes Wooden gears much cheaper as you can now make them from wooden corners (process a plank, then the sidings, then the mouldings. 16 gears from a single plank!).

* The saw also kills mobs dropping player-only drops.

* You can tell the gearbox and axle are connected right by seeing the axle turn. Right click the gearbox to move the input side (the one with the cross on it) to face the waterwheel.

* Making a 4th axle allows the mill stone (power must come from top/bottom of millstone) to be powered here instead of by hand.

* You don't need the axle between the gearbox and waterwheel, but is helpful later when needing the space to surround the mill stone with Mk2 hoppers.

* Mechanical power is binary, it's either on or off. You can split power as many times as you want to power your stuff.

* Because Better With Mods drops all products on the ground, Mk2 hoppers are your friend since they can be chained together (unlike Mk1 hoppers, because they don't have an internal inventory). Alternately,  put it over some water you've removed, thus creating a natural whirlpool into a strainer which stores items, or like this when you can place water.
![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_8.png)

### Astral Sorcery beginnings

Astral sorcery is based on star light feeding into bigger and bigger altars and actual star gazing. Getting the luminous crafting table opens the next age. This mod is gated on aquamarine which is configured to come only from the top of the Beneath world, and Mulberry bark which can only be scraped off with a Better with Mods Saw, and a Necronomicon Ritual taking 1000 PE (waiting in front of statue with book in hand for 15 minutes, or with a Energy Pedestal).

* The meat of astral sorcery is covered in [Age 2: Astral Sorcery](#heading=h.q8tahli9nh0b)

# Age 2

## Uncategorized Tips

* Not all of the [below](#heading=h.s3hykq23gasz) baubles need to be equipped to work.  Most will work as long as they're in the inventory.

* If you want to harvest any of the Low Grade Charcoal blocks, from the Dark Tower in the Twilight Forest for instance, do so before entering the next age as this will cause them to turn into netherrack.

* Torch launcher : Provides a large supply of throwing torches

* Monster spawners generate mossy cobblestone from regular cobble, making the mossy variant renewable.

* SevTech contains the mod "Despawnable Spawners".  This mod is set up to destroy spawners (the cage block) after it has spawned 400 mobs.

* Well Bucket - Creates water if next to a source block. Combine with liquid hopper to automate into a tank

* Think big, plan ahead, don't get stuck in a small base in ages 1 and 2 since age 3 involves a lot of multiblock machines that will require a lot of space.

* Save your iron, you will need a lot of it and it's not as common as in regular modded mc.

* Once you unlock JourneyMap, which is possible this Age, you can shift+right click  (NOT WITH AN EMPTY HAND, BUT WITH SOMETHING IN IT) on an ore sample to automatically create a waypoint. No more marking your veins manually in the atlas!

* If JourneyMap does not show up immediately after eating the JourneyMap Token, press 'CTRL+J'

* Sludge jello + pears(both betweenlands) makes amazing food(5% fruit, full saturation)

* A feeding trough (see if it can be fed with a hopper) will automatically breed animals until it is somewhat crowded

* There are three different backpacks (iron backpack, improved backpack, lurker skin pouch) and they all have their own hotkey. Use all three of them for quick access to your items.

* Nocturnal powder right clicked on the ground spawns lots of mobs, handy with vector plates in a mob grinder.

### Things to look out for

* If you see an Enderman you should absolutely try to kill him. Ender pearls are important.  Endermen will only drop ender dusts. You can smelt these in the melter and cast them to ender pearls using the pan cast.

## What you can do now

* Tinker's Crafting Station

* Armor Station

* Boat

* Books

* Slime Sling, and obviously the Slime boots/Wild Dog Pelt Boots you had available in age 1, so you don't die from flinging yourself

* Poor-mans flight via slime boots bounce + the charge ability from the tinkers longsword.

* Quartz Grindstone [Applied Energistics 2]

* Framed Storage Drawer

* Mine Iron, Gold, Lapis

* Ranged weapon, See Tinkers construct below

* Transport NPCs (excluding most mounts) without leads [Interdimensional Cage]

* Tinker's Tank

* Create Speed, Night Vision, Healing and Regeneration Potions with Rustic [Alchemy](https://github.com/the-realest-stu/Rustic/wiki/Alchemy).

* While a bucket of lava in the Melter won't melt Iron, it will melt gold. Pour that over a dirt chest to get a Gold Chest. Poor man’s ME system.

## Baubles

* Climbing Gloves : Let's you climb vertical walls.

* [Gluttony Charm](https://ftb.gamepedia.com/Gluttony_Charm) : Consume food instantly

* [Sleep Charm](https://ftb.gamepedia.com/Sleep_Charm) : Sleeping is instantaneous

* [Portal Charm](https://ftb.gamepedia.com/Portal_Charm)  Allows for instantaneous travel through dimensional portals

* Compass : The X and Z of the player

* Stopwatch : The movement speed of the player

* Depth Meter : The Y of the player

* Slimey Compass : Whether or not the player is in a slime chunk

* Chunker : The Chunk's X and Y coordinate

* Calendar : Month, day and year of the world

* Biomealyzer : Displays the name of the biome you're in.

* Super Sound Muffler : Allows for the muffling of certain categories of sounds

## Automating a Melter

* Use a simple Chest + wooden hopper to feed a Melter

* Get a Liquid Hopper to pull molten metal from the Melter

* Use a Lever to control multiple hoppers feeding into dedicated casts

## Liquid management

* A tower of clay barrels can hold 20 buckets

* A tower of porcelain barrels can hold 30 buckets

* A wooden barrel can hold 8 buckets. Place a lid and shift right click to put in your inventory. Doing so without a lid falls back to carry-on. It will collect rain water if left open to the rain. Breaking it empties the liquid.

* Liquid hopper has a 16 bucket buffer and retains liquid.

* Seared tank holds 4 buckets

## Which pickaxe to pick

To mine the Carminite reactor in the urgast towers you may need a diamond-level pickaxe.

### Tinker's Construct

These tools allow you to swap out parts, gain modifier slots the more you use them, and have a very large selection of materials to use. There are lots of abilities tied to each modifier, allowing a great deal of customization to fit your needs. These modifiers are not available until you reach age 3. [Here](#heading=h.ynpqna7qajwe) are useful parts listed and described.

#### Black Quartz

While a black quartz pickaxe isn't much to write home about, combining with the hoe, sword, axe, and shovel gives an AIOT tool (All In One Tool) with 1120 durability, and great damage. 1 black quartz repairs 370 durability.

### Betweenlands

Octine tools are better than iron: Mining Speed 6, 900 durability, can be enchanted

Valonite are as good as steel: Obsidian mining, mining speed 8, 2500 durability, can be enchanted

The Swift Pick: Obsidian mining, mining speed unknown, 2500 durability, can be enchanted

### Twilight Fortress

Ironwood Pick: Diamond level, Mining speed 6.5, 512 durability

Mazebreaker: Diamond level, Mining Speed 8, 1561 durability, Efficiency 4, Unbreaking 3, Fortune 2

Steeleaf Pick gets Fortune II, if crafted from Steeleaf (instead of finding it in chests). Nice to have before Tinker's Construct modifiers are unlocked. 131 durability.

## Best melee weapon

Astral sorcery crystal sword

Requires investing into building up 2 nearly perfect rock crystals. But this sword is as fast as a Tinker's construct rapier (crystal stats don’t affect the speed), can be enchanted with books and the refracting table, Infused for delivering a AoE  once every few seconds. Sadly must be repaired by soaking in starlight.

* Twice the damage of an iron sword.

* When combined with Power V, Sharpness V and elixir of strength[Betweenlands] vs full valonite dummy dealt 19 dps, or 17 times as much damage as an iron sword

### Enchanting

While the enchanting table is gated for later ages, the refracting table from astral sorcery is available. This let's you pick what enchants as well as making sharpness VII, power V available (higher than normal loot).

### Attunement

Astral sorcery let's you attune yourself with one of the conselations, 2 of which are good for battle: Amara and Decidio. See the astral sorcery section for how to level up in their perk trees for even more defense and damage

## Tinkers Construct

Note: Blank patterns require Sidings from the Saw instead of sticks.

* Make sure the pattern chest is touching both the stencil table and the part builder, otherwise you have to access it by clicking on the pattern chest tab.

* The crafting station is the block that allows the rest to be accessed as tabs in one UI.

* You can make **one-use-****casts by Melting clay** and pouring it over a stone part. Melting metal, and pouring it onto a  clay cast, consumes the cast in the process.

* Lasting casts can be made by pouring gold over a stone part.  These casts won't be consumed by future use.

* Make a stone nugget to create the nugget cast.

* Use a (clay, mud, seared) brick to create the ingot cast.  You could use an ingot as well, but that seems wasteful.

* Best bow

    * Crossbows and longbows can't be created until age 3 so short bows are the only solution.

    * Wood bows have nerfed durability, so Iron arms are the way to go. 

    * Damage arrows (**3.67 hearts** average observed, 50 arrows): **Bone **arrowhead, reed shaft, feather fletching.

        * This is easier to repair on the go than a slime arrow.

    * Endurance arrows (1.9 hearts average observed, **170 arrows**): Green slime crystal arrowhead, reed shaft, feather fletching

* Melee: A bone and flint mattock with bone handle does **as much damage as a diamond sword**

* [Here](http://tinkers-construct.wikia.com/wiki/Material_Stats) are the modifiers and descriptions

* Note that sharpening kits only repair. **Don't plan on getting obsidian sharpening kits** to upgrade your mining level

* Craft a battlesign with **cactus **as the tool rod to deal damage while blocking. Pair this with a **steeleaf** sign and a stack of steeleaf in your hotbar to become almost invincible to any attack.

#### Head 

**Bronze:** This is the first head you would want. It has a mining speed of 6.8 and the modifier 'dense' which together with a reinforced modifier(age 3) can give the pickaxe infinite durability.
**Naga Scale:** The drops from the first Twilight Forest boss can be crafted into a pickaxe with a mining speed of 8.9, but with a mining level of iron.
**Knightly:** This material is harder to get, but with a decent mining level and a mining speed of 8 and the highest durability: 1200. 
**Abyssalnite:** Abyssalnite is found in the many little shrines scattered across the Abyssal Wasteland (dimension). Once you reach this dimension these buildings are easily found and inside you will find one grey block with a ladder underneath it that leads to a chest with loot (mainly abyssalnite). It has a mining speed of 10.
**Refined Coralium:** Rarely found in the same structures as abyssalnite but can also be found underground as Liquified Coralium Ore. The veins are very small and very hard to find. The mining speed is 12. This material has the modifier ‘Coralium-Plagued’ which inflicts the Coralium Plague (not to be confused with the Dreaded Plague) on critical hits. Don’t use it as a weapon!

#### Blade

**Iron: **Easy to get with an attack damage of 4.**
Prismarine: **Prismarine offers 6.2 attack damage, but requires you to clear an ocean monument.**
Fiery: **Only available after defeating the Hydra or the Ur-Ghast in the Twilight Forest, but it is the blade with the highest damage: 7.6.

#### Binding/guard and tool rod

**Wood:** Wood repairs itself, but very slowly.

**Steeleaf:** Repairs tools with about 4 durability per second. It requires steeleaf to be in the hotbar (not consumed and the more the better!).
**Knightly:** The binding has a very high durability.
**Bronze: **Dense (see the Head section above).
**Sponge:** Gives silk touch. It's found in vanilla ocean monuments. 
**Prismarine: **Faster underwater mining. Watch out! The tool rod lowers durability drastically.
**Bone:** Gives bonus damage

### [Optional] Tool Forge

You can make a Tool forge by burning grout into seared stone and 4 Iron/Copper/Tin/Bronze blocks (Note: JEI only lists recipe with iron blocks, but the other metals do work).

* Stone on the other hand, doesn't require casts, and can be repaired easily. Recall parts can be swapped out when you get a full smeltery for better parts.

* Once in the twilight forest, steeleaf is a good material to use as it gives the tool a self repair when you have stealeaf on your hotbar with the tool (working for arrows as well). The speed of this increases as you gave more steeleaf on your hotbar, getting to the point where the tool can repair faster than you can damage it at this age.

* Make a **Bronze-Stone Hammer** and Stone Lumber Axe for quick mining and felling.

    * You can use a bronze head and a stone and/or wood plate to get the benefit of speed, durability, and Dense modifier while still easily repairing your tool.  You can upgrade once you have it unbreakable.

* The materials used in faceplates and heads can be used for repairing.

    * A wood faceplate gives ecological (self repairing) and is cheap to repair, at the cost of max durability

    * Stone is a bit faster and is common when mining

    * Iron gives magnetic (pull drops towards you)

    * Slime gives high durability, sporadically spawn slimes when mining, useful for the excavation modifier next age.

    * Stone makes it mine faster the lower the durability.

* Shuriken: these are reserved for age 3. 

## Interdimensional Cage

The Interdimensional Cage from Abyssalcraft allows you to transport Villagers, Mobs and Animals for a small P.E. cost. 

* The cage must be charged before use in an Energy Pedestal. 

* Right click to capture most NPCs, right click again to release.

* Villagers require a shift-right click for capture.

* Horses and Llamas cannot be captured.

* Each capture requires about 30 P.E. and the cage capacity is 1,000 P.E.

* Only one NPC may be caged at a time.

Materials

1000 P.E. + 8 Iron Bars + Shard of Oblivion(4 Shadow Gem + Transmutation Gem)

Transmutation Gem (10 uses, 1 is used in crafting the shard):

* 300 P.E.

* 2 Ender Pearl

* 2 Transformation Powder from the Twilight Forest

* 4 Aquamarine from the Beneath

* Coralium Pearl

## Blood magic

* The tier 3 altar requires either flowstone or sea lanterns, the latter is available to you in this age found in the oceans. Don't forget the totem with squid for water breathing.

* Sadly there is not much unlocked for you to make in blood magic in age 2, but the altar is technically buildable.

## Getting Iron

Iron (Hematite which has a brown color; Malachite (copper) is green) is now open, but your melter isn't going to get hot enough. In addition to tracking it down and mining it, you’ll need lava in either a porcelain or seared tank (matching your melter)

### Handling lava

Before venturing out to find Hematite, make a couple Seared Tanks or Seared Gauges.

Pick one of the following for holding lava:

*  As many clay buckets as lava you need

* A Between lands Bucket![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_9.png) made from Syrmorite holds lava

* Wood Barrels can hold up to 8000mb of Lava and can be shift-right clicked to store in your inventory. Lava will burn the barrel if left in the Overworld. It will also burn you if you stand next to the burning barrel (oops).
Placing a lid on the wooden barrel lets you pick it up into inventory.

### Hematite

* A 6 high buffalo totem gives you haste 3.

* If you got a Tinker's stone hammer, you can speed up mining Hematite by placing cobble and mining that.![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_10.png)

* You can melt iron by reconfiguring your melter to be heated by a Seared Gauge.  Seared tank won't work with porcelain melter, material type must match.  Note the automation section above to automate the faucet.

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_11.png)![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_12.png)

* Make a stone bucket and place in a table, then melt 2 gold or clay and pour to make a bucket cast. Pouring 3 iron gives you a bucket. Use gold instead of clay if you think you'll need more buckets.(the watering can consumes the bucket in its recipe)

## The Between Lands

Before we can make a smeltery (required for age 3 alloys, useful for efficient and mass processing of ores), we need to take the side quest of the Between Lands. Because it has its own wood and tool tech tree, you'll need to start from roughly scratch.

Goal: Obtaining a Aqua Middle gem found in Sludge Plains lakes

* Ring of Ascent to 100% chance drop from Betweenlands Bosses & will help you if you get overwhelmed by a swarm of mobs later on, especially wights. It basically provides creative-mode-flying but if you jump off a high ledge, gravity forces you downwards like a chicken, and you slowly float to the ground but with a cool leafy effect around you. You can also slowly float upwards but this is counter productive if you've kept the step-up ability to move up one block steps instead of jumping. **The Ring of Ascent relies on XP levels to function**, so if you have none, you will not fly. If you have many levels, you will fly for a while but it gets used up fast.

* The druids spawn when you enter the ritual area, giving you time to prep before the battle.

* Take the time to get slime boots when fighting the Druids. It turns their offensive spell against them. Alternatively make a Bat totem pole (along with Pig for luck) near the circle where you are fighting them. Furthermore carrying a dagger of sacrifice with a blood altar allows dealing with druids very quickly as they die in 1 hit. This same strategy also works on many other enemies in the betweenlands except bosses.

* The Betweenlands is a very large mod, consult [http://the-betweenlands.wikia.com/wiki/Basic_Guide_to_Survival](http://the-betweenlands.wikia.com/wiki/Basic_Guide_to_Survival) for some starting tips.

* To enter betweenlands, plant a sapling in a wide open area and right click on it with talisman.

	If you have problems entering the portal; you have to wait in the portal for a few seconds still to enter.

* Take neither non-cooked food (berries -> rotten, hearty stew is fine), bedding, Vanilla Torches nor weak weapons (overworld diamond < between wood sword)

* Totem torches work normally in the Between lands. Furthermore the torch launcher also works but this could be considered cheating as the world uses you placing torches to trigger making them damp, and the launcher doesn't hit the same codepath. Blood magic’s Sigil of the blood lamp works here as well, and lets you throw light.

* Setting the spawn point with a sleeping bag apparently works. Death in the between lands respawns you back in the betweenlands and not necessarily at the portal.

* A chopping block can split weedwood into weedwood sticks, otherwise find bushes and break for sticks. 

* Hunt down a Weedwood tree and make a base in it ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_13.jpg)

* Find a Sap Tree and chop the wood to get balls of sap.  Eat this to fill up your decay bar.  When the decay bar gets low your max health and speed are decreased making you very easy to kill.  ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_14.png)

* Instead of making 2 Sulfur furnaces, craft a single one with 8 betweenstone for a double furnace.

* Upon death, you will respawn near the portal unless you have reset your spawn point using the Moss Bed.

* Food is hard. Cook Swamp Reed ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_15.png) into donuts for 6 hunger bars.

* Be on the lookout for Syrmorite ingots![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_16.png) in pots![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_17.png) inside Fortresses to get early access to lava-capable Syrmorite Bucket![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_18.png).

* The syrmorite bucket can hold lava, possibly earlier than going through a tinkers smeltery and stone bucket. Use this on rubber trees and make rubber shoes. These let's you walk on marshes at normal speed.

* ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_19.png)

* To make a full smeltery, you will need to go to the Betweenlands and find a Aqua Middle Gem found in lakes on the surface. Remember to take a bucket of swamp water with you. The purifier needs it and the normal fuel to run.

* The Betweenlands boat is tricky to operate. Left and right arrows operate each oar, similar to QWOP. In other words you must hold both left and right arrows to row forward. Holding only 1 lets you turn. Don't get stuck in the cavity of a tree, as you will suffocate if your head is not in open space.

* You can avoid using glass by using the silt glass from betweenlands instead. Its crafting recipe to glass and panes aren't modified. This avoids having to use the smeltery to create glass and glass panes.

* Syrmorite hopper is just as good as a regular hopper and is easier to make.

* Syrmorite armor and weapons are just as good as iron ones.

* For easier travel, you can tame a [Harlequin Toad](http://the-betweenlands.wikia.com/wiki/Harlequin_Toad) with Dragonfly Wings. As with other minecraft mounts, they require a lead and fencepost when you aren't riding them. The toad is able to swim and traverse Sludge Plains.

* Don't forget to craft a betweenlands bow before venturing into the fortress as you'll face ranged mobs in there.

* Life crystals are harvested from stalactites that have a white band on them.![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_20.png)

* Life crystals are found by some to be underwater in the cave system, so if you are able to acquire sea lanterns, use them to light your way as you swim around to find them, as the caves are dark, but the water in the caves is darker.

    * Can also use jack'o'lanterns underwater, and harvest glowing betweenstone or cragrock tiles from dungeons for underwater lighting

    * For emergency air, place a torch on the block next to your head.  The torch will pop off the wall but your air bubbles will be refilled.  Works with sulfur torches.

* Middle gems (red, green, and blue) can be applied to weapons and armor to enhance them, even stuff from other mods, just not tinkers. You can stack the same gem to make the chance the gem activates greater. Be aware that mobs spawn enhanced with these gems. If you have green enhanced armor a red swamp hag will do more damage to you. The tables are turned if you wore a blue gem. Blue imbued swords would do more damage to red mobs.

* Farming Lurkers gives Lurker skin. The full armor set gives awesome water-focused perks. Movement, mining speed, sight and greatly extended breathing boosts makes farming middle gems much easier.

* Lurker skin also gives you a pouch, which is a backpack that doesn't take a hotbar slot

* Sneaking near wights makes you undetectable by them as they use echolocation for targeting.

    * However, beware that the wight's 'special attack’ (becoming a mist and attacking you) deals **magic damage**, bypassing armour. Either eat food to combat with regen or drink cider from Rustic to gain magic resistance.

* Betweenlands armor, tools, and weapons corrode while in your inventory and simply moving around in the betweenlands (haven't tested in overland). Water corrodes it faster. Moving it into a backpack blocks the corrosion.

* It's extremely useful to purify your weapons & tools often, especially if you cannot find any scabist to coat them. Purification requires buckets of water and sulfur to power it.

* The purifier helps with keeping your tools working in top notch order. Finding **Scabyst** while mining will help stave off the corrosion for a long period of time.

* It is also extremely useful to put to work an animator, especially if you have found at least one life crystal in your travels, which can have its power replenished with wight hearts in the same way you use scabyst. Use the animator to animate any item scrolls you find (this requires a LOT of sulfur) to acquire any item like the swift pick, hag hacker, critter cruncher, and wight's bane. The chance of receiving these items is random but these weapons one-hit mobs in this dimension when they are fully charged, and even after they’re broken, as long as you purify them of their corrosion, it still only takes at least 2 hits with the weapon of its respective mob to kill it, which is a lot easier than with other tools.

* The Blue Middle Gem is great for ranged weapons (chance to weaken).

* Green Middle Gem is great for Armor (absorb damage)

* Valenite sword(2500 durability, 7 damage, 1.6 speed) can heal you when you attack.

* The end boss has a nasty wight attack. Run in circles and wait it out. Especially make sure you have a wight's bane for this fight, as it will save you a lot of headache even with a sword as useful as the Shockwave Sword.

* The voodoo dolls are really OP, bypassing armor and do damage in an AoE. Really helpful for abyssalcraft bosses

* Sulfur torches provide a great source of light, much like totem torches, so be sure to bring them with you even when you're done with the Betweenlands.

* If you can handle the stress of looking for, and fighting a few Wight Fortress buildings, the Shockwave Sword is especially useful for fighting Naga in the Twilight Forest, and lasts a heck of a long time, and would be great to have a few more of when one runs out, if it doesn't act like the other betweenlands weapons and continue working after being broken.

* Angry pebbles are something you can find while exploring, activating some item scrolls, and in pots. You right click with it in your hand to charge it up, and then throw it somewhere, causing an explosion somewhat like a throwable TNT.

* Always keep balls of sap or weeping blue petals on you to decrease the decay. Once the bar is empty, your health bar will decrease and you will die.

* Peat mummies are terrifying and when they roar it will shake your screen. If you happen to have a ring of ascent, it will help you fight them from above, and if you have a shimmerstone, you can throw that to distract them. You will be able to retrieve the shimmer stone back from the mummy once it is defeated.

* To get weedwood sticks faster for tool making and recipes, get as much as you can of it, bring it back into the overworld and place it in a horse chopper. It will make weedwood planks and sticks for you like normal planks and sticks so you can focus on other stuff. Unfortunately despite being a mountable creature, you cannot use Harlequin toads as horses to a chopper (leads break after a few seconds if you attach them to a post, but you can lead them around), or any other mob in the betweenlands unfortunately.

Betweenlands Farm

* It makes sense when you enter the betweenlands to create a farm for what you may need the most. Reeds are most needed, especially if you want to make caving ropes. 

* Invest time into the purifier for your farm, to purify your farmland so that it doesn't decay and need to be redone later on. 

* You cannot automate compost bins but everything around you is most likely compostable whether punched or collected with the sickle. 

* Almost any item you may need or want more of can be farmed; all you really need is a few pieces of farmland and to place the item you want more of on it. An example would be the blue petal flower; harvest it with shears (to get the 3D version of it) and place on one piece of farmland, and then over time it will spread to the blocks around it.

* White pear seeds can only be harvested from the hangers that hang from a giant weedwood tree, so if you find one early on, that's a great fruit source.

* Sometimes when you travel between the overworld and the betweenlands, your crops may disappear. So if you don't want to go through the trouble of searching for seeds to the stuff you want to grow more of in the future, think ahead and save some in a chest, just in case the plants do decay over time.

* Nettle soup is a great source of vegetable and jam donuts are an easy way to consume grain and fruit. 

### Betweenlands alchemy

Potion brewing is more complex, versatile and powerful than vanilla. [Here](https://youtu.be/b5FxMjufCtw) is a great tutorial for how to get into alchemy.

* Betweenlands plants have different aspects based on the seed, making each playthrough unique. ie. There isn't a fixed set of plants that will give a healing potion on all world seeds.

* Alchemy is gated on having a sickle from valonite (diamond equivalent) to harvest the various plants.

* Dedicate a gold backpack for gathering the ingredients

* You can stack power 5 potion and haste 3 potion and do 18 damage with your fist or a tcon dagger, which has no cool down, resulting in absurdly high DPS

* To help organize your alchemy research have 1 chest with a sample of your ingredients and a primal shelf holding your stock. This let's you hold shift to see the quantity. Do alphabetize the shelf to make finding the ingredient faster.

* Some ingredients for alchemy cannot be used in their dropped form, they have to be harvested with the sickle. If you try to use them in the pestle & mortar, they will not grind until you replant them and harvest them with a sickle. (example, golden club flowers has two forms when you search it, but the one that can be ground is not the one you can punch to harvest)

* Geckos cannot be placed in cages with the Carry On mod; you need to collect the gecko with a net, and you will receive a 2D item in your inventory that will become the gecko again when you click on a cage with it.

* Geckos do not last through tons of experiments so gather a few.

* If you want Potency V potion to last longer (30-60 secs) invest into wine. Find grapes, make stomping box, stomp, put 1 bucket in a brewing barrel and let ferment for 1/2 day. Pick quality of 0.6 (max:0.75). Use bottle to extract. Destroy other cultures and put best wine in far left slot. Added wine will get better values.

As you progress through the Betweenlands, you will encounter a Wight Fortress eventually. You need to be prepared for the battle ahead as the boss is very difficult to defeat on your own, so any aid in alchemy is really necessary here, as well as the best armor and weapons available, amulets, and rings if found. Set up base around or inside the fortress once you get through it so that if it is too far away from your home base, you don't need to travel a million years just to get back to your grave. See here for more information: http://the-betweenlands.wikia.com/wiki/Wight_Fortress

## Tinkers Construct Smeltery

Prerequisite: Turntable[Better with mods], Aqua Middle gem[Betweenlands] or wait till the nether for blaze powder.

Note that ore doubling from tech mods has been nerfed greatly. Even Mekanism is delayed until age 5, and it won't process your ores. A smeltery will be your go-to tool for ore processing for quite a while.

* A bucket cast is made from a stone bucket, not a clay one. You still need a clay bucket to get lava for the seared/porcelain tank under a melter.

    * Note that a seared tank won't work with a porcelain melter.

* You can make casts out of Gold, Brass, or Aluminum brass(1 copper+3 aluminium). Seems you only have access to gold right now.

* To stock up on lava either jump into the betweenlands for a syrmorite bucket or use a clay bucket to bootstrap the smeltery and cast gold on a stone bucket, then pour iron to get a vanilla bucket. Then use barrels (8 bucket capacity) and a lid to store lava (lidded wood barrels don't catch fire).

* A tinkers smeltery can be as small a base of 1 square, but the primary use case for the smeltery is to be the main ore processor, so you should just start making a larger one.

* Smelteries can share sides, but not the tank nor controller. This helps avoid unwanted alloys.

* A liquid hopper feeding into an ingot cast automated processing but is tricky to place. You need to be on the side of the block you want the hopper to pull from.

* Note: **Obsidian doesn't form** in the smeltery, so you won’t have quick and easy access to Obsidian yet.

* The pictured smeltery is fed by an upper from the ironwood crate. The basin/table are using wooden hoppers to extract items and blocks into an upper below the gold chest.The fluid hoppers are set to work on a high redstone signal from a lever above them.

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_21.png)

## Twilight Forest

* The portal to the twilight forest is built in the same way as usual (12 flowers around a 2x2 pool of water). Because you do not have access to diamonds it is opened with a Starmetal Ingot dropped into the pool.

* Take climbing gloves with you as there are many quests made easier when you can climb their structures.

* Vanilla ore veins spawn in the Twilight Forest, and due to the dimension's lower surface height can be a lot easier to reach, or in some cases even be found right at the surface.

* Redstone is available but you can't make redstone torches nor comparators. While you can craft redstone blocks, placing them makes it look like granite, but rest assured it functions as a redstone block, giving you a poor-man's redstone torch. Mining it returns granite.

* If you notice a lot of FPS lag while in Twilight Forest, try reducing your view distance.  This kind of stuttering is usually related to minecraft trying to render too many textures.

* Hedge Mazes may contain a hostile wolf spawner, which if left intact may provide you with an easy source of pelts to craft into leather or glue if you have not yet started breeding animals at this point.

* The lich's shields can be destroyed with the Betweenlands Voodoo doll. This doll also easily handles the horde found in the mounds.

* Medium and large hollow hills, as well as hydra lairs contain Redstone Ore, as well as Coal, Iron, Gold, and Lapis.

* Maze wafers are a decent source of grain nutrients and can be found in Labyrinths and other dungeons later in the progression.

* While you are in the Goblin Stronghold, make sure to collect Knightmetal as it will prove very useful later on. 9 Armor shards make one ingot, two ingots make a pickaxe head, and a pickaxe head is the easiest and earliest way to get cobalt-level mining (expect Obsidian). It's also a great material in general and you might benefit from getting yourself some extra. A knightly sword has great durability, deals extra damage outside the Twilight Forest (from a base of 7), and will occasionally give Resistance III in combat.

* In later dungeons, a food called experiment 115 can also be found which gives all 4 nutrient types

* Ensure that you collect as many steeleaf as you can (at least 4) from the labyrinth so that you can craft the coal engine to move towards age 3. You do not want to have to find you way back into the labyrinth later.

* Dark Towers have plenty of useful items to loot, including Brewing Stands, Anvils, and Pistons, as well as the Carminite Reactor you will need at the end of this age, in addition to this there will be plenty of spawners that will spawn carminite ghasts which you can kill for ghast tears, and there are a lot of chests to loot for other goodies like Redstone Lamps, glowstone dust, and Experiment 115

* Do NOT activate the Carminite Reactor in the Dark Tower. This would be accomplished by triggering the pistons surrounding it and is a bad idea.

* The Carminite reactor required a bronze pickaxe to pickup. Claw paxel works as well.

* Dark Towers also can contain Blaze spawners, though Blazes don't actually seem to spawn in age 2. However moving blaze spawner to overworld makes it spawn blazes even in age 2.

* Take some bones to the doggos in TF to tame them, and carry them back to your base. They'll run faster than the horses for your machines.

* Cave Illuminators (from Astral Sorcery) allow you to clear Mazes, Hollow Hills, Labyrinths, and Goblin Knight Strongholds much more easily.

* In the Twilight Forest, many ores tend to spawn in the South East corner of a chunk near bedrock regardless of standard Y level spawning tendencies. (This is especially useful in Age 5 when you need diamonds to craft the Prospector to help find diamonds)

* The knights in the urghast tower give awesome loot including a chance to get excavation on a knightly pick. Use an anvil to join it with mending.

* When facing the urghast you might want to replace the pressure plate near the ghast buster traps with a lever so that it activates when you want it not by accident.

* Twilight Forest chest loot can contain tools with enchantments such as Excavation and Silk touch

* You can mine the glass from the snow queen's biome and craft the shards into glass, helpful for liquid hoppers.

* The Hydra is a fierce foe who may break your grave. The easiest way to kill it is to break cobble into stones, and throw them nonstop at the Hydra's open mouths. Bonus damage for hitting the incoming fireballs back into the beast with the rocks.

* The twilight quest to eat 6 twilight foods include: venison, need, stroganoff, Hydra chop, maze wafer, experiment 626.

* Charm of life acts like a Totem of undying that resurrects you if you die.  Even if you have them, gather all you find to make the Journey Map token.

* When you have the Journey Map you can shift-right-click on an ore sample to create a waypoint named after that ore type

## Teleportation

Here are some methods of teleportation available.

### Astral Sorcery Method

Astral sorcery's celestial gateway can be used to teleport to a different altar. Remember to use an anvil to name the gateway block itself.

* Pros: Very easy to use, works across different dimensions and over long range as well

* Cons: requires 2 starmetal ingots and 8 stardust to create 2 of them and both require a marble structure.

### Betweenlands Method

Furthermore you can link betweenlands portals with the swamp talisman

* Pros: Can be used as soon as the swamp talisman is obtained, new portals are very cheap to make

* Cons: Can only teleport up to 1500 blocks away and exactly one portal MUST be in the betweenlands so you need to use 2 portals to reach a different place in the overworld.

* Also it takes a while for the teleporter to function and the world to load.

* Additional Portals can be made with wood harvested from a portal tree then ignited with a talisman. A full portal tree is not needed.

## Blood Magic

* You can progress your altar to a tier 3 by going to an ocean monument and getting sea lanterns (silk touch or via getting prismarine).  You can silk touch glowstone blocks from twilight forest but they will not be placeable until age 3. 

* ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_22.png)

## Astral sorcery

* Start by making some lightwells, preferably with liquid hoppers pulling from the bottom and pushing into wooden barrels. You only need 1 bucket of starlight to upgrade to the next tier of altar.

* All Astral Sorcery recipes require a minimum amount of starlight. Early items often need so little starlight that you can craft them during the day. Upgrading your alter probably needs to wait till nightfall. Star light increases with Y level, up to y=120. If making the next item in AS needs more starlight than you have at your base then move your AS stuff into the mountains. Use a bronze or claw pickaxe to pick up the luminous crafting table and find a higher place or different chunk. Higher than 120 doesn't matter. Once you get more advanced altars this benefit doesn't matter.

    * If you are struggling to get a bit more starlight for the altar, you can craft **spectral relays** to boost the altar. When placed in a multiblock structure (look in the book) with a clear view of the sky and a **Glass lens** put into it, the Spectral Relay will bring more starlight to the closest Luminous Crafting Table (or any upgraded altar) in a **16 blocks radius** around itself. However, multiple Relays in a 16 block radius will have **diminishing **effects.

* Mischief of Mice's [top tips](https://www.youtube.com/watch?v=i22YPsbfego) and a [playlist of astral sorcery - bit by bit](https://www.youtube.com/watch?v=9uU67eYK_Mc&list=PLQzDSnrhrcyyZKmHp1zdj03jRbuZN7NOh)

* For a more concise, text and image based guide see [minecraftguides.net's Astral Sorcery Guide](https://minecraftguides.net/AS/index).

    * Notable differences between vanilla Astral Sorcery and Sevtech Astral Sorcery are the lack of world-generated Temples, the source of Rock Crystals, and the source of Aquamarine. Constellation paper is obtained via Abyssalcraft Ritual, Aquamarine is mined in The Beneath, and Collector Crystals must be crafted.

### Finding Rock Crystals

* The Resonating Wand does not make the Crystal Rock Samples more visible, like it does in the standard mod with Starmetal Ore.

* Take 6-10 crates with you, because rock crystals don't stack(due to unique stats on each crystal), and it’s nice having a healthy supply, though you don’t strictly need more than 3 chest’s of rock crystals.

* Crystal rock samples look like:![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_23.png) These produce starmetal dust; used below. You only need ~3 of them to do the needed steps for AS, but would want closer to 7 to get to the OP stuff AS provides in this age. 

* Sevtech changes iron access to make stardust generation more tricky. Getting Iron Ore requires a trip to the Ore cavern in twilight, which also gives access to redstone. Alternatively you can slowly get more via celestial rock crystal farming below. 

* Once you find a Rock Crystal Sample, you need to look at the outer corner the chunk it's in (just outside of it). Press F9 to see the limit of the chunk. Unlike the vanilla version it will be a big cluster of crystal and it can be hidden under lava (mine was). The Tough Dousing Rod will detect it if you are lower than y 48.

* Rock Crystal ore is not mineable with a stone pickaxe, you need something with mining level diamond to harvest it (like an iron or bronze pickaxe from tinkers or claw paxel available starting from Age 0).

* Getting lapis on a tinkers pickaxe before mining rock crystal is nice, as looting works on Rock Crystal Ore.

* You can also use a pig totem to get Luck 3 and get more rock crystals.

### Starlight Generation and rock crystal stats

* If you have time then only liquify a handful of rock crystals into starlight. Turn the rest into celestial rock crystals, described below, which are better in all respects.

* When siphoning starlight from rock crystals into lightwells start this process at nightfall, as daylight reduces the amount of liquid starlight generated.

* ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_24.png)

* Barrels (8 buckets) provide cheap portable liquid storage, or the Rustic Barrel if you want 16 buckets of portable storage (2 iron for 2 barrels). Use carry-on to rotate out full barrels. An empty barrel exposed to rain gets water. Mining it empties the barrel. Stack the barrels with the top one having a lid. Use a Fluid Hoppers to pull from the bottom of the lightwell to automate extraction. A Tinker's Tank makes for a great way to store all that precious Liquid Starlight. Later a containment chalice can be used. Putting a chalice near a infusion structure **drastically reduces** starlight usage.

* The following items can be placed in a lightwell, which locks it into melting into liquid starlight: Aquamarine < Resonant Aquamarine < Rock Crystal < Celestial Crystal < Attuned Rock Crystal < Attuned Celestial Crystal

* Liquid starlight that touches water creates ice. Speed up your horse-powered machines by making an ice track. It is also great for the heat generator in Age 3.

* You can drop a rock crystal and a stardust in a pool of liquid starlight. If you unintentionally pick the crystals up just back up some more. This will grow a celestial crystal cluster. Don't spend your time trying to get a normal rock crystal to 100% purity. Just go for the celestial right off the bat.  When full grown (white sparks will show) you can break this to get at least one, often two, stardusts back. Make a pig totem to increase these chances.
 ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_25.png)

* Use the stardust to turn more of your rock crystals into celestial rock crystals, which produce more liquid starlight, and letting you roll again on getting a high purity celestial rock crystal. You'll end up with an overabundance of liquid starlight, so just toss the celestial crystals back in with stardust to get more dust and trying to get a better crystal.

* Grow celestial crystals on starmetal ore, making the chance they drop an additional stardust increase as well as making them grow faster (.5 to .8).

* When you get a celestial collector crystal you can direct its starlight at the cluster to speed up growth.

    1. Note that if you split the light to multiple destinations the light delivered gets divided/reduced as though it is being used for something or not, thus focus your light and babysit it.

* Note that you need a linking tool to send the collector crystal's light to your altar or an iron ore block (found inside mounds near the minotaur lairs) which turns into a stardust ore block. Note that if you link the collector crystal to multiple things the light always gets divided, even when not used. Best to keep it on 1 thing at a time. 

* Collector crystals are better when made from crystals with bigger size and higher purity. Cut doesn't matter.

* The multiblocks that collector crystals and spectral relays can share edges, allowing you to put 3 collector crystals on one side of your crafting altar.

* Your goal is to get 95%+ purity celestial rock crystal, with the rest going to liquid starlight and recipes.

* Growing crystals and rock crystal tools by soaking in starlight grows durability while decreasing the cutting. Place in a grindstone to increase cutting at the cost of durability. Purity makes the durability fee cost less. Using a tool doesn't use up durability but rather the cutting.

* When making a rock or celestial crystal grow by soaking it in starlight, if you continue past the maximum size there is a 1/6th chance that a second crystal will form with higher purity (this is also the only way to increase purity). See [here](https://youtu.be/i22YPsbfego?t=5m23s) for example

* You want to use 90%+ purity crystals and get their size as large as you have patience for rituals and collector crystals, and preferably celestial crystals

* Crystal tools are very effective, for example the highest quality sword does 7 full hearts of damage, (double that of a diamond sword). The quality of a tool depends on the stats of the crystals used. Higher size/cutting means more efficiency. However they slowly decrease these stats over time when used. These can be gained back by putting them in liquid starlight or on a grinding bench. Later they can be infused to make them more durable and effective.

### Tier 1 altar

* Use a Fosic resonator to find patches of dark blue mist. Must be within ~3 chunks to see it and somewhat close to the ground, so don't go too high on your slimesling. These areas are great for starlight. Pillar up and build your altars there.

* Place your lightwells near your tier 1 altar to speed up production of starlight, as well as providing more light to the altar.

* While the Starlight crafting altar in JEI shows an iron bucket, the book correctly reflects that a clay bucket of starlight works just fine.

* Spectral Relay bases can share blocks, allowing you to pack the relays in a smaller area. The Relay simply needs line of sight to its nearest alter crafting table.

* When creating Lenses ignore the cutting. Purity affects how much starlight passes through. Size impacts the yield of the recipe (5 for size 400 ).

### Other altars

* The 5 chapters in the Astral Tome are unlocked by manually upgrading the second most advanced alter you can see in the Astral Tome to the next tier (ie. if you can see the Attunement chapter then make the Starlight Crafting alter and its multiblock structure, then fill in the items for the Celestial Altar and then right click with the resonating wand). If you are in creative mode it may mean you must build the multiblock structure appropriate for that altar.

* To tech up to a Collector Crystal, which can turn Iron Ore found in Twilight Forest mounds, into starmetal ore, you'll need 64 aquamarine, 15 stardust, and 11 stacks of Marble with an assortment of liquid starlight, wood and so forth.

* To upgrade to the next tier alter you'll need to get some easy twilight forest items and kill the naga and lich, which lets you enter the maze. On the Magic map the maze looks like this![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_26.png). The mazestone just takes a long time to mine. You don’t need to kill the boss. If you want you can get the maze map, which will show where a solid square is which contains a trapped room with the mazebreaker. But that is optional.

* While the Naga is straightforward, the Lich's 5 shields need to be eliminated first. See the Twilight Forest section for tips on defeating him.

* Silt from the Betweenlands smelts into silt glass which easily crafts into silt panes for lens crafting.

* Celestial Gateways allow for inter-dimensional transport, you can set up gateways to travel to the end, nether, or even other GalaticCraft planets - the multiblocks can be built in stage 2. Even if the destination is at a lower Y value the "star" won't go below the horizon.

### Attunement

Attunement is learning about the constellations, constructing the attunement altar area and table, and imbuing yourself when desired constellations are out. This imbues you with powers and starts you on a progression tree to get more perks.  You can use a shifting star item to reset your attunement, thus losing all progress. Crystals can also be attuned required for special items later. You are limited the the following 5, but crystals have more.

* The hand telescope sucks. Upgrade to the normal telescope ASAP. You don't need to fine tune centering on the constellation. Keep it near the attunement area. Note that not all constellations show up all the time.

* Put the Constellation paper in your offhand so the attunement area stays lit up while you place the relays with your main hand.Spots where to place the spectral relays glow blue.

* You can attune yourself to a constellation for all kinds of bonuses. This requires the attunement altar and a rather large multi block structure (using 225 sooty marble alone) it also requires some spectral relays.

    2. **Discida** gives all kinds of damage buffs

    3. **Armara** provides a multitude of damage reducing buffs. Progress by taking damage.

    4. **Vicio** increases speed, places lights, reduces hunger and grants temporary lava immunity. Progress by moving.

    5. **Aevitas** provides increased reach, natural armor regen and turning stone around you into ore. Animals are frisky and plants grow faster. Progress by having things grow around you.

    6. **Evorsio** gives mixed mining speed and damage increases as well as disarming your opponent's armor.

* The Armara perks make you extremely hard to kill, and several of the perks work on damage that doesn't seem to be affected by armor. For example, the Dread Plague from Abyssalcraft is reduced in damage significantly by the 'No armor is more armor’ perk, making the Dreadlands much easier than otherwise. Armara also almost reduces fall damage to 0, allowing you to use the slimesling without the boots.

* The aevitas skill tree has a natural armor regen perk. Take it, get your strongest armor and put some middle gems from betweenlands on them for maximum power. Don't forget to put some on your weapon as well and take a amulet.

* A mineralis cloak allows for easier ore finding once you get silk touch as it highlights any ores you are holding.

* Vicio attuned Mantle of Stars and Resonating Wand allow infinite flight (elytra style flight).

#### Tips for leveling attunements

* There are 30 levels max, so spend your points wisely. It is easy getting to level 10, tedious getting to 20, and hard getting to level 30, so only invest into "Increased Perk Experience Gained" if you're shooting for level 30 more quickly.

* A shifting star held with right click will clear your attunement and put you at level 1.

* A Irradiant star of your will refund your perk points and attune you with the star's constellation. Thus pick Vicio to level, then reattune yourself with the desired constellation.  When leveling in this way be sure to pick the 2 nearby "Increased experience Gained" nodes first, then path out to Epiphany nodes. Note that you need to get the 3 surrounding nodes before you can get the center epiphany one, but then simply using a single point to get another epiphany node grants you all of its 3 surrounding experience nodes.

**Vicio:** Gain XP by walking, sprinting, swimming and flying. The wild dog boots, and preferably potion of nimbleness from The Betweenlands, and running on the top of the canopy of the Phantom zone in Twilight Forest will let you get to level 25 in roughly 15 minutes. Creative flight is bugged so the Vicio elytra mantle is recommended if you must fly, but sprinting with the wild dog boots gets you leveled faster.

**Amara:** Level with the amount of damage you take. Armor will get hosed, so focus on some healing trick to level quickly. Craft a betweenlands potion of healing with max potency(V), disrobe yourself, drink the potion and stand next to the saw [Optionally put Spikes beneath you for more damage]. This gets you leveled from 1->11 with potion 1, 11->20 with potions 2,3,4, and 5, each potion lasting 2 minutes.  Note: Don't get Added Armor, nor Bulwark while leveling as it reduces damage taken.  Another approach is to do the Sun Dance from Totemic which won’t kill you, but still do damage.

**Aevitas:** Placing blocks gives you experience, the harder the better. Wood has a hardness of 2, same as cobble (see [this table](https://minecraft.gamepedia.com/Breaking#Blocks_by_hardness)). Get a lumber axe from Tinkers Construct, mine big trees and place the logs. If you've automated obsidian farming then they are worth 25 logs in XP.  280 wood logs placed gets you to level 2. Use an iron wand to speed up placing blocks. An iron wand maxes out at 9 blocks placed. Wait for a diamond wand for faster XP gains.

**Evorsio:** Gain XP by mining blocks. A tinker's construct lumber axe working away on Twilight Forest giant trees are your path forward. An axe with the Dense property and 8500 durability and 3 giant trees gets you to level 16.

### Rituals

* The Attunement, Size and Purity of the crystal are all that matter. Cutting doesn't matter.

* Don't waste time on a Mineralis ritual yet, it’s been reported and the configs need to be altered so it doesn’t break pack progression. Mining with this method results in a break in progression, as it can provide ores from GalactiCraft planets / Asteroids, this nullifying most of intended GalactiCraft methods.

### Misc

* Having two Chalice of Containments one with lava and one with starlight will mostly make sand, but will also give you aquamarine shale and the rare rock crystal. While the aquamarine found in the beneath is not affected by luck, aquamarine shale made this way is. You average 3 shale per bucket of lava and starlight and if you use resonating gems you typically get more than a bucket of starlight. Recommend using an ender hopper or similar to collect items. Note if your server is using Sponge, the two chalice thing is bugged. Blood magic Senade of the nether is a great way to get lava.

* You can build yourself an indestructible chamber with the Illumination wand. Inside you place any kind of stone. When you wear Mantle of Stars attuned to Fornax and set yourself on fire (e.g. with flint & steel) you melt the stone to lava source blocks.

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_27.png)

### Stellar Refraction Table Constellation Effects source

(Sourced from [Mischief of Mice's video here](https://www.youtube.com/watch?v=LOtA7MZC2-M&list=PLQzDSnrhrcyyZKmHp1zdj03jRbuZN7NOh&index=6))

Infused Wood is made by throwing oak logs into starlight. 

The drawing table works by placing a special glass sheet on top and etching it with 1-3 constellations. You first etch it by placing the astral sorcery parchment in the lower section, opening the UI and dragging 3 constellations onto the main area. There is a chance that the paper gets burned up. We don't yet know why, just try again. While you can place the constellations anywhere, their location doesn’t matter, nor does aligning any of the points. Only the overlap. There is some funky math it does behind the scenes, but the easiest is to just have them completely overlap each other.

You can only select constellations that are in the sky, so you may have to wait. After placing your 3 constellations, it will etch the glass with that selection. Take out the paper and place items that can be enchante

<table>
  <tr>
    <td>Constellation</td>
    <td>Potion</td>
    <td>Weapons</td>
    <td>Armor</td>
    <td>Tools</td>
    <td>Book</td>
  </tr>
  <tr>
    <td>Aevitas</td>
    <td>Regeneration I-IV</td>
    <td>Mending</td>
    <td>Mending</td>
    <td>Mending</td>
    <td>Mending</td>
  </tr>
  <tr>
    <td>Discidia</td>
    <td>Strength I-IV</td>
    <td>Sharpness III-VII
Power III-VII</td>
    <td>N/A</td>
    <td>N/A</td>
    <td>Sharpness III-VII
Power III-VII</td>
  </tr>
  <tr>
    <td>Armara</td>
    <td>Resistance I-III</td>
    <td>N/A</td>
    <td>Protection III-V</td>
    <td>N/A</td>
    <td>Protection III-V</td>
  </tr>
  <tr>
    <td>Vicio</td>
    <td>Speed II-IV</td>
    <td>N/A</td>
    <td>Feather Falling III-V</td>
    <td>N/A</td>
    <td>Feather Falling III-V</td>
  </tr>
  <tr>
    <td>Evorcio</td>
    <td>Haste VI-IX
Attack Speed II-V</td>
    <td>N/A</td>
    <td>N/A</td>
    <td>Efficiency III-V</td>
    <td>Efficiency III-V</td>
  </tr>
  <tr>
    <td>Mineralis</td>
    <td>Haste I-IV
Attack Speed</td>
    <td>N/A</td>
    <td>N/A</td>
    <td>Fortune I-III</td>
    <td>Fortune I-III</td>
  </tr>
  <tr>
    <td>Fornax</td>
    <td>Fire Resist I</td>
    <td>Fire Aspect I-III
Flame I-II</td>
    <td>N/A</td>
    <td>Scorching Heat</td>
    <td>Fire Aspect I-III
Flame I-II
Scorching Heat</td>
  </tr>
  <tr>
    <td>Octans</td>
    <td>Water Breathing III-V</td>
    <td>N/A</td>
    <td>Respiration II-IV</td>
    <td>N/A</td>
    <td>Respiration II-IV</td>
  </tr>
  <tr>
    <td>Lucerna</td>
    <td>Night Vision I-III</td>
    <td>N/A</td>
    <td>Night Vision</td>
    <td>N/A</td>
    <td>Night Vision</td>
  </tr>
  <tr>
    <td>Bootes</td>
    <td>Saturation III-VI</td>
    <td>N/A</td>
    <td>N/A</td>
    <td>Silk Touch</td>
    <td>Silk Touch</td>
  </tr>
  <tr>
    <td>Pelotrio</td>
    <td>Regeneration
Absorption</td>
    <td>Mending</td>
    <td>Mending</td>
    <td>Mending</td>
    <td>Mending</td>
  </tr>
  <tr>
    <td>Horologium</td>
    <td>Speed II-V
Haste VI-IX
Atk Spd</td>
    <td>Looting III-V</td>
    <td>N/A</td>
    <td>Fortune IV-VI</td>
    <td>Fortune IV-VI
Looting III-V</td>
  </tr>
</table>


# Age 3

**Ores:** Galena (Silver and Lead), Limonite (Iron and Nickel), Platinum, Cinnabar (Redstone), Bauxite (Aluminum), Nether Quartz, Nether Amethyst.

**Tools:**** **

**Key Items:**

## Uncategorized Tips

* If you want to minimize your time hunting for rock crystal samples, rush Starlight Infusion - that lets you create Stardust out of crushed Nether Quartz

* If you don't want to wait until the next age for wireless redstone, try using Cyclic’s Password Trigger. It will either toggle or emit a pulse when you type a certain message in chat (which it will also prevent from appearing). Just don’t lose track of your passwords.

## What you can do now:

* Vanilla Enchanting (including Ore Excavation/Veinminer)

* Buildcraft Pipes

* Storage Drawers Controller and Compacting Drawer

* Tinker's Construct modifiers

* Vanilla redstone circuits (repeaters, observers, comparators)

* Automated farming via Garden Cloches

* Automated Animal farming via Mob Filters combined with the [Feeding Trough]

* Vacuum/Ender Hopper

* Minecarts (Vanilla and Steve's Carts 2)

* Infinite water: A better with mods well bucket next to a water source can give you infinite water. A fluid hopper pulls it out.

## Obsidian

* Obsidian is now available. It used to be cracked basalt but now appears in the world.

    * Astral Sorcery crystal pick can mine obsidian very quickly

    * The swift pick from the betweenlands is highly recommended due to its insanely high mining speed. It breaks obsidian in a rate of about 1 a second.

    * The Bound Pickaxe from Blood magic is relatively cheap if you have a tier 3 blood altar established and has a cobalt mining level and mining speed of 10.

        * the only downside is that you have to have LP in your network when it is activated or you will take damage every so often

* Once you get access to excavation on a sufficient pick, use it on Obsidian! You only need to break one block for all the others to be mined almost instantly, making collection much easier. 

## Nether

* You can cast yourself a nether portal out of lava: ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_28.png)

* When turning netherrack into hellfire dust know that the 8th dust spawns a ghast if you don't have a urn under the hopper. If the hopper is receiving mechanical power, it also wont spawn a ghast or break when trying to create large amounts of hellfire dust.

* Nether Amethyst Ore only spawns in the vanilla Hell biome (get a Biomeanalyzer). It's rare, so Fortune III is recommended

* When farming a blaze spawner don't forget to make yourself some totems (fire protection). 

* Blood Magic's Sigil of the Phantom Bridge lets you get around easily, avoiding Thornstalks and Soul Sand

* Spawners can normally be picked up with the Carry On mod (shift+right click with an empty hand)

    * The Sack of Holding can also be used to pick up and move spawners without the drawbacks of Carry On

* Magma block/Netherrack over a Lightwell generates Lava for your furnace.

* To grow Nether Wart, you need Ichor (red liquid in arctic abyss biome) next to tilled soul sand.

## Better WIth Addons

* The ancestral infuser must sit on soul sand with the sand having nothing else adjacent, even diagonal. As it must also be dark, use an ender totem to give yourself night vision in a dark room.

* To make bamboo slats you need a soaking unit. The multiblock structure should look like this

* ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_29.jpg)

## Food

* Fish n' chips. This food restores 9+ full hunger bars and saturation. Every fish n’ chips also requires 1 paper cone made of 3 paper(recall the easier recipe for paper in this age). You get the cone back after eating it, so keep a slot dedicated for holding paper cones else you’ll drop them if your inventory is full. Note, this recipe uses only age 2 and lower materials but is only obtainable in age 3. 

    * The 2 best ways of getting lots of fish is either a waterfall or the strainer which needs worms to run. Worms come from using a trowel on dirt.

* French Fries (5% grain) made with potatoes.

* Cooked ghast meat. This food restores 4 full hunger bars and 5+ saturation Raw ghast meat can be obtained in large quantities in a ur ghast tower in the twilight forest. Note that ghast spawners despawn after 400 spawns. Raw ghast meat can be obtained in age 2 but only cooked in age 3

    * **Important**, eating ghast meat gives levitation 2 for 10 seconds, this could be beneficial or not depending on the situation

## Blood magic cont.

* To help provide more blood (beyond what the blood alter normally has capacity for, is. You can have a tier 2 alter take on transmutations that would normally require the capacity for a tier 3 or 4) make a ritual altar and attach a collector Crystal attuned to Aevitas. This gives you regeneration 2 while close by. Amplify the effect by having a collector crystal, also attuned to Aevitas, with the collector multiblock base then link it to the ritual pedastal. Before setting up the lenses place a ritual anchor 4 blocks above the center crystal. Then deal with the Beams of light which will then point out. Use lenses to redirect them back using the linking tool to link the lens back to the ritual pedastal. More beams will come out, repeat. Then put the other ritual anchor at your blood altar area. Then link the 2 anchors together. This brings the Regen into your blood altar area. With this super Regen start the transmutation and stab yourself till the transmutation is done.

* Another way to generate tons of blood is to have a ritual of sacrifice damaging zombies, then heal them with graveyard soil.

## Storage

* Obsidian chests are the best one block storage options for its price, each having enough space equal to 3 large chests (108 slots)

* You gain access to tanks, specifically from Immersive Engineering. While this multiblock is non-portable, it is very useful for storing large amounts of fluids. This is good for creosote, lava (though this might be difficult to collect), and water. These liquids have been, and will continue to be very useful (well you just gained access to creosote but it applies to it as well) so it is recommended to store up on them.

## Tinker's Construct Tools:

* Shuriken: The upper left-hand corner determines what material repairs it.

    * If you have access to obsidian and therefore Reinforcement modifiers, you can make a shuriken that's unbreakable (**infinite ammo**) right out of the gate by using one paper part. One paper, 2 bone, and one iron part gives 7 hearts of damage, increasing with number of hits. This can probably be increased further by replacing the iron with prismarine or firewood if you have access to those. The paper part can be replaced after leveling up twice.

* Note that sharpening kits only repair. **Don't plan on getting obsidian sharpening kits** to upgrade your mining level

* The silky touch modifier uses betweenlands gems rather than emeralds. This is useful for getting the ore itself, needed for a few recipes later and ore doubling

* You gain access to the Ore Excavation modifier in this age (alongside the ability to add modifiers in general). Check options for the keybindings available. Ctrl+OreEx keybind opens up a GUI that allows you to edit shapes if you want.

* OreEx will continue mining blocks with your tool, it only stops when one of the following happens:

    * Your hunger hits zero

    * You let go of the excavation key

* If you hold food in your offhand and have a gluttony charm equipped you can eat while ore excavating, allowing you to mine the max 4000 blocks all at once.

* You can swap parts on your tinker tools without any penalty. This lets you do something like create a pickaxe with a stone head, add the ore excavation modifier to it, and then mine through huge amounts of stone, repairing the tool as you go (make sure to have a Tool Station on hand and a LOT of food) in order to level it up very quickly. A good way to do this is to add, in order, the ore excavation modifier, 5 reinforcement modifiers (ASAP as soon as you get the levels, to make the tool's durability last longer than your hunger) to make it unbreakable, and then Luck III. Due to Ore Excavation, redstone (Haste) isn’t as important, so it can wait. Also, since you can replace parts without penalty, you can keep this pickaxe/axe/shovel/whatever for the rest of the game, replacing any part on it whenever something better shows up without having to worry about ever repairing it.

* Absolutely make yourself a Luck III pick (even 1 lapis + time or forking up the 360 lapis to quickly get to Luck III), either on your main pick or keep a spare just for the ores that are annoying to find (nether amethyst,  aquamarine, ...) (Just by adding only 1 Lapis will help, it slowly increases when used.)

    * Most geolosys ores are not affected by Luck, the ones affected by Fortune/Luck will be noted above in 	the Ore Distribution chart

* You can easily get repairable tinkers tools with mending moss (right click a moss ball on a bookshelf + have 10 levels to give up) and copper parts which causes lots of exp drops (when mining stone for example)

* Another alternative to using Mending Moss is to have a part made of Steeleaf, from The Twilight Forest. It's got great stats for Bows and Bolts, and it adds the Modifiers Twilit and Synergy. Twilit buffs damage outside of the Twilight Forest, and Synergy auto-repairs the tool for free as long as there are Steeleafs in your hotbar, with faster repair on how large your stack is. It doesn’t consume them and saves you a modifier slot

* You can clear out huge swaths of cobblestone using the Excavation + Blasting modifier + Gluttony charm + lots of food. Blasting 3 destroys all the cobble you mine. After blasting the stone you are left with easy to find veins. If you use Copper you get tons of XP as you're doing it. 100+ levels in 10 minutes.

## Stoked Fire

* Make a Hibachi and Bellows, plug bellows onto an axle and create a [redstone clock](https://minecraft.gamepedia.com/Clock_circuit#Repeater_clock) (or make a timer) that turns of/on the gearbox. Put a redstone torch next to the Hibachi and you should see a blue flame - stoked fire. This unlocks many new cool things, 

    * Note the bellows can breath on all Hibachis in a 3x3 in front of it.  More fire = faster crafting.

    * Nether bricks for the blast furnace (probably the most important thing to get as of now)

        * Note: don't put nether sludge in a crucible while it is heated with a stoked fire. It will explode.

        * Best way for potash is the sawdust from your saw.

    * The kiln is also another required machine. Note that to cook the unfired crucible the fire under the kiln needs to be red, not blue. Simply turn off the bellows and the crucible will start to cook.

* ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_30.png)![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_31.png)

* When you put [4 bricks above the stoked fire](http://sargunster.com/btw/index.php?title=Kiln) you will get a Kiln. You can make nether bricks in it - this unlocks the blast furnace from Immersive Engineering, therefore Steel and this will unlock doing most of the IE things in this Age.

* Nether Sludge can be hand crafted to Unfired Netherbrick that can be placed into the cyclic block placer as a way to automate the creation of nether bricks in the kiln. You can then use the Dark Utilities Ender Hopper to automatically pick the dropped Netherbrick up of the ground into a chest, just place the chest under the hopper.

    * Vanilla Dispenser works in place of Cyclic Block placer and is much cheaper to produce

    * Vanilla Upper works in place of Ender Hopper and does not require Nether materials, [like so](i.imgur.com/ipS8GCM.png).

* In a kiln you can make Melon Pie(2 watermelon+raw egg+flour+sugar): **4% Fruit**

* When you put a Better with mods stoked Crucible above the stoked fire you can melt down armor (gold and iron) to ingots and nuggets. Combo this with the hunting dimension and a mob grinder there to get infinite gold and iron.

## Water

* Be prepared to run utilities to various corners of your base. Organising "steam tunnels" under your base will make routing water and other liquids between machines less tedious, leaving the sky available for "dire wires".

* Make sure to build a cactus zone for easy harvesting of cactus if you plan to use buildcraft pipes. Make sure you can walk away with at least a stack each harvest. (See also: sugar cane, swamp reed for doughnuts). 

* A redstone engine pumping water out of a Better with Mods Well Bucket surrounded on all sides with water blocks will serve your resource needs well. (Note that the water bucket is available in age 2, but if you've settled near a river or ocean, this problem only becomes fraught at this age.)

* Another reason to run a *single* water network around your base is that the buildcraft fluid transport pipes have a non-trivial amount of fluid storage inside of them. While they do not have nearly the same transport rate as Immersive Engineering pipes, the virtues of cheapness and a water buffer are good. (The buffer is only useful insofar as you have some pipes exposed so you can see if there is a problem when walking past. Build diagnostic pipe sections accordingly.) For steam tunnels, know that you can disconnect immersive engineering fluid pipes with a hammer (in case of junctions) and that stone and cobblestone fluid pipes do not connect to each other. Next age you'll want a fluid pump (make sure to supply it redstone and power, and have at least one input (hit with hammer) open to 3 or more tiles of water source.

* Running power in your "steam tunnels" is not an awful idea, and will reduce the amount of incidental shocks occurring, but requires pre-planning.

* See [this imgur post](https://imgur.com/r/feedthebeast/e0rgiiR) for a Age 2 water tower distribution network. 

## Immersive Engineering/Tech/Petroleum

* Put a crafting station next to your coke oven to easily make treated wood. The bucket input and output slots are visible as attached inventory slots in the crafting station. You can also use a Jerrycan to do 10x crafting recipes at once.

* After making the Engineer Manual and Workbench, focus on shooting for Thermo electric generators. Put ~6 of them diagonal to eachother. Down 1 bishop's line put lava (the hottest liquid you have). In the next bishop’s row put Liquid starlight (the coldest liquid you have). Repeat for each bishop’s line making opposite sides of the generator with maximum extremes of temperature liquids.

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_32.jpg)

* Except power, first thing you should make is a Metal Press (more efficient rods and wires).

    * Have the press feed into a chest.

* Craft capacitors to store power. Put LV Wire Connectors on the generators. Use LV Wire to connect to a central LV Wire relay, then connect that to a capacitor. Make sure the capacitor has a blue ring to receive power.  Now you can pick it up and power the Core Sampler. Once you've found oil you are going to want to string power to the Pump Jack (an LV capacitor powers it for 30 seconds, not enough time). You can either connect the capacitor with wire to the Core Sampler or use the hammer to make one side of the Capacitor orange (output power) and place the Core Sampler on that side to power it directly.  Create 4-5 capacitors and stack them end to end, so the input is coming in the top, and you power your stuff from the bottom. This gives you a deep buffer to power your machinery.

* The main quest progresses through the Immersive Petroleum and a part of the Immersive Tech questline, you will need a lot of steel to complete it, but otherwise it is fairly straightforward.

* Wire Connectors can pass power through a block by putting a connector on the opposing side and right clicking with a hammer.

* Engineering components are cheaper in the workbench than in the crafting grid.

* In Immersive Petroleum, you will be required to find (using the Core Sampler) and create an Oil Pumpjack. The oil will go through the Distillation Tower, which will turn it into Naphtha and Diesel. Additionally, the tower will spit out Bitumen as another byproduct. Both the Naphtha and the Diesel have their uses, so be sure to store them.

* The Pumpjack can also be used to collect non-oil liquids from the core (beneath bedrock), such as water and lava. This is one method of collecting the liquids for crafting uses, though do note that just like the oil this is finite.

* When you need power on the go, the terminals of an HV capacitor can connect directly to contacts of the core drill (and charging station) saving quite a lot of fiddly setup and teardown of wires. Make sure the capacitor is showing an orange face on the side you place adjacent to the drill/charger.

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_33.png)

* If you navigate to a multiblock in the engineers manual then craft the book with the projector, it will make the projector project that multiblock. Crafting it with anything else removes the ghost from the world. You can rotate the projection by middle clicking.

* All machines in the 3 mods (Immersive Engineering, Tech, and Petroleum) use up a good amount of power. You want a just as effective power generation to power these machines, especially the constantly active ones. The strongest power generation possible at this level is Biodiesel, which produces 4096 rf/t with a upkeep requirement (due to the machines required to get the biodiesel) of 904 rf/t (wiki says Fermenter requires 8rf/t). You can also wait until Age 4 and use a different powergen option, like the ones from Advanced Generators.

* Having 2 garden cloche feeding melon slices to the fermenter and 3 garden cloches feeding melon seeds to the squeezer should maintain 2 diesel generators working giving a constant 8192 rf/t.  Industrial hemp seeds, which you can get from the market and then grow in a cloche, are another good option for the squeezer.

* Try to get the Crusher, Squeezer, and Arc furnace as early as possible. These three machines are the key components to ore doubling (finally!) and will be very helpful in the long run. Make sure to have the power to maintain these though, as they do use up a fair amount of power.

    * Enchant the electrodes with Unbreaking to greatly extend their lifetime

    * Use a wooden hopper to place 1 item at a time, thus spreading out ores over the 12 input slots.

* You have access to Garden Cloches. Use Pumpjack for the water (again, finite), and make sure to have the power to maintain them. These are very useful farms which also take up a very minimal space. Alternatively, you can use a well bucket and a liquid hopper as an infinite water source.

* You can attach a capacitor directly to your kinetic generator, no connectors needed

* The portable generator is a cheap and easy way to produce power, once you've acquired gasoline. However, it's rather inefficient, and isn’t viable for building a self-sustaining oil industry. 

* You can have a 2x2 solar tower grid with each tower sharing 2 solar panels with its neighbors. Only the top block of the solar panel needs access to the sky.

* Just make a boiler (not solar) and then only long enough to get two buckets of steam. That'll be enough to get to age 4, then you can use a heat exchanger (advanced generators) to get cheap steam. One bucket of lava makes at least 6x more steam than a bucket of diesel (and you can use the diesel for power or kerosene instead). As of 3.0.8, lava doesn't seem to work in a boiler.  Biodiesel does, however.

* If you are just rushing to Age 4, then consider re-using your modular machinery blocks to switch between the three modular machines required to make plastic. You only have to switch out one or two blocks to switch between chemical mixer to liquid processor and etc. But there won't be an alternative way to make plastic in Age 4, so you’ll need a full setup sooner or later.

### Metal Press Automation

Metal presses are slow, and feeding them by hand is tedious. A slightly more sophisticated configuration makes it possible to batch arbitrary amounts of ingredients, even if the (gears) contain multiple input ingots.

* *Single-ingredient automation:* A hopper inputting *directly* into the input belt of the machine press, and some sort of inventory directly on the output will feed single ingots into the machine as they become available.

* *Multi-ingredient automation*:  You will need four things: an extracting conveyor belt attached to a chest or similar inventory, wirecutters, and a redstone clock from the cyclic mod. Position the extracting belt such that items falling off of the belt will fall onto the input belt of the press (you may need to upgrade to caged belts or glass walls if you are wearing magnetic armour), and the redstone clock immediately adjacent to the belt. The belt will stop extracting when it gets a redstone signal. With the wirecutters you can adjust the extraction timing of the belt to 4 ticks. You can then set the redstone clock with a duration (redstone on) around 64, and a delay (redstone off) of 4 times the number of ingots to drop. This will eliminate huge item spewing issues and offers a way to set-and-forget large item pressing batches. Once you advance into the next age, you can run belts or simple inventory managers to the output of the machine to have these resources automatically move into storage. Using the extracting belt means that extracted items can fall onto the metal press. Using a hopper (base 8 ticks) would require an extra belt to insert onto in any event.

## ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_34.png)![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_35.png)

## Airship

* Even though the airship looks cool, it's not on the main questline and it’s very expensive to make. It requires you to upgrade the extended crafting table, and then make the airship using a lot of resources. Prioritize other progression before making it.

## Blood Magic

While normal spawners only spawn 400 mobs, Betweenlands spawners are infinite. Use them below your blood alter and harvest spawns with 

## Infinite Ores

Mark/Ritual of the Falling Tower is a high tier Blood Magic ritual requiring 1M blood and summons a meteor directly from the sky. Put an obsidian block 20 blocks above the center to catch the meteor.  Use Ritual of Magnetism to pull the meteor's ores into a 3x3x3 and the Ritual of the Crusher to mine it.

This mining process bypasses SevTech's mining, allowing you infinite access to diamonds.

The best bang for the buck is using a gold block to initiate the Ritual of the Falling Tower.

Steve's carts

# Age 4

**Ores:** Assorted Quartz (affected by Fortune), Silicon Ore, Ardite Ore (Nether normal gen) and Cobalt Ore (Nether normal gen)

**Tools:**** **If you didn't unlock Journeymap in Age 2 or 3, it will automatically unlock on entering Age 4.

**Key Items: **

## Uncategorized Tips

* In Age 4 you unlock the Large Storage Crate from Actually Additions, which gives you three pages of 13x9 storage (351 stacks in total) in a single block. This is just over 3 times as efficient as the obsidian chests, and the best part is that they still work with crafting stations for easy one-click recipe crafting. Until you have a decent gui storage method, this is a very viable solution to overly complicated chest layouts.

* Ender Utilities is now open. Tooltips are super informative.

    * Note: The Ender Bag only works with vanilla chests

* Hopping Bonsai pot lets you farm wood easily and is cheap

* The Enchantment Extractor lets you pull "Experience Boost" enchant and put it onto a sword. Combine with the Mob Imprisonment Tool (which remembers mob HP when captured) to make an XP/Loot farm.

    * Enchantment Applicator can boost Astral Sorcery enchants which are higher than vanilla versions. Use the Fluid Converter to change out Cyclic XP for Essence.

    * The Mob Duplicator has a range of 1, ie. on top. No need to blow/push mobs into your grinder.

* IF's Rancher gets around BWA’s Fleece and harvests wool from sheep directly, this can also occasionally be a source of powdered dye production from further processing the coloring byproducts from crushing wool

* IF's Water Condensator produces about 100mb/t of water per water source block adjacent to it

* A fairly cheap way to get fast transportation from your base to the end is to make a Astral Sorcery Celestial Gateway. The Celestial Gateway needs sky above it to operate, so place it above the stronghold (or make a skylight down to the End portal). You can also make the gateway directly in the End. *you can name the gateway in an anvil and the name will appear above the star.

* After going to the End, you can use the Ender Utilities' portal (portal frame blocks + 1 or more portal control panels with 1-8 linking crystals in each panel) to easily set up cost-free teleportation to wherever you want (cross-dimensional), as long as you’ve linked the location to a linking crystal. You can pair this with an Ender Porter with it’s own linking crystal to go back to your base from anywhere (Advanced Ender Porter needed for the teleport back to be cross-dimensional). The Porter needs an ender capacitor, but the portal multiblock does not.

* There are several pre-cobalt pickaxe heads able to mine cobalt. These are: Obsidian, Twilight Forest's Knightmetal, Blood Magic’s Bound Pickaxe, and Abyssalcraft metals (abbysalnite, refined coralium, dreadium). Abyssalnite is found in Darklands biomes below Y = 32. It’s VERY rare. Refined coralium is made by smelting down Liquified Coralium, found at Y = 22 and below in the Abyssal Wasteland dimension (not too hard to find, definitely easier then abyssalnite). Note that the Abyssal Wastelands have a bunch of shrine looking things with ladders underneath them (you need to break a block to open the passage) with chests very often containing abyssalnite and other goodies. Dreadium ingots can be acquired in the Dreadlands most easily by using the Transmutator on certain mob drops from that dimension. Just don’t use a tool made from Dreadium as a weapon, as explained above. 

* Refined Storage can be connected to a drawer controller via a [External Storage](https://refinedstorage.raoulvdberge.com/wiki/external-storage) connector.

* Combine an XP Tap, Ariel interface, and liquid hopper to recycle XP. This let's you recharge items with the Mending enchant for free.

* Applied Energistics Storage Bus can also be attached to a drawer controller. Set the priority high to automatically store items in the assigned drawers connected to the drawer controller. This is a great way have your favourite items like ingots on display and be connected to your ME network.

* Before going to the moon bring either a Celestial Gateway or the ender utilities portal setup. The age advancement freezes your game for a little bit and can cause you to crash before the game unfreezes. If you get stuck, you can use the command /gchouston to return to the world spawn point on Earth.

* To get rocket fuel (just called fuel) you need to make an Oxygen collector and pipe the oxygen into an IE refinery with Kerosene.

* Remember a parachute when traveling in the rocket, this isn't advance rocketry where the engine control the landing. You need a parachute or you will crash land. Note that when you travel to the moon it resets your spawn and you’ll be in a death loop as you respawn without your spacesuit.

* To get a very cheap and easy supply of wood, sticks, and fruit, set up a Bonsai Hopper with your choice of sapling

    * Bonsai trees void all surplus production, so if you don't want a specific product (like leaves or sticks), put a drawer under a bonsai hopper and place in the materials you want to keep

    * You can use both Oak and Menril saplings to get an infinite and cheap supply of Fruit nutrition with apples or Menril Berries (Menril Berries can also be crafted into Menril Torch)

* Alien Villagers use Lunar Sapphires as currency. You can find these in dungeon chests, or trade them for Jungle Saplings.

* As of Version 3.0.8, currently unresolved, the Mechanical Squeezer will drain an infinite amount of power constantly. To counter this, use a LV or MV capacitor to reduce the power transfer rate and a breaker switcher or switchable aluminium wire to turn it on and off as required. 

* Don't bother with compacting drawers to store ingots, they do not convert between blocks and ingots.

## Storage

There are 3 main ME systems available: Refined Storage, Applied Energistics, and Simple Storage.

Refined and Applied don't yet have the ability to do automated crafting, nor deep storage. Thus all 3 are at best a way to sort your junk into a central system that can make crafting much easier.  Use a Junk Storage to store your non-stackable items and useless junk.

### Simple Storage

This mod allows you to connect the core storage block to your existing storage chest layout, as well as a tablet for remote access. The tablet comes in 2 flavors, a 64 block radius, and an advanced one for multi-dimensional access. At this point in your progression the advanced tablet is not that expensive. The Large Storage Crate mentioned earlier will also connect to this network for easy mass storage. Combine this ability with the advanced tablet for all the storage you'd ever need and the ability to craft anything with your items anywhere in the game. 

### Refined Storage

SevTech has gated refined storage on the same inscription plates that AE has, requiring a fair bit of tech either way. Thankfully you can craft them instead of exploration for meteors and a high tier pick. 

The primary purpose in going this route is if you plan on upgrading to the computation plate in age 5 for auto-crafting.

Because you don't have much in terms of storage, using obsidian chests and external storage busses will be the way to go for storage.

#### Tips

* Grab the wrench made out of quartz to rotate the inscriber, allowing you to use a hopper for all 3 inputs, thus automating circuits.

* Actually Additions Large Crates hold considerably more items than obsidian chests and can interact with the external interface

### Applied Energistics

See refined storage above. SevTech has both mods with enough item gating that both paths are equivalent.
 	

## Power Generation

* You have a few options for power generations at this point, most of which are connected to diesel.

* Immersive Engineering: Having 4 garden cloche with melon seeds feeding melon slices to the fermenter and hemp fiber seeds to the squeezer can maintain 2 diesel generators working, giving a constant 8192 rf/t, use MV connections and not LV.

    * For infinite water use an Immersive Engineering Pump connected to a 2x2x2 or 1x3x1 hole full of water sources, use the hammer to set input to one side facing the water and output to the side facing the pipe. Needs energy and a redstone signal to work. A well next to a single water source block will also provide enough water for around 9-10 Garden Cloches without a problem, and doesn't require power.

    * Adding a tank between the refinery and the generator can give a Biodiesel buffer

    * For crafting melon into melon slices use an Automatic Crafter from Inductive Logistics, set them to craft 4 (1 from each garden cloche)  items at a time to speed them up.

        * Alternatively a compacting drawer will also convert a melon to 9 slices. You'll need to filter the output to only the slices (easiest way is to another locked drawer with slices), and the compacting drawer is a little expensive at this stage, but might be worth considering.

    * The Automatic crafter takes inputs from an adjacent inventory and you need pipes to extract the output.

    * Any pipe should work, I like the Inductive logistic ones (Extraction, Transport and Injection).

    * The Obsidian chest is fairly cheap (8 obsidian blocks and a chest) and has plenty of inventory.

    * When out of energy a few watermills can "Jump Start" the setup.

* An alternative source is a Steam Turbine + Alternator connected to a solar tower (or more than one). With the only input being water, you get a steady stream of RF and a peak output of 24kRF/t (6 4kRF HV lines). A 512B tank holds enough steam to run an arc furnace through 24 stacks of steel (12 at a time) with no buffering (see below). Once setup, there is no upkeep required. Each bucket of steam produces about 1.25MRF, or 2.6 seconds of 24kRF/t. Note: This can be lossy as the steam turbine outputs 24kRF/t on demand, regardless of actual power draw. So building a buffer and running it only when your buffer is low is highly recommended.

     ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_36.jpg)      ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_37.png)

* Advanced Generators: A Gas turbine feed with Kerosene and with an Air/Gas Mixer for efficiency can give nice power output.

    * To output RF from it use a Forge Generator connected to a Power Adapter.

    * Adding a Gas Mix Compressor when enough ender pearl are available will further enhance the efficiency.

### Schmitt Triggers

A schmitt trigger is something that turns on at a certain level, and then turns off at a different level. [This post](https://www.minecraftforum.net/forums/minecraft-java-edition/redstone-discussion-and/2980824-redstone-schmitt-triggers) has a diagram of redstone based schmitt triggers. 

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_38.png)

Building a do-nothing trigger to understand the various components is very important. 

The main insight needed for a schmitt trigger at this tech level is that an HV capacitor can output it's fill-level via a comparator. It is important not to use the wireless transmitter and receiver from cyclic, as they do not preserve the redstone level, but only presence/absence of signal.

* I use the redstone block to indicate a known strong redstone source. In the actual deployment, this is linked to a lever next to an iron door (rotated to be closed when the power is on). 

* The side redstone input represents the signal coming from the singular HV capacitor. As they will tend to drain in series, rather than in parallel, choose a capacitor that is in the "middle of the pack" (of 8) and easy to access as your diagnostic output.

## ![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_39.png)![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_40.png)

* It's important to make sure that when the HV capacitor is full, the signal the first subtraction comparator applies zeros out the redstone signal. Some playing with signal strength is warranted. This configuration results in outputting a redstone signal when charge is needed. (I hit my generators with a hammer to have them only turn on when they get a redstone signal)

## Pneumaticcraft

You need to get your hands on compressed iron. The metal press has a plate for that, but it's much more efficient to use TNT for it (Only 20% loss compared to 55%). Angry pebbles from the between lands also provide enough of an explosion to create compressed iron. It’s easy to assemble the pressure chamber 3x3x3. Remember to make 2 interfaces and a valve. The interfaces has an "I" or input side and an “O” side or output. Make sure you have one input and one output on the outside of the chamber. Hook up an air compressor with pipes to the valve and use a lever on the compressor to turn it on and off (you will need to configure it). Note that before turning on pressure into pipes, loop the pipe back onto itself making a closed loop, otherwise your compressed air fizzes out. Place a chest on the output interface and a hopper going into the input interface. You are still able to click on the output interface and you need to setup filters so it won’t pull out the items you are trying to process. Start with filtering for compressed iron and then throwing in iron ingots into the hopper. With pressure adding to the system you should be able to get compressed iron much easier.

**Warning:** pressure has a max and you can have machine blow up if they go into the red. This is why its important to be able to shut off the compressor. Safety valves and security upgrades can be useful in preventing explosions, and you can shut off the compressor using a simple redstone + pressure gauge system.

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_41.jpg)

You will need a plastic mixer to get colored plastic (note this plastic is different from the Industrial Foregoing plastic) The mixer requires heat, a torch is very slow to heat, lava is slow and will turn to obsidian after a while. You can use blood magic's serenade of the nether to get lava and place it all around the mixer to speed up the heat. Or you can just use a vortex heater. Using molten plastic from Modular Machines bypasses the need to be heated. It uses red,green, and blue dye powder to color the plastic and if heated high enough can remelt unused plastics.

Compressed iron and green plastic makes a circuit board, which then you place in the UV light (which does require pressure) after it hits 100% throw it in some etching acid (made in the pressure chamber) Note with items floating in this pack make sure you block in your acid completely, half stabs on the bottom will let the board flow out of the acid. 

The tablet needs a charging station like the wrench and when you have a charge, you will need to shift right click on the tank that contains the fluid to sell, or on the chest with the item to sell. And then shift right click on the tank/chest for the sold item to go into. Right click with the tablet, right click to add to your order. Then click the order button for the drones to first take the item, then delivery the item.

When it comes to making the assembling line you will need a pneumatic wrench, right click the IO assembler arm to turn it blue, Blue is the the input and orange is the output

## Initial Automation (and drawbridges)

The lesser-known mod: [Modular Routers](https://github.com/desht/ModularRouters/wiki) can automate PCB, Engineering, and Logic Circuit creation (barring only the manual processing of galacticraft metals). It will be far less tedious to use this mod after you are able to visit the end, as the "Connect to any inventory within 12 blocks" level 2 modules require ender eyes (process ender pearls at a chalice-equipped lightwell for free eyes) to function. 

* The primary constraint of the item router is that it can only buffer a single stack of items internally. To enable batch processing, make sure that each "batched" ingredient is moved around by its own item router. The blocks themselves are cheap, it's the ender eyes for easy routing that are expensive.

* Through strategic pullers, senders, and whitelists, the above is all that's needed for logic and engineering circuits. 

* For PCB automation, having multiple item exporters pulling (filtered) items from your pressure chamber will make automation easier. Then have a buildcraft automated crafter taking finished parts from a modular router adjacent to it, with the router pulling from various chests as appropriate. 

* Modular routers can also place blocks in the world, providing for farming, automatic harvesting of cactus, drawbridges, and secret doors.

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_42.png)![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_43.png)

# Age 5 

**Tools: **

**Key Items: **See individual Galacticraft section

Stage 5 really opens to be a kitchen sink pack with a lot of default recipes and minimal tweaks in configs. The only real big recipe changes are the creative items.

Mob duplicator and Mob Crusher can be your friend on getting hard to find mob drops. Any spawner that you can stabilize with spawner agitator (or building in a slime chunk) can get you mob essence which you can use with the mob duplicator to get any mob you have capture in a mob imprisonment tool. Making a RFtools spawner with a wither essence is another good idea as the mob crusher will kill the wither instantly and convert its xp into mob essence.

## Uncategorised Tips

* With your earliest emerald and diamond (use the starlight transmutation to swap their ore blocks around and starlight infusion to get 4 stones per ore) craft an inventory upgrade from cyclic (and maybe crafting table if you do not yet have a simple remote). 

* A powered diamond anvil is a good way to repair your expensive weapons and armour from previous ages if you don't have the mending perk from astral sorcery or steel leaf tinker's items.

* You can upgrade your gold backpack to a diamond backpack for more personal storage if you don't have a universal remote from simple storage.

* The speed charm provides a meaningful (stacking) bonus to speed, even when in astral sorcery creative mode flight. (the spectral wings perk combined with the Vicio mantle of stars provides no-upkeep creative flight.)

## Power

* RFTools Powercells transport power interdimensionally

* Aluminium wires have an unlimited transfer rate and are extremely cheap to make. One of the best power transfer options, especially late game.

* A great early Age 5 power generation is Advanced Generators. You can make Low Grade Charcoal in Kilns, mill it up with a horse powered millstone and then pump into a Syngas producer, use the Syngas in a Gas Turbine Generator and you get 1k+ RF/t easily.

* Alternately, an Advanced Generators Heat Exchanger with a single heat exchanger is sufficient to power an Immersive Tech Steam Turbine/Alternator setup with little water/lava required.   The Alternator can only connect to IE wiring but IE connectors can connect to Mekanism Universal power cables.  The major cost for the setup is the amount of steel required for the turbine/alternator setup. You can connect universal cables to HV capacitors for maximum power output from the alternators.

    * A lava fabricator connected to a MV capacitor to reduce power draw will happily provide a Advanced Generators heat exchanger with enough lava to keep up with steam production demand, and produce a little extra lava on the side. You can increase the power drain by using HV Capacitor or alternate power method to create a supply of lava. A turbine will produce 26k rf/t, and the HV capacitor will only draw 4096 maximum.

    * 3 or 4 wells around a single water source block will provide a heat exchanger with enough water to produce plenty of steam to happily power two Steam Turbines. Very low cost to set up and, doesn't require redstone or power. A basic mechanical pipe from Mekanism set to pull will suck out the water from the well in to the heat exchanger. 

## Ore Processing

* The starlight infuser is excellent for early age 5 diamond duplication, returning 4 diamonds to 1 silk touched ore. Starlight transmutation can make emerald ore out of diamond ore.

* Mekanism Metallurgic infusers have a 1:5 tin to copper ratio for making bronze

* Putting a diamond into the enrichment chamber can get you 8 times the diamonds for the infuser. This is true of any recipe in the infuser that can accept a compressed variety of the item. E.G. Carbon (coal), Redstone, and Refined Obsidian.

* Mekanism Ore quintupling is now available, though very expensive. To get started, you will need a Purification Chamber, Crusher, Enrichment Chamber, and the other machines necessary to get them and to maintain them (P.C. requires Oxygen, created by the electrolytic separator when water is processed). Note that you cannot ore double with Mekanism, as it creates a different type of iron dust that cannot be processed. This forces you to go straight for Ore tripling. After getting this, you can slowly progress towards upgrading your machines and power gen, while working towards ore quadrupling and quintupling (4x and 5x).

* If you silk touch mine Silicon and Redstone, you get Silicon and Redstone Ores. You can crush the ores with a Actually Additions crusher into a lot more resources than you would get if you simply mined the geolosys ores. This can help you get your 64k drive more easily. Other ores this works with is: Lapis, Coal, Nether Quartz (don't silk touch assorted quartz though).

* Once you have decent power generation, a T1 Void miner from EnvironmentalTech is easy to make. It needs about 660RF/t.

    * Make a bee-line for Erodium and upgrade your solar panels to tier 2 erodium panels. A Tier 2 void miner consumes the same energy as Tier 1.

    * A Speed Modifier will double the energy consumption of the void miner.

* The Electric Arc Furnace from Galacticraft will DOUBLE outputs of ordinarily smelted ores. This is extremely useful for Meteoric Iron and Unrefined Desh!

## Storage

* Quantum Storage Disks (from Quantum Storage compat with Refined Storage) store 2.14B items of any types and are very cheap, it trivializes most other storage options in the pack

* As far as item transfer (if you don't count the computer system), unfortunately there is no Ender IO in the pack. The closest thing I could find is Inductive Logistics (and later on xnet might be a better option).

* Modular Routers is also quite effective for item transfer.

## Space

* Consider diving into the astral sorcery teleportation for quick access to oxygen.

* Pressing shift to dismount while in a spaceship is possible, yet your rocket will still fly off. DON'T DISMOUNT.

* You'll want an oxygen collector if you plan on doing anything productive on other planets. Leaves and crops create oxygen for it to collect.

* If you eat the cyclic "Inventory Upgrade" pie you get another backpack-like inventory. There is a key-binding to swap armor sets with the left-most slots. This is helpful when going back and forth between space and the overworld

* Despite the Tooltip saying you don't need RF on your spacesuit, failing to do so makes it get destroyed super quick. Enchant with Unbreaking to reduce this damage.

* If you put mending on your space suit you can repair the durability with XP. Use the XP Spiggot to recycle XP into durability.

* Desh is a critical ingrediant going forward. Use excavation to mine out areas leaving the desh exposed.

* After you obtain Desh on Mars, both the RFTools Matter Transmitter/Receiver and Mekanism Teleporter can be built as well.

* The Slime Sling is a great mode of transportation on the low gravity planets.

* Living armor with Elytra upgrade and air sigil is also great transport

* The weirding gadget only works while you are in space. Slightly helpful to farm meteors.

* The Spawner Seeker from Cyclic can be used to find the dungeons on the planets.  It has a range of 128 blocks and will find the spawners in the dungeon.  You may have to make multiple jumps using the slime sling but it's often easier than searching for the entrances.

* If you get stuck on a planet in a death loop or no way to get home, you can type /gchouston in the chat twice to be sent back to world spawn

* Mercury is the same tier as Asteroids, but offers Solid Meteoric Iron much more easily. You can find both Solid Desh and Solid Meteoric Iron asteroids on the surface of Mercury, each yielding over a stack of the solid block. 

### Moon

* Can trade for the Tier 2 Rocket schematics with villagers if you don't feel dungeon crawling for one

    * Note: you need the buggy schematic to get the rocket and the rocket to get the buggy schematic.

* GalactiCraft ores are not staged, and therefore fake players can quarry them

    * For quarrying, the two best options are RFtools Builders with a storage filter module (for blacklisting)

        * Some ores (ilmenite being one) do have issues with metadata matching with ores. There are some cases where you may not be able to use a filter from RFTools and have to void off the materials you don't need. The Builder has a problem with filtering out the Ilmenite with the base rocks. Storage Drawers with void upgrades work great for this on the other hand.

    * Note that the ingots are not the same as the ones you've created up till now, so you may find crafting recipes don’t work with them.

* Use Meteoric Iron sparingly until you get to the Asteroid belt as it's generation requires waiting in either the moon or mars

* Dungeon generation is different than before, dungeons do not share the same coordinates going from one planet to another

### Mars

* Has a higher meteor rate than the Moon

Asteroid Belt

* Ilmenite (titanium) is found in the asteroids along with meteoric iron.  

### Mercury

* One of the few GalactiCraft planets where you actually need the pressure suit as Armara + natural food regen cannot out heal the damage from this planet's environment.

* Mercury is required, not Venus.

### Venus

* Venus is super corrosive, as are the other gas giants. Sadly this is the only place to get the item that counteracts the corrosion. If you don't have enough regen then you’ll die and respawn on venus forever. So before you go here plan on teching up to fast regen. Probably will need to do the Armara regen, or possibly bring an rftools env controller with remote power to do some regen, or use a nanotech beacon with regen.

* The Tier 4 rocket plan say it's from Venus, but it's really from Mercury.

### Jupiter

* The dungeon is a little bit harder to find due to the fog, lightning storm, and monotone color palette of Jupiter, this was a screenshot of the dungeon entrance that I almost missed

![image alt text]({{ site.url }}/public/BMbpD6rCZ1qoniF20u7H2A_img_44.png)

* Saturn, Uranus, Neptune

    * Same as the others, quarry it, loot it's dungeon

## Automation

* Once you get the calculation plate you can start investing in autocrafting with either Refined Storage or AE2

* Refined storage has the advantage of the quantum storage disks and not needing to worry about channels

* Extended crafting tables have a block to allow for automation, it does take power tho.

* Automating the metal press can be done by adding one extra conveyor belt and a hopper, normally you can just use a hopper, but any recipe that takes more than one item needs an extra belt.  Keep in mind that with this change, the hopper no longer directly inserts items into the conveyor.  This will cause items to despawn when doing large batches.

Astral Sorcery

* To automate getting star metal and stardust, use Refined Storage (or Applied Energistics) Constructors and Destructors with Vanilla Iron Ore linked to a Collector Crystal.

    * You can change Iron Ore Clusters/Space Iron/Abyssalcraft Iron into Vanilla Iron Ore with the Oredictionificator.

## Mystical Agriculture:

Tier 6 seeds work in the Garden Cloche, but don't work with dirt. You'll need the appropriate Crux as the "dirt", or a block of Insanium Essence for the tier 6 Inferium seed.

Garden Cloches are pretty fast with mystical agriculture/other crops, but I found that a 9x9 field surrounded by Cyclic sprinklers + 1 in the center is a bit faster. A Cyclic Harvester set to Area will do the area all at once also. Other alternatives like the AA farmer or IF Plant Gatherer can't keep up with the speed of the overlapping sprinklers. The Harvester does take RF power, even though it looks like it only takes coal as power.

It's possible to begin Mystical Agriculture without going to Space. The Mekanism Oredictionificator is capable of converting Iron and Copper ore into Kepler 22b Iron and Copper ore. This in turn can be used in Starlight Transmutation to create Inferium Ore and Prosperity Ore, thereby bypassing the need for Saturn Slime ore to create your first inferium.  

# Creative age

	Reached by making the Ultimate crafting grid. It doesn't have the normal shape to tell you it unlocks the next age.

# Creative tips

You can complete all the quests by using the following command (Note severe lag)

/advancement grant playerName everything

You can revert to the beginning with 

/gamestage clear PlayerName

You can complete individual quests with the following command followed by one of the below quests (prerequisite in parenthesis). Note this is a dump (minecraft/config/triumph/script/...) from 3.0.4 so may be outdated.

/advancement grant playerName only triumph:stageX/(some triumph from below)

<table>
  <tr>
    <td>stage0</td>
    <td>stage1</td>
    <td>stage2</td>
  </tr>
  <tr>
    <td>kiln</td>
    <td>claybarrel</td>
    <td>stevescarts</td>
  </tr>
  <tr>
    <td>saltflats</td>
    <td>tin</td>
    <td>market</td>
  </tr>
  <tr>
    <td>horsechopper</td>
    <td>woodbasin</td>
    <td>depth</td>
  </tr>
  <tr>
    <td>tipi</td>
    <td>gearbox</td>
    <td>smeltertank</td>
  </tr>
  <tr>
    <td>grill</td>
    <td>prospector</td>
    <td>lapis</td>
  </tr>
  <tr>
    <td>workblade</td>
    <td>parchment</td>
    <td>gold</td>
  </tr>
  <tr>
    <td>flintknapp</td>
    <td>cart</td>
    <td>stopwatch</td>
  </tr>
  <tr>
    <td>chestupgrade</td>
    <td>stepup</td>
    <td>resonatingwand</td>
  </tr>
  <tr>
    <td>fish</td>
    <td>bloodaltar</td>
    <td>mapping</td>
  </tr>
  <tr>
    <td>melterbase</td>
    <td>parrot</td>
    <td>paper</td>
  </tr>
  <tr>
    <td>atlas</td>
    <td>beneath</td>
    <td>piston</td>
  </tr>
  <tr>
    <td>farmland</td>
    <td>astable</td>
    <td>wool</td>
  </tr>
  <tr>
    <td>woodhopper2</td>
    <td>dung</td>
    <td>starpowder</td>
  </tr>
  <tr>
    <td>lead</td>
    <td>chest</td>
    <td>skywave</td>
  </tr>
  <tr>
    <td>charcoal</td>
    <td>alloykiln</td>
    <td>extendedcraftingbasic</td>
  </tr>
  <tr>
    <td>wheel</td>
    <td>crafting</td>
    <td>betweenlands</td>
  </tr>
  <tr>
    <td>flamehopper</td>
    <td>hoe</td>
    <td>bucket</td>
  </tr>
  <tr>
    <td>workstump</td>
    <td>axle</td>
    <td>enderman</td>
  </tr>
  <tr>
    <td>abyssalgem</td>
    <td>huntingdim</td>
    <td>twilight</td>
  </tr>
  <tr>
    <td>weaponize</td>
    <td>furnace</td>
    <td>tcontable2</td>
  </tr>
  <tr>
    <td>upgrade</td>
    <td>turntable</td>
    <td>weedwoodsticks</td>
  </tr>
  <tr>
    <td>fiber</td>
    <td>coal</td>
    <td>weedwoodsword</td>
  </tr>
  <tr>
    <td>woodenbarrel</td>
    <td>bucket</td>
    <td>rockcrystal</td>
  </tr>
  <tr>
    <td>totemic</td>
    <td>blackquartz</td>
    <td>compass</td>
  </tr>
  <tr>
    <td>horsepower</td>
    <td>tchannel</td>
    <td>drawertable</td>
  </tr>
  <tr>
    <td>lowgradecharcoal</td>
    <td>statue</td>
    <td>biomealyzer</td>
  </tr>
  <tr>
    <td>handgrind</td>
    <td>pedestal</td>
    <td>wateringcan</td>
  </tr>
  <tr>
    <td>collectplank</td>
    <td>plumbline</td>
    <td>dowsingrod</td>
  </tr>
  <tr>
    <td>tomahawk</td>
    <td>stoneanvil</td>
    <td>iron</td>
  </tr>
  <tr>
    <td>melter</td>
    <td>aqueduct</td>
    <td>conpaper</td>
  </tr>
  <tr>
    <td>abyssalbiome</td>
    <td>necro</td>
    <td>lightwell</td>
  </tr>
  <tr>
    <td>mill</td>
    <td>leafbed</td>
    <td>glass</td>
  </tr>
  <tr>
    <td>buffalo</td>
    <td>extension</td>
    <td>tcontable1</td>
  </tr>
  <tr>
    <td>firsttool</td>
    <td>aquamarine</td>
    <td>controller</td>
  </tr>
  <tr>
    <td>saddle</td>
    <td>journal</td>
    <td>tcontable3</td>
  </tr>
  <tr>
    <td>firepit</td>
    <td>bronze</td>
    <td>astable2</td>
  </tr>
  <tr>
    <td>spear</td>
    <td>waterwheel</td>
    <td>weird</td>
  </tr>
  <tr>
    <td>firstbreak</td>
    <td>copper</td>
    <td></td>
  </tr>
  <tr>
    <td>baykok</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>firstchest</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>mesh</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>fluidbladder</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>mat</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>leather</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>woodhopper1</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>fire</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>gear</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>stonetools</td>
    <td></td>
    <td></td>
  </tr>
</table>


<table>
  <tr>
    <td>stage3</td>
    <td>stage4</td>
    <td>stage5</td>
  </tr>
  <tr>
    <td>crudeoil</td>
    <td>silicon</td>
    <td>wirelesscharger</td>
  </tr>
  <tr>
    <td>iehammer</td>
    <td>ardite</td>
    <td>creativemodifer</td>
  </tr>
  <tr>
    <td>drawercontroller</td>
    <td>rsgrid</td>
    <td>creativeenergycube</td>
  </tr>
  <tr>
    <td>blazerod</td>
    <td>cobalt</td>
    <td>emerald</td>
  </tr>
  <tr>
    <td>projector</td>
    <td>launchpad</td>
    <td>diamond</td>
  </tr>
  <tr>
    <td>rails</td>
    <td>blockheads1</td>
    <td>inferiumessence</td>
  </tr>
  <tr>
    <td>steel</td>
    <td>amadrontablet</td>
    <td>prospectorstage5</td>
  </tr>
  <tr>
    <td>oreprospector</td>
    <td>manyullyn</td>
    <td>diamondjetpack</td>
  </tr>
  <tr>
    <td>circuitboard</td>
    <td>solidendereye</td>
    <td>t2rocket</td>
  </tr>
  <tr>
    <td>bauxite</td>
    <td>printedcircuitboard</td>
    <td>charger3</td>
  </tr>
  <tr>
    <td>liquidplastic</td>
    <td>endercrafter</td>
    <td>osmium</td>
  </tr>
  <tr>
    <td>vacuumtube</td>
    <td>certusquartz</td>
    <td>spacesuit4</td>
  </tr>
  <tr>
    <td>standardhull</td>
    <td>moon</td>
    <td>neptune</td>
  </tr>
  <tr>
    <td>netherbrick</td>
    <td>enderalloy3</td>
    <td>ultimateingot</td>
  </tr>
  <tr>
    <td>creosote</td>
    <td>pressurechamberwall</td>
    <td>creativefluidtank</td>
  </tr>
  <tr>
    <td>filteredhopper</td>
    <td>inscriber</td>
    <td>electrumjetpack</td>
  </tr>
  <tr>
    <td>platinum</td>
    <td>extendedcraftingelite</td>
    <td>scanner</td>
  </tr>
  <tr>
    <td>iebook</td>
    <td>spacesuit</td>
    <td>cheese</td>
  </tr>
  <tr>
    <td>conveyorbelt</td>
    <td>machinecasing</td>
    <td>prosperityshard</td>
  </tr>
  <tr>
    <td>woodhull</td>
    <td>compressor</td>
    <td>desh</td>
  </tr>
  <tr>
    <td>galgadorian</td>
    <td>laserassembly</td>
    <td>mars</td>
  </tr>
  <tr>
    <td>redstone</td>
    <td>plasticmixer</td>
    <td>creativecompressor</td>
  </tr>
  <tr>
    <td>naphtha</td>
    <td>ae2panel</td>
    <td>skystone</td>
  </tr>
  <tr>
    <td>workbench</td>
    <td>compressediron</td>
    <td>emeraldjetpack</td>
  </tr>
  <tr>
    <td>amethyst</td>
    <td>t1rocket</td>
    <td>creativejetpack</td>
  </tr>
  <tr>
    <td>oreexcavation</td>
    <td>prospector4</td>
    <td>ultimatecraftingtable</td>
  </tr>
  <tr>
    <td>steam</td>
    <td>fuelloader</td>
    <td>marsrover</td>
  </tr>
  <tr>
    <td>bellows</td>
    <td>enderalloy1</td>
    <td>saturn</td>
  </tr>
  <tr>
    <td>propene</td>
    <td>blockheads3</td>
    <td></td>
  </tr>
  <tr>
    <td>sampledrill</td>
    <td>enderalloy2</td>
    <td></td>
  </tr>
  <tr>
    <td>windmill</td>
    <td>blockheads2</td>
    <td></td>
  </tr>
  <tr>
    <td>modularmachinery</td>
    <td>theend</td>
    <td></td>
  </tr>
  <tr>
    <td>hibachi</td>
    <td>nasaworkbench</td>
    <td></td>
  </tr>
  <tr>
    <td>silverlead</td>
    <td>presses</td>
    <td></td>
  </tr>
  <tr>
    <td>distillation2</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>extendedcrafting1</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>netherexbiome</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>viescraft</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>waterwheel</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>stevescartsassembler</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>potash</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>plastic</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>bonehoe</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>compactmachines</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>netherwart</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>nether</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>buildcraft</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>nickel</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>soundmuffler</td>
    <td></td>
    <td></td>
  </tr>
</table>


# Cross-age Info

## Ore distributions

*(as of 3.0.6)*

<table>
  <tr>
    <td>Material</td>
    <td>Min Y</td>
    <td>Max Y</td>
    <td>Notes</td>
  </tr>
  <tr>
    <td>Aquamarine</td>
    <td>150</td>
    <td>246</td>
    <td>The Beneath only</td>
  </tr>
  <tr>
    <td>Autunite</td>
    <td>8</td>
    <td>33</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Azurite (copper)</td>
    <td>12</td>
    <td>44</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Bauxite (aluminium)</td>
    <td>45</td>
    <td>79</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Beryl</td>
    <td>4</td>
    <td>32</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Black Quartz</td>
    <td>2</td>
    <td>100</td>
    <td>The Beneath only</td>
  </tr>
  <tr>
    <td>Casserite (tin)</td>
    <td>44</td>
    <td>68</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Cinnabar (redstone)</td>
    <td>5</td>
    <td>12</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Coal</td>
    <td>48</td>
    <td>78</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Corrallium</td>
    <td>4</td>
    <td>56</td>
    <td>Overworld (All biomes) & Twilight Forest</td>
  </tr>
  <tr>
    <td>Galena (silver & lead)</td>
    <td>16</td>
    <td>50</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Gold</td>
    <td>5</td>
    <td>30</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Hematite (iron)</td>
    <td>32</td>
    <td>60</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Kimberlite</td>
    <td>2</td>
    <td>15</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Lapis</td>
    <td>10</td>
    <td>38</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Limonite (iron & nickel)</td>
    <td>6</td>
    <td>32</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Malachite (copper)</td>
    <td>39</td>
    <td>44</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Platinum</td>
    <td>3</td>
    <td>25</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Quartz</td>
    <td>6</td>
    <td>29</td>
    <td>Overworld & Twilight Forest</td>
  </tr>
  <tr>
    <td>Redstone Ore</td>
    <td>N/A</td>
    <td>N/A</td>
    <td>Twilight Forest in the hollowed out caves</td>
  </tr>
  <tr>
    <td>Sphalerite</td>
    <td>35</td>
    <td>55</td>
    <td>Only blacklisted in the nether & end</td>
  </tr>
  <tr>
    <td>Teallite (tin)</td>
    <td>8</td>
    <td>43</td>
    <td>Overworld, Beneath & Twilight Forest</td>
  </tr>
</table>


## Heatmap biomes

*Credit to /ChaoticNonsense on reddit for **[the researc*h](https://www.reddit.com/r/feedthebeast/comments/8crpq4/sevtech_heatmap_breakdown/)

## Climate:

SevTech does indeed use a heat/humidity grid system for its biome generation. The Z axis determines temperature, and the X axis determines humidity. Both follow a periodic pattern similar to a sine wave, where you move from one extreme to another, and the moderate levels are in between.

There are four Temperature levels, (hot, warm, cool, icy) and three humidity levels (dry, average, wet). As your coordinate values increase (Inc. X is east, Inc Z is south), you get the transitions listed below.

**Z (N/S)**: Warm -> Hot -> Warm -> Cool -> Icy -> Cool ->(repeat).

**X (E/W)**: Avg. -> Wet -> Avg.->Dry -> (repeat).

If one makes the grid of a full cycle in each axis, (now matching the cardinal directions) it looks like the table below. Obviously, the table wraps around when you go off an edge.

<table>
  <tr>
    <td>W/A</td>
    <td>W/W</td>
    <td>W/A</td>
    <td>W/D</td>
  </tr>
  <tr>
    <td>H/A</td>
    <td>H/W</td>
    <td>H/A</td>
    <td>H/D</td>
  </tr>
  <tr>
    <td>W/A</td>
    <td>W/W</td>
    <td>W/A</td>
    <td>W/D</td>
  </tr>
  <tr>
    <td>C/A</td>
    <td>C/W</td>
    <td>C/A</td>
    <td>C/D</td>
  </tr>
  <tr>
    <td>I/A</td>
    <td>I/W</td>
    <td>I/A</td>
    <td>I/D</td>
  </tr>
  <tr>
    <td>C/A</td>
    <td>C/W</td>
    <td>C/A</td>
    <td>C/D
</td>
  </tr>
</table>


There are a few other points/observations worth noting. The first, is that you will always spawn in a Warm Average zone. So generating a bunch of different worlds (as I did before this analysis) will get you nowhere. Also, there are four distinct Warm Average zones in the table; I can't say with certainty, but the settings make me suspect you spawn specifically in the Northwest corner of the table. The configs also specify that a full cycle is about 10k blocks. It didn't specify a direction on that, so I'm assuming the Humidity bands are about 2500 across, and the temperature bands are about 1700 across.

This information, with the classifications below, should be enough to find specific biomes more methodically. Good Luck!

## Biome Classification:

### Hot Dry:

* Red Desert - (Traverse)

* Desert

* Mesa

### Hot Average:

* Plains

* Mutated Plains

* Woodlands - (Traverse)

### Hot Wet:

* Jungle

* Swampland

* Mini Jungle - (Traverse)

### Warm Dry:

* Badlands - (Traverse)

* Savanna

### Warm Average:

* Forest

* Birch Forest

* Mutated Forest

* Mutated Birch Forest

* Autumnal Woods - (Traverse)

* Meneglin - (Integrated Dynamics)

* Meadow - (Traverse)

### Warm Wet:

* Roofed Forest

* Temperate Rainforest - (Traverse)

* Lush Hills - (Traverse)

* Green Swamp - (Traverse)

### Cool Dry:

* Extreme Hills

* Darklands Plains - (Abyssalcraft)

### Cool Average:

* Taiga

* Darklands Forest - (Abyssalcraft)

* Darklands - (Abyssalcraft)

### Cool Wet:

* Coralium Infested Swamp - (Abyssalcraft)

* Mutated Redwood Taiga

* Redwood Taiga

### Icy Dry:

* Ice Flats

* Mutated Ice Flats

### Icy Average:

* Snowy Coniferous Forest - (Traverse)

* Taiga Cold

### Icy Wet:

* Glacier - (Traverse)

* Glacier Spikes - (Traverse)

### Other: 

Oceans can go anywhere, and there are a ton of river/transitional/Hill variants of the above.

# How to replicate this

## Google Docs Tips

* People won't change the overall format even if they have the permission, so think good and hard about having a good high level flow.

* Use header formats rather than Bullet list nesting. Don't let bullets go further than 3 levels deep, pushing for extracting stuff into their own section.

* Enable link sharing with comment permission as the default. You can always add trusted people as direct editors using their **gmail** address.

* Because viewers can't sort by newest you'll have to make a revision history for them. Periodically go to the Version History and make a named version, then click last week's named version to see the diff. Print this diff to PDF. Upload that PDF to Google Docs or github for sharing. Record this link in the Recent Changes section of the Google Docs

* Use the Addon called Gabriel covered later.

* Know that there will be lots of lurkers looking directly at your doc. They will have it open on another screen and forget their focus is not on minecraft. Thus you'll get quite a few edit proposals to add 'e' to some place. This is annoying but worth the price for allowing random people to toss in proposals.

## Github Pages

* Github allows you to host a static website in their repo using Markup. Create a free github repo, go to settings, Choose a theme and have it populate your repo with the needed files. The README seems to be the only Markup file that you can access from the static site. We'll be pushing your above google doc to this README, but we need to do some prep work.

* Find the default.html file that your template uses and wrap the {{content}} section in a section and article. Add the tocible javascript and stylesheet to your page: [https://github.com/borg286/sevtech2/blob/master/_layouts/default.html#L15](https://github.com/borg286/sevtech2/blob/master/_layouts/default.html#L15)

* Add this script section to your page: [https://github.com/borg286/sevtech2/blob/master/_layouts/default.html#L32](https://github.com/borg286/sevtech2/blob/master/_layouts/default.html#L32)

* This will result in a dynamic table of contents that can look at your page and programatically create a table of contents based on the headers of the page. The one I linked above uses H1's as the first level, and H2's as subitems. You can see it in action here: [https://borg286.github.io/sevtech/](https://borg286.github.io/sevtech/)

## [Gabriel](https://chrome.google.com/webstore/detail/gabriel/okimajjeocnndpifeelaajdebkkbckff?utm_source=permalink)

* This is a Google Doc addon that can convert a google doc into markup and push it and images to a github repo.

* Grant access to your github repo, choose the root folder and change the name of the output file to [README.md](https://readme.md/)

* Before doing an export you'll want to download the html export from Google docs and find large images. These large image make the Gabriel exporter take longer pushing to Github. If this is more than about 3-5 MB then Gabriel times out. Find large images, downsize them, then replace them in the Google doc.

* After exporting to your github repo go back to github and edit the [README.md](https://readme.md/). Gabriel adds a heading section that conflicts with Github Pages. Delete the section starting and ending with ====. Sadly Github Pages will return a 404 after this. Simply edit the file again and make a small change and save it. This will trigger a push to the Github Sites caches.

## Alternatives considered

I had considered using Google Doc's native web view and embed the provided iframe into a skeleton site, but the formatting Google provides is so bad it is nigh unusable. The benefit of native web view is that it is always up-to-date. The downside is that we can't change the way it looks. The way browsers handle iframes protects the inner page from any poking from the parent page it is embedded into.

I had considered using Google Doc's native html export and simply uploading that to a static site storage site. The image links would work, and the size limit wouldn't be as much of a problem. The table of contents I wanted to add meant I'd have to either edit the top level html page every time I push, or have a page that uses javascript to pull the html from the same page and inject the javascript added above.

