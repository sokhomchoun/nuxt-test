<template>
    <div class="container">
        <div class="control-header flex">
            <div class="relative manage-bg">
                <div class="logo bg-black text-white">
                    LOGO
                </div>
            </div>
            <div class="control-title-list">
                <div class="title flex align-center background">
                    <div class="bg-hover">
                        <div class="cursor-pointer categories">
                            <span class="text-gradient-hover">LỊCH TRỰC TIẾP</span>
                            <div class="alert-hover">
                                <div class="list-play flex align-center bong-da">
                                    <img :src="football" alt="">
                                    <span>BÓNG ĐÁ</span>
                                </div>
                                <div class="list-play flex align-center dua-bi">
                                    <img :src="duabi" alt="">
                                    <span>ĐUA BI</span>
                                </div> 
                                <div class="list-play flex align-center bong-ro">
                                    <img :src="bongro" alt="">
                                    <span>BÓNG RỔ</span>
                                </div>
                                <div class="list-play flex align-center e-sports">
                                    <img :src="esport" alt="">
                                    <span>E-SPORTS</span>
                                </div>
                                <div class="list-play flex align-center casino">
                                    <img :src="casino" alt="">
                                    <span>CASINO</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="bg-hover">
                        <div class="cursor-pointer categories">
                            <span class="text-gradient-hover">LỊCH THI ĐẤU</span>
                            <div class="alert-hover">
                                <div class="list-play flex align-center bong-da">
                                    <img :src="football" alt="">
                                    <span>BÓNG ĐÁ</span>
                                </div>
                                <div class="list-play flex align-center dua-bi">
                                    <img :src="duabi" alt="">
                                    <span>ĐUA BI</span>
                                </div>
                                <div class="list-play flex align-center bong-ro">
                                    <img :src="bongro" alt="">
                                    <span>BÓNG RỔ</span>
                                </div>
                                <div class="list-play flex align-center e-sports">
                                    <img :src="esport" alt="">
                                    <span>E-SPORTS</span>
                                </div>
                                <div class="list-play flex align-center casino">
                                    <img :src="casino" alt="">
                                    <span>CASINO</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="cursor-pointer categories"><span class="text-gradient-hover">TỶ LỆ KÈO</span></div>
                    <div class="bg-hover">
                        <div class="cursor-pointer categories">
                            <span class="text-gradient-hover">KẾT QUẢ</span>
                            <div class="alert-hover">
                                <div class="list-play flex align-center bong-da">
                                    <img :src="football" alt="">
                                    <span>BÓNG ĐÁ</span>
                                </div>
                                <div class="list-play flex align-center dua-bi">
                                    <img :src="duabi" alt="">
                                    <span>ĐUA BI</span>
                                </div>
                                <div class="list-play flex align-center bong-ro">
                                    <img :src="bongro" alt="">
                                    <span>BÓNG RỔ</span>
                                </div>
                                <div class="list-play flex align-center e-sports">
                                    <img :src="esport" alt="">
                                    <span>E-SPORTS</span>
                                </div>
                                <div class="list-play flex align-center casino">
                                    <img :src="casino" alt="">
                                    <span>CASINO</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="cursor-pointer categories"><span class="text-gradient-hover">PHÒNG CHAT</span></div>
                    <div class="cursor-pointer categories"><span class="text-gradient-hover">TIN TỨC</span></div>
                    <div class="flex control-btn">
                        <!-- <button class="btn cursor-pointer">ĐĂNG KÝ</button>
                        <button class="btn gradient-btn cursor-pointer"><span class="text-gradient">ĐĂNG NHẬP</span></button> -->

                        <div class="user-profile">
                            <div class="text-name">
                                Xin chào, NguyenVanDen
                            </div>
                            <div class="control-profile flex align-center relative">
                                <input type="checkbox" id="toggle-coin-first" class="toggle-input-coin" />
                                <div class="bg-active">
                                    <div class="coin bg-white flex align-center relative">
                                        <img class="img-coin" :src="cucoin" alt="">
                                        <div class="flex align-center list-price">
                                            <span class="text-price">1000</span>
                                            <div class="control-add-coin">
                                            <input type="checkbox" id="toggle-coin" class="toggle-input">
                                                <label for="toggle-coin" class="make-coin cursor-pointer">
                                                    <img class="img-add" :src="add" alt="">
                                                    <img class="img-sub absolute" :src="sub" alt="">
                                                    <div class="text-coin absolute">
                                                        <div class="take-coin flex align-center">
                                                            <img class="coin-gray" :src="coingray" alt="">
                                                            <span class="price-coin">20.000</span>
                                                        </div>
                                                        <div class="take-coin flex align-center">
                                                            <img class="coin-king" :src="king" alt="">
                                                            <span class="price-coin">20.000</span>
                                                        </div>
                                                        <div class="nap-them flex align-center">
                                                            <img class="coin-gray" :src="add" alt="">
                                                            <span>Nạp thêm</span>
                                                        </div>
                                                    </div>
                                                </label>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="email relative cursor-pointer">
                                    <img :src="bell" alt="">
                                    <div class="text-email absolute">10</div>
                                </div>
                                <div class="email relative cursor-pointer">
                                    <img :src="email" alt="">
                                    <div class="text-email absolute">2</div>
                                </div>
                                <img class="calandar cursor-pointer" :src="calandar" alt="">
                                <input type="checkbox" id="toggle" />
                                <label for="toggle">
                                <div class="action-user flex align-center relative cursor-pointer">
                                        <img class="user" :src="user" alt="">
                                        <img class="avatar absolute" :src="avatar" alt="">
                                    </div>
                                </label>
                                <div class="display-list ">
                                    <div class="list-user absolute">
                                        <div class="text-user flex align-center cursor-pointer">
                                            <img :src="businessman" alt="">
                                            <span class="text-trung">TRUNG TÂM TÀI KHOẢN</span>
                                        </div>
                                        <div class="text-user flex align-center cursor-pointer">
                                            <img :src="home" alt="">
                                            <span class="text-trung">TRANG CÁ NHÂN</span>
                                        </div>
                                        <div class="text-user flex align-center cursor-pointer">
                                            <img :src="arrow" alt="">
                                            <span class="text-trung">NHIỆM VỤ</span>
                                        </div>
                                        <div class="text-user flex align-center cursor-pointer">
                                            <img :src="cart" alt="">
                                            <span class="text-trung">VÍ CỦA BẠN</span>
                                        </div>
                                        <div class="text-user flex align-center cursor-pointer">
                                            <img :src="chart" alt="">
                                            <span class="text-trung">LỊCH SỬ GIAO DỊCH</span>
                                        </div>
                                        <div class="text-user flex align-center cursor-pointer">
                                            <img :src="exit" alt="">
                                            <span class="text-trung">THOÁT TÀI KHOẢN</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
                <div class="list flex align-center bg-black">
                    <div class="text-gradient flex align-center cursor-pointer list-img">
                        <img :src="vector" alt="">
                        <span>Bảng Tin</span>
                    </div>
                    <div class="text-gradient flex align-center cursor-pointer list-img">
                        <img :src="reels" alt="">
                        <span>Reels</span>
                    </div>
                    <div class="text-gradient flex align-center cursor-pointer list-img">
                        <img :src="highlight" alt="">
                        <span>Highlight</span>
                    </div>
                    <div class="text-gradient flex align-center cursor-pointer list-img">
                        <img :src="tip" alt="">
                        <span>Tip Kèo</span>
                    </div>
                    <div class="text-gradient flex align-center cursor-pointer list-img">
                        <img :src="video" alt="">
                        <span>Phim Ảnh</span>
                    </div>
                    <div class="text-gradient cursor-pointer flex align-center cursor-pointer list-img">
                        <img :src="book" alt="">
                        <span>Truyện Tranh</span>
                    </div>
                    <div class="flex control-btn-toggle">
                        <button class="language cursor-pointer flex align-center"><img class="img-logo" :src="Logo" alt="">
                            <span>TIẾNG VIỆT</span>
                        </button>
                        <div>
                            <label class="switch">
                                <input type="checkbox">
                                <span class="slider absolute cursor-pointer"></span>
                            </label>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup >
    import { ref } from 'vue';
    import Logo from '@/public/assets/imgs/vietnam_icon.png';
    import football from '@/public/assets/imgs/football.gif';
    import duabi from '@/public/assets/imgs/dua-bi.gif';
    import bongro from '@/public/assets/imgs/bong-ro.gif';
    import esport from '@/public/assets/imgs/e-sports.gif';
    import casino from '@/public/assets/imgs/casino.gif';
    import vector from '@/public/assets/imgs/vector.png';
    import reels from '@/public/assets/imgs/reels.png';
    import highlight from '@/public/assets/imgs/highlight.png';
    import tip from '@/public/assets/imgs/tip.png';
    import video from '@/public/assets/imgs/video.png';
    import book from '@/public/assets/imgs/book.png';
    import avatar from '@/public/assets/imgs/avata.png';
    import user from '@/public/assets/imgs/user.png';
    import calandar from '@/public/assets/imgs/calandar.png';
    import email from '@/public/assets/imgs/email.png';
    import bell from '@/public/assets/imgs/bell.png';
    import cucoin from '@/public/assets/imgs/cucoin.png';
    import add from '@/public/assets/imgs/add.png';
    import sub from '@/public/assets/imgs/sub.png';
    import businessman from '@/public/assets/imgs/businessman.png';
    import home from '@/public/assets/imgs/home.png';
    import arrow from '@/public/assets/imgs/arrow.png';
    import cart from '@/public/assets/imgs/cart.png';
    import chart from '@/public/assets/imgs/chart.png';
    import exit from '@/public/assets/imgs/exit.png';
    import coingray from '@/public/assets/imgs/coin-gray.png';
    import king from '@/public/assets/imgs/king.png';

</script>
