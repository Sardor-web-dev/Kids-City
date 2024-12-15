<template>
    <div class="container">
        <div class="header">
            <b>О нас</b>
            <b>Почему мы</b>
            <img src="./assets/images/Снимок экрана 2024-11-04 204337.png" alt="">
            <b>Услуги и товары</b>
            <b>Контакты</b>
        </div>
        <div class="main">
            <div class="text">
                <p class="big">Kids City – ваш надежный <br>
                 магазин качественной детской <br>
                одежды!
            </p><br><br><br>
            <span class="small">
                👕 Мы предлагаем широкий ассортимент стильной и удобной одежды для детей всех
                 <br> возрастов, от малышей до подростков. Каждый предмет подобран с любовью, чтобы ваш
                 <br> ребенок чувствовал себя комфортно и выглядел на все 100! <br>
            </span>
            </div>
        </div>
        <div class="products-part">
            <div class="txt-of-products">
                <p>Наши товары</p>
                <span>Самая лучшая и высококачественная детская одежда в Самарканде!</span>
            </div>
            <div class="products">
                <div class="product1">
                    <div class="product">
                        <img src="./assets/images/photo_2024-11-07_12-44-45.jpg" alt="">
                        <p class="p1">одежда для мальчиков</p>
                    </div>
                <button>Посмотреть в каталоге</button>
            </div>
            <div class="product2">
                <div class="product">
                    <img src="./assets/images/photo_2024-11-07_12-44-43 (2).jpg" alt="">
                    <p class="p2">одежда для девочек</p>
                </div>
                <button>Посмотреть в каталоге</button>
            </div>
            </div>
        </div>
        <div class="about">
            <div class="text1">
                <p>О нас</p>
                <span>
                В 2020 году во время пандемии COVID-19, основательница нашего магазина запустила интернет-магазин детской одежды в Самарканде.
                Сама идея возникла после нескольких неудачных покупок в интернет-магазинах, так как у нее были 3 детей, а магазины все закрыты,то  не тот размер отправляют, то качество очень низкое.
                Затем она решила поискать оптовых поставщиков детской одежды сначала экспортные товары с Узбекистана, позже и с Турции и Китая , этим же она хотела помочь другим мамочкам иметь возможность приобрести качественные вещи по приемлемым ценам для своих детей. Первыми клиентами были, конечно же родственники, подруги, знакомые и их знакомые.  
                В режиме онлайн работали около 3 лет, позже решили также открыть офф-лайн магазин, так как очень многие клиенты хотели не только оформлять заказы онлайн, а приезжать на примерку вместе со своими детьми, поближе ознакомиться с ассортиментом товаров .
                С апреля 2023 года мы начали работать в оффлайн режиме, предлагая своим клиентам иметь возможность приобретать качественную одежду для своих детей от 0 до 14 лет, работаем только с проверенными производителями с Китая, Турции и США.
            </span>
            </div>
            <img src="./assets/images/L_height (1).png" alt="">
        </div>
        <div class="best">
            <p>Почему мы лучшие?</p>
            <span>Три преимущества нашего магазина</span>
            <div class="facts">
                <div class="fact1">
                    <img src="https://cdn-icons-png.flaticon.com/512/5499/5499068.png" alt="">
                    <p>Высококачеставенная импортная одежда</p>
                    <span>У нас широкий ассортимент <br> высококачественной одежды по <br> хорошим ценнам, из Китая, США и Турции.</span>
                </div>
                <div class="fact2">
                    <img src="https://cdn-icons-png.flaticon.com/512/1156/1156685.png" alt="">
                    <p>Доставка по всей Республике</p>
                    <span>Нашу одежду можно заказывать онлайн <br> и можно приехать в магазин и <br> примерить понравившеюся вам <br> одежду, а также имеется доставка по <br> всей республике и не только</span>
                </div>
                <div class="fact3">
                    <img src="https://cdn-icons-png.flaticon.com/512/3735/3735864.png" alt="">
                    <p>Постоянные скидки и акции</p>
                    <span>В нашем магазине постоянно <br> проводятся разные акции и скидки в <br> связи с какими нибудь праздниками <br> либо просто при покупке более 2 <br> вещей</span>
                </div>
            </div>
        </div>
        <div class="photos2">
            <div class="ptxt">
                <p>Фотографии нашего магазина</p>
                <span>Это фотографии нашего магазина внутри и снаружи</span>
            </div>
            <div class="images">
            <img src="./assets/images/photo_2024-11-07_12-44-44 (2).jpg" alt="">
            <img src="./assets/images/L_height (1).png" alt="">
            <img src="./assets/images/photo_2024-11-07_12-44-44.jpg" alt="">
            </div>
        </div>
        <div class="contackts">
            <p>Контакты</p>
            <br><br>
            <span>Телефон: +998 97 397 00 34</span>
            <a href="https://www.instagram.com/kids_city_sam/">Instagram:  @kids_city_sam</a>
            <a href="https://t.me/kids_city_sam">Telegram:  t.me/kids_city_sam<</a>
            <br><br>
            <span>Адрес: Ул.Бустонсарой(Бирлик 24)</span>
        </div>
    </div>
