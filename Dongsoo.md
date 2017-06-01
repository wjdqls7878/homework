# 스마트 동시 통역 기기

## 6조
### 이시온, 이정현, 조동수, 이학재

1. 문제 정의

 *외국어 의사소통*에 어려움을 격지 않기 위해 
 **부실한 번역 프로그램을 _개선한 장치_**. 혹은, 프로그램

2. 요구사항

 * 사용자에게 신속하고도 정확한 번역을 제공해야 한다
 * 휴대성이 좋아야 하므로 웨어러블 디바이스의 형태로 착용이 가능해야 한다
 * 미묘한 뉘양스(+반어법, 비유법, 중의적 표현 등*)를 번역할 수 있어야 한다
 * 잡음을 제거해 음성정보인식을 정확히 할 수 있어야 한다
 * 이어폰이나 무선 이어폰으로 연동할 수 있어야 한다
 * 휴대하는 기기와 스마트기기와 무선으로 연결할 수 있어야 한다

3. 필요성

 * 언어의 다양성으로 인한 교육의 어려움
 * 번역 보조 도구의 신속성 부족
 * 번역 프로그램의 정확성 부족

4. 해결방안

 * 빅 데이터 기반으로 처리 한다
 * 목걸이나 시계 등의 웨어러블 디바이스 형태로 만든다
 * 1. 음의 높낮이나 톤에 따른 데이터 수집을 통해서 말하는 사람의 어조를 구분한다
   2. 같은 문장에 대한 유사한 다수의 번역을 제공해 사용자가 선택할 수 있어야 한다
 * 노이즈 캔슬링 기능을 통해서 목소리 이외의 음성을 걸러낸다.
 * 이어폰 모드를 추가한다
 * 블루투스를 통해 휴대기기와 스마트 기기를 연결한다.

5. 링크

 [유사한 제품 ili ](blog.naver.com/PostView.nhn?blogid=mrwiver&logNo=220615614485)
 [마크다운에 관해 참고][1]
 [마크다운 위키피디아]

 [1]: http://en.wikipedia.org/wiki/Markdown "Wikipedia"
 [마크다운 위키피디아]: http://en.wikipedia.org/wiki/Markdown "Wikipedia"

6. 표

 Markdown | Less | Pretty
 --- | --- | ---
 *Still* | 'renders' | **nicely**
 1 | 2 | 3

7. 코드
 inline 'code' hsa 'back-ticks around' it.

 ```javascript
 var s = "JavaScript syntax highlighting";
 alert(s);
 ```

 ```python
 s = "Python syntax highlighting"
 print s
 ```

 ```C
 char s;
 s = 'C syntax highlighting';
 printf("%c", s);
 ```

 ```C++
 string s;
 s = 'C++ syntax highlighting';
 cout << s << endl;
 ```

8. 이미지

 ![마크다운 로고](https://raw.github.com/dcurtis/markdown-mark/master/png/208x128.png)

9. 인용

 > 인용이다.
 > 인용 안에서도 문단을 나눌 수 있다.
 >
 > ### 제목 드으이 다른 문법도 사용 가능하다.
 > 
 > > 인용 안의 인용도 된다.
