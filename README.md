<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>Poogle</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
   <ul>
      <li><a class="active" href="index.html">Google</a></li>
      <li><a href="daum.html">Daum</a></li>
      <li><a href="youtube.html">Youtube</a></li>
      <li><a href="image.html">Image</a></li>
      <li><a href="polymath.html">Polymath</a></li>
    </ul>
   
    <h1><span>P</span><span>o</span><span>o</span><span>g</span><span>l</span><span>e</span></h1>
    <form action="https://www.google.com/search?q=" method="get">
        <div class="mx-auto search-bar input-group mb-3 rounded-pill">
            <input name="q" type="text" class="form-control" placeholder="검색어를 입력하세요" aria-label="검색어를 입력하세요" aria-describedby="button-addon2">
            <div class="input-group-append">
                <!--<button type="button" id="" class="btn btnEvent"><img src="search.png" alt="btnImages" class="btnImages" width="30px" height="30px">
                </button>-->
                <button class="btn btn-outline-secondary" type="button" id="button-addon2"><img src="search.png" alt="btnImages" class="btnImages" width="30px" height="30px"></button>
            </div>
        </div>
    </form>
    <!--<form action="https://www.google.com/search?q=" method="get">
        <div class="mx-auto search-bar input-group rounded-pill">
          <input name="q" type="text" class="form-control" placeholder="검색어를 입력하세요" aria-label="검색어를 입력하세요" aria-describedby="button-addon2">
          <div class="input-group-append">
            <button class="btn btn-outline-secondary dropdown-toggle" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Dropdown</button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
              <div role="separator" class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Separated link</a>
            </div>
          </div>
        </div>
    </form>-->
    
</body>
</html>
