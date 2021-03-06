# 푸드테크(음식 배달과 TECHNOLOGY)

> 조현준, CTO @Delivery Hero Korea님의 기사를 분석해 보자!
>
> 출처 : [https://medium.com/deliverytechkorea/%EC%9D%8C%EC%8B%9D-%EB%B0%B0%EB%8B%AC%EA%B3%BC-technology-384245adc7d7](https://medium.com/deliverytechkorea/음식-배달과-technology-384245adc7d7)



  최근 4–5년 간 배달 음식 업계는 매우 큰 변화를 겪고 있다. “철가방”을 든 배달원이 “짜장면 시키신 분~~”을 외치는 것으로 대표되던 대한민국 음식 배달이, 때와 장소를 가리지 않는 정도를 넘어 이제는 바닷가재, 스테이크덮밥에 심지어는 삼겹살 불판까지도 집으로 배달을 해 준다. __이처럼 편리하고 다양한 배달 음식 문화가 만들어진 데는__, 음식점에서 정성스럽게 음식을 만들어 주시는 분들이 계시고, 조리된 음식을 따뜻하게 집으로 배달을 해 주시는 배달원 분들의 노고가 있어서 이기는 하나, 한편으로는 __“technology”가 큰 역할을 했음을 부인할 수는 없다.__

```
  이 변화를 직접 겪은 세대로서, 나 또한 사람들의 삶에 변화를 주는 service를 개발하고 제공해보고 싶다. 내가 푸드테크에 기여할 수 있는 부분이 무엇이 있을까?
  전화로 음식 시키는 것을 귀찮아 했던 사람으로서, 어플 내 버튼을 클릭하는 것 만으로도 음식을 주문할 수 있었던 그 순간을 기억하자!
```



  __온갖 광고지와 전단지 책자들이 스마트폰 속으로 들어왔고__, 책장을 이러저리 넘겨 가며 어떤 음식점이 있는지 찾아야 했던 것이, __배달앱 검색창에서 손가락 몇 번 놀림으로 쉽게 해결__되며, 매일 무엇을 먹을지 고민하는 1인 가구주에게 우리동네 __맛집을 추천__해 주기도 한다. 늘 “5분 전에 출발했어요”라고 수화기 저편에서 들리던 사장님의 목소리는 이제 구세대 어른들의 옛 추억 속의 이야기가 되었고, __나를 위한 음식이 몇분 간의 조리 후 배달원들의 배달통 속에 담겨져 어느 경로로 오고 있는가까지 핸드폰으로 확인할 수 있는 시대__가 되었다. __인공 지능 스피커와 대화를 나누며 음식을 주문__할 수도 있고, 이전에는 배달하지 않던 맛집의 음식을 퇴근하는 차 안에서 집에 도착하는 시간에 맞추어 오게 할 수도 있다. 머지 않아 사람이 아닌 __로보트가 배달__을 하게 될 것이며, 한강 시민 공원에서 __드론이 배달해 주는 치킨__을 먹게 되기도 할 것이다. 이렇게 우리가 매일 먹어야 하는 음식을 편안하게 내가 원하는 곳에서 배달 받아 먹을 수 있게 하는 일을 하고 있다는 것이, Delivery Hero Korea의 CTO 이전에 한 사람의 개발자로서 너무 뿌듯하고, 책상에 앉아 아무도 읽지 않을 연구 논문을 쓰는 것보다 훨씬 잘 한 선택임을 다시 한번 나 자신에게 일깨운다.

```
  AI로보트로 주문을 한다거나, 로보트가 배달하거나, 드론이 치킨을 배달해주거나.. 결국 4차산업혁명 핵심 기술들이 음식에도 적용되는 것을 보여주는 예라고 생각한다. 이 부분이 내가 푸드테크에 가장 관심갖게 된 계기인 것 같다. 음식을 좋아하는 사람으로서, 첨단기술 개발에 함께하고싶은 사람으로서, 내가 개발한 서비스를 사람들이 사용하는 것을 보길 원하는 사람으로서! 
```



  물론, 지금까지의 여정이 결코 쉽지는 않았다. 사업 초기, __음식점 사장님들은 technology 라는 것에 익숙치 않은 분들이 대부분 이었고__, 컴퓨터를 잘 다루시지도 않았고, 스마트폰 어플리케이션이라는 것이 무엇인지도 모르는 분들이 많았다. 전화로 받는 주문 밖에 모르시는 분들에게, 메뉴를 컴퓨터에 입력하고 어플리케이션이나 문자로 들어오는 주문을 소화하게 하는 일은 사용자들에게 이 서비스를 알리는 것보다 훨씬 어려운 일이었다. 이를 극복하기 위해, 주문이 발생하면 __기존에 매장에서 쓰고 계시던 POS 기기로 주문이 바로 입력될 수 있도록 해당 기술을 개발__하고, __한 달에 주문이 얼마나 일어났는지를 보기 쉽게 만들어 제공__해 드리며, 우리가 매일 매일 모으는 __방대한 양의 데이터를 분석하여 개별 음식점 사장님들이 어떻게 하면 더 성장하실 수 있는지 컨설팅__을 해 드리기도 한다. 이미 40여개국에서 배달 대행 서비스를 제공하고 있는 딜리버리히어로의 기술을 활용하여 우리 회사 __배달원들이 최적의 경로를 따라 배달__을 하며 많은 수익을 올릴 수 있도록 우리 기술을 더 발전시켜 나가고 있고, 주문의 트랜드를 분석하여 수요에 맞춘 적절한 식자재 준비가 가능하도록 리포트를 해 드리려고 한다. __가능한한 음식점 사장님들은 음식 조리에만 집중할 수 있도록 해 드리고, 음식 주문과 배달은 모두 시스템이 알아서 편리하게 할 수 있도록 하기 위해 기술을 개발__하고 글로벌 네트워크의 노하우를 공유 받아 우리 것으로 만드는 작업을 늘 수행 하고 있다.

```
  가장 핵심이 되는 내용. 결국 딜리버리히어로코리아가 가고자하는 길인 것 같다.
  
  '음식점 사장님들은 음식 조리에만 집중하세요. 나머지는 저희가 알아서 해드리겠습니다.'
  
  데이터 분석을 통해 정확한 정보를 제공해드릴 뿐만아니라 사용자의 경험에도 초점을 맞춰 최적의 서비스를 제공하는 모습 정말 멋있다!
```



  사람들은 인공지능 또는 머신러닝 같은 기술을 이세돌과 바둑을 둔 알파고를 통해 접하지만 그런 기술들이 실제 어떤 곳에 쓰이는지는 잘 알 수 없다. 하지만, 우리는 인간이면 반드시 하는 “밥 먹기”를 더 편하게 할 수 있도록, 빅데이터를 분석하고 인공지능 기술을 통해 사용자들이 먹고 싶어 하는 음식을 추천하며, 댓글이나 설문에 남겨진 사용자들의 감정을 분석하여 더 나은 서비스를 제공하기 위해 많은 개발자들이 고민하며 새로운 기술을 익히고 또 우리 서비스를 발전시켜 가고 있다. 이 모든 과정들을 통해 현재의 대한민국 음식배달 문화는 만들어져 왔으며, 그 바탕에는 늘 technology가 있었고, 나는 오늘도 사용자들과 음식점 사장님들에게 더 좋은 서비스를 제공하기 위해 컴퓨터를 켜고 데이터를 분석하며 프로그램을 점검한다.