</template>

<script>
export default{

}
</script>

<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
button{
    cursor: pointer;
}
.container{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.header{
    width: 100%;
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 75px;
    b{
        cursor: pointer;
        font-family:sans-serif;
        font-size: 25px;
    }
    img{
        margin-left: 105px;
    }
}
.main{
	position: relative;
    background-image:url(./assets/images/photo_2024-11-07_12-44-46.jpg);
    background-repeat: no-repeat;
    width: 100%;
    height: 600px;
    background-size: cover;

}
.text{
    margin-top: 50px;
    display: flex;
    flex-direction: column;
    gap: 15px;
}
.text1{
    width: 400px;
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.big{
    font-weight: bold;
    color: white;
    text-align: center;
    font-size: 48px;
}
.small{
    color: white;
    text-align: center;
    font-size: 35px;
}
img{
    width: 280px;
}
.txt-of-products{
    text-align: center;
    p{
        font-size: 35px;
    }
    span{
        font-size: 24px;
    }
}
.products-part{
    margin-top:50px ;
    display: flex;
    flex-direction: column;
    align-items:center;
    justify-content: center;
    gap: 25px;
}
.products{
    display: flex;
    gap: 15px;
    align-items: center;
    justify-content: center;
    button{
        text-align: center;
        width: 200px;
        height: 30px;
        background-color: #9f887e;
        color: white;
        border: none;
        border-radius: 10px;
        font-size: 16px;
    }
}
.product1{
    display:flex ;
    flex-direction: column;
    gap: 15px;
    align-items:center ;
    justify-content: center;

}
.product2{
    display:flex ;
    flex-direction: column;
    gap: 15px;
    align-items:center ;
    justify-content: center;
}
.product{
    display: flex;
    flex-direction: column;
    gap: 5px;
    align-items: center;
    justify-content: center;
    p{
        font-size: 24px;
    }
}
.p1{
    color: blue;
}
.p2{
    color: magenta;
}
.about{
    margin-top: 100px;
    display: flex;
    gap: 55px;
    p{
        font-size: 35px;
    }
    span{
        font-size: 20px;
    }
    img{
        width: 500px;
    }

}
.best{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: 100px;
    p{
        font-size: 45px;
    }
    span{
        font-size: 25px
    }
}
.facts{
    display: flex;
    gap: 45px;
    align-items: center;
    justify-content: center;
}
.fact1{
    display: flex;
    flex-direction: column;
    display: flex;+a
    flex-direction: column;
    gap: 15px;
    p{
        font-size: 20px;
    }
    span{
        font-size: 17px;
    }
}.fact3{
    display: flex;
    flex-direction: column;
    gap: 15px;
    p{
        font-size: 20px;
    }
    span{
        font-size: 17px;
    }
}
.sales{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: 100px;
    gap: 15px;
    p{
        font-size: 35px;
    }
    span{
        font-size: 20px;
    }
}
.promotions{
    margin-left: 25px;
    margin-left: 25px;
    display: flex;
    align-items: center;
    justify-content: center;
    p{
        font-size: 20px;
    }
    span{
        font-size: 16px;
    }
}
.photos2{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.ptxt{
    margin-top: 50px;
    display:flex ;
    margin-bottom: 20px;
    flex-direction: column;
    gap: 3px;
    p{
        font-size: 28px;
    }
    span{
        font-size: 20px;
    }
}
.images{
    display: flex;
    gap: 25px;
}
.contackts{
    margin-top: 50px;
    display: flex;
    align-items: center;
    flex-direction: column;
    width: 100%;
    background-color: #9f887e;
    color: white    ;
    height: 250px;
    p{
        font-size: 25px;
    }
    a{
        text-decoration: none;
        color: white;
        font-size: 25px;
    }
    span{
        font-size: 25px;
    }
}

</style>