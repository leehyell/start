# 🧐start
👌🏻 SpringBoot 시작할 때 밑작업이 되어 있는 레파지토리
<br/>
👌🏻 thymeleaf layout 되어 있음
<hr>
git clone 후 resources/templates/application.properties 파일의
<br/>
spring.datasource.username=
<br/>
spring.datasource.password=
<br/>
계정 변경 후 서버 실행
<hr>
🌫 구조:
<br/>
<ul>
  <li>java
    <ul>
      <li>config</li>
      <li>controller</li>
      <li>dto</li>
      <li>entity</li>
      <li>repository</li>
      <li>service</li>
    </ul>
  </li>
  <li>resources
    <ul>
      <li>static
        <ul>
          <li>css</li>
          <li>img</li>
          <li>js</li>
        </ul>
      </li>
    </ul>
    <ul>
      <li>templates
        <ul>
          <li>html</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>
<br/>
🌫 popup 종류
<br/>
<ul>
  <li>alert
    <ul>
      <li>- alert_whole div</li>
      <li>- 팝업 열기: alertShow(text1,text2)</li>
      <li>- 팝업 닫기: alertHide()</li>
    </ul>
  </li>
  <li>confirm
    <ul>
      <li>- confirm_whole div</li>
      <li>- 팝업 열기: confirmShow(text1,text2,type)</li>
      <li>- 팝업 닫기: confirmHide()</li>
    </ul>
  </li>
  <li>standby
    <ul>
      <li>- standby_whole div</li>
      <li>- 팝업 열기: standbyShow(text1,text2)</li>
      <li>- 팝업 닫기: standbyHide()</li>
    </ul>
  </li>
</ul>
※ 공통 팝업 닫기: commonHide()
<br/><br/><br/>
💌 궁금한 부분이 있다면?
<br/>
helena1005@naver.com
hellllena1005@gmail.com
