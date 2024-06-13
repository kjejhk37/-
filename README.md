<h1>자바스크립트를 사용한 추가 설명 창 생성 </h1>

![자세한 설명 예시](https://github.com/kjejhk37/Simple-Hover-explain/assets/118964808/be4807a3-b488-48c4-a062-3216e460188b)

<hr/>

<h2>createExplanationBox(MainId,Name, triggerContent,content,ImgURL)</h2>

마우스를 가져다 대면 추가 설명과 설명용 이미지를 보여주는 박스를 생성하는 함수입니다.

<b>MainId</b> : 추가 설명용 박스의 부모 박스 id입니다.
<br/>
<b>Name</b> : id를 설정하기 위한 고유 이름입니다.
<br/>
<b>triggerContent</b> : 트리거에 상시 표시될 텍스트입니다.
<br/>
<b>content</b> : 마우스를 Hover할 때 표시될 추가 설명 텍스트입니다.
<br/>
<b>ImgURL</b> : 마우스를 Hover할 때 표시될 추가 설명 이미지입니다.
<br/>

해당 트리거의 가장 상위 div의 id는 'Box' + Name
<br/>
트리거는 'trigger' + Name
<br/>
트리거 텍스트는 'Text' + Name
<br/>
숨겨진 추가설명의 가장 상위 div는 'hiddenBox' + Name
<br/>
숨겨진 추가설명의 텍스트 박스는 'hidden-Font' + Name
<br/>
숨겨진 추가설명의 이미지 박스는 'hidden-Image' + Name
입니다.
<br/>

