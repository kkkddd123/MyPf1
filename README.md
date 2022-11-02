# MyPf1
my portfolio1
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Team Mod</title>
    <link rel="stylesheet" href="assets/css/images-compare.css"/>
</head>
<body>
    <div class="js-img-compare">
        <div style="display: none;">
            <span class="images-compare-label">상품1</span>
            <img src="assets/img/01-celine-skowron-before.jpg" alt="상품1">
        </div>
        <div>
            <span class="images-compare-label">상품2</span>
            <img src="assets/img/01-celine-skowron-after.jpg" alt="상품2">
        </div>
    </div>
    <!--왼쪽 사이드바-->
    <input type="checkbox" id="menuicon">
    <label for="menuicon">
        <span></span>
        <span></span>
        <span></span>
    </label>
    <div class="sidebar_a">
        <div class="sidebar_left">
            <div class="boxContainer_left">
                <table class="elementsContainer_left">
                    <tr>
                        <td>
                            <input type="text" placeholder="URL 입력(left)"
                            class="search">
                        </td>
                        <td>
                            <a href="#"><i class="fa-solid fa-magnifying-glass"></i>
                            </a>
                        </td>
                    </tr>
                </table>
                <div class="img_inputbox"></div>
                <button class="add-button"
            type="button">
            Add 
        </button>
            </div>
        </div>
    </div>
     
    <!--오른쪽 사이드바-->
    <input type="checkbox" id="menuicon_right">
    <label for="menuicon_right">
        <span></span>
        <span></span>
        <span></span>
    </label>
    <div class="sidebar_b">
        <div class="sidebar_right">
            <div class="boxContainer_right">
                <table class="elementsContainer_right">
                    <tr>
                        <td>
                            <input type="text" placeholder="URL 입력(right)"
                            class="search">
                        </td>
                        <td>
                            <a href="#"><i class="fa-solid fa-magnifying-glass"></i>
                            </a>
                        </td>
                    </tr>
                </table>
                <div class="img_inputbox"></div>
            </div>
        </div>
    </div>


<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/hammer.js/2.0.8/hammer.min.js"></script>
<script src="assets/js/jquery.images-compare.js"></script>
<script src="https://kit.fontawesome.com/b1cf78c6ff.js" crossorigin="anonymous"></script>
<script>
$(function () {
    var imagesCompareElement = $('.js-img-compare').imagesCompare();
    var imagesCompare = imagesCompareElement.data('imagesCompare');
});
</script>   
</body>
</html>
