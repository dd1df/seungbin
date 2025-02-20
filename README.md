<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>서비스 안내 페이지</title>
  <!-- 고급스러운 Playfair Display 폰트 로드 -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      background-color: #ffffff; /* 밝은 배경색 */
      background-image: url('https://www.transparenttextures.com/patterns/paper-fibers.png'); /* 밝은 패턴 */
      color: #333; /* 텍스트 색상을 어두운 색으로 변경 */
      text-align: center;
      font-family: 'Playfair Display', serif;
      padding: 20px;
      margin: 0;
    }
    h1 {
      font-size: 30px;
      margin: 20px 0;
    }
    ol {
      font-size: 30px;
      list-style-position: inside;
      padding: 0;
      margin: 0 auto;
      max-width: 600px;
      text-align: left;
    }
    li {
      margin-bottom: 15px;
      line-height: 1.4;
    }
    a {
      color: #0077cc;
      text-decoration: underline;
    }
    /* 모바일 가독성을 위한 반응형 디자인 */
    @media screen and (max-width: 600px) {
      body {
        font-size: 28px;
      }
      h1, ol {
        font-size: 28px;
      }
    }
  </style>
</head>
<body>
  <h1>서비스 안내 😊</h1>
  <ol>
    <li>직원을 불러 영수증을 받아주세요! 😊</li>
    <li>
      영수증을 받으셨다면 아래 링크로 들어가주세요!<br>
      <a href="https://m.place.naver.com/my/checkin" target="_blank">https://m.place.naver.com/my/checkin</a> 😊
    </li>
    <li>영수증을 터치 후 카메라로 영수증을 찍어주세요! 😊</li>
    <li>후에 나오는 리뷰를 순서대로 작성해주세요! 😊</li>
    <li>보여주시면 주류/음료 한 개가 서비스로 지급됩니다! 😊</li>
  </ol>
</body>
</html>
