# tatasus20.html
<html>
 <head>
  <meta charset="utf-8">
  <meta name="description" content="소개">
  <meta name="keywords" content="코딩,자바">
  <meta name="author" content="going">
  <!--
  <meta http-equiv="refresh" content="5" alt=새로고침>
  -->
  </menu>
</head>
<body>
  <form action="http://localhost/login.php" method="post"
   enctype="multipart/form-data" autocomplete="on">

  <p><label for="id">아이디:</label>
    <input id="id" type="text" name="id"placeholder="id를 입력해주세요"
     required pattern="[a-zA-Z]."> </p>  <!--.은 어떤패턴이든 가능하다 -->
  <p><label for="password">비밀번호:</label>
    <input id="password" type="password" name="pwd"autofocus> </p>
  <p>주소:<input type="text" name="address"></p>
  <p><label>텍스트:
      <textarea cols="50" rows="10">default value</textarea>
      <input type="reset">
     </label>
  </p>
  <p><input type="submit"></p>

  <h1>색상(다중선택)</h1>
  <select name="color" multiple>
    <option value="red">붉은색</option>
    <option value="black">검은색</option>
    <option value="blue">파란색</option>
  </select>
    <input type="radio" name="color" checked>
  <label>
    <input type="checkbox" name="size" value="90">90
  </label>


<p> <input type="submit"></p>

<p> <input type="text" name="id">
    <input type="hidden" name="hide" value="egoing">
    <input type="submit" value="전송">
    <input type="button" value="버튼" onclick="alert('hello world')">
    <input type="reset"> </p>

    <p> <input type="file" name="">
        <input type="submit">

    <input type="number" mim="10" max="15">
    <input type="date" name="datev">
    <input type="email" name="emailv">
    <input type="submit">


</form>
</body>
</html>
