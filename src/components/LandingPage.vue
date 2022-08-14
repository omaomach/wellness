<template>
<div class="header">
        <img class="logo" src="../assets/logo.png"/>

    <div class="floatRight1">
        <div class="digits">
            254728748441
        </div>

        <div class="phoneNumber">
            <i class='fas fa-phone' style='font-size:24px'></i>
        </div>

        <div class="email">
            wellnessenprevention@gmail.com
        </div>

        <div class="mail">
            <i class='far fa-envelope' style='font-size:24px'></i>
        </div>

        <div class="link1">
            FAQ's
        </div>

        <div class="friends">
            <i class='fas fa-user-friends' style='font-size:24px'></i>
        </div>
    </div>
            

</div>

<div class="topMid">

    <div class="links2">

        <div class="home">
            Home
        </div>

        <div class="blog">
            Blog
        </div>

        <div class="products">
            Products
        </div>

        <div class="prices">
            Prices
        </div>

        <div class="team">
            Team
        </div>

        <button class="loginBtn">LOGIN</button>

    </div>
</div>

<div class="topMid2">

    <div class="makeAnAppointment">
        <div class="questions">
            <h4>Are questions about<br>your health you would like to discuss</h4>
        </div>
        <div class="questionsP">
            <p>In practice, care is extremely overburdened<br> 
            and there is not always time to talk about<br> 
            other medical complaints that you would like to<br> 
            discuss.</p>
            <p>Even if you want to take a proactive approach<br> 
            to your health, it is difficult to discuss, as it is <br>
            not considered urgent. Still, it is advisable to <br>
            invest in your health</p>
        </div>

        <button class="makeAppointmentBtn">Make an appointment</button>

    </div>

    <div class="patientImageDiv">
        <img class="patientImg" src="../assets/wolverine.jpg"/>
    </div>

</div>

<div class="expectnBot">
    <div class="expect">
        <p>What can you expect at the Medical Consultation?</p>
    </div>
    <div class="chatbotIcon">
        <i class='fas fa-comments' style='font-size:36px'></i>
    </div>
</div>

<div class="tableDiv">
    <table style="width:100%">
        <tr>
            <th>
                <div class="circle1">
                    1
                </div>
            </th>
            <th>
                <div class="circle2">
                    2
                </div>
            </th>
            <th>
                <div class="circle3">
                    3
                </div>
            </th>
        </tr>
        <tr>
            <td>Describe your complaint</td>
            <td>Speak to our doctor</td>
            <td>Consultation</td>
        </tr>
        <tr>
            <td>16</td>
            <td>14</td>
            <td>10</td>
        </tr>
    </table>
</div>

</template>

<script>
export default {
    name : 'LandingPage'
}
</script>

<style>

.header {
    display: inline-block;
    width: 100%;
    margin: 0;
    padding: 0;
}


.logo {
    width: 228px;
    height: 141px;
    margin-left: 32px;
    float: left;
    padding: 0;
}

.floatRight1 {
    margin-top: 95px;
    padding: 0;
}

.digits {
    float: right;
    color: #6674DD;
    margin-right: 20px;
    font-size: 20px;
    font-style: 'Abhaya Libre';
    font-weight: 400;
    line-height: 24px;
    padding: 0;
}

.friends {
    float: right;
    margin-right: 5px;
    padding: 0;
}

.mail {
    float: right;
    margin-right: 5px;
    padding: 0;
}

.email {
    float: right;
    color: #6674DD;
    margin-right: 30px;
    font-size: 20px;
    font-style: 'Abhaya Libre';
    font-weight: 400;
    line-height: 24px;
}

.phoneNumber {
    float: right;
    margin-right: 5px;
}

.link1 {
    float: right;
    color: #6674DD;
    margin-right: 30px;
    font-size: 20px;
    font-style: 'Abhaya Libre';
    font-weight: 400;
    line-height: 24px;
}

template {
    margin-top: 0px;
    margin: 0;
    padding: 0;
}

i {
    color: #FF00FF;
}

.topMid {
    background-color: rgba(102, 116, 221, 0.11);
    width: 100%;
    height: 65px;
    margin-top: 0;
    margin: 0;
    padding: 0;
    position: relative;

}

.links2 {
    padding: 0;
    margin-top: auto;
    margin-bottom: auto;
    display: inline-block;
    width: 100%;
    position: absolute;
    top: 25%;
}

.home {
    float: left;
    margin-left: 80px;
    font-family: 'Abhaya Libre';
    font-style: normal;
    font-weight: 400;
    font-size: 28px;
    line-height: 33px;
    height: 33px;
    color: #6674DD;
}

.blog {
    float: left;
    margin-left: 65px;
    font-family: 'Abhaya Libre';
    font-style: normal;
    font-weight: 400;
    font-size: 28px;
    line-height: 33px;
    height: 33px;
    color: #6674DD;
}

.products {
    float: left;
    margin-left: 65px;
    font-family: 'Abhaya Libre';
    font-style: normal;
    font-weight: 400;
    font-size: 28px;
    line-height: 33px;
    height: 33px;
    color: #6674DD;
}

.prices {
    float: left;
    margin-left: 65px;
    font-family: 'Abhaya Libre';
    font-style: normal;
    font-weight: 400;
    font-size: 28px;
    line-height: 33px;
    height: 33px;
    color: #6674DD;
}

.team {
    float: left;
    margin-left: 65px;
    font-family: 'Abhaya Libre';
    font-style: normal;
    font-weight: 400;
    font-size: 28px;
    line-height: 33px;
    height: 33px;
    color: #6674DD;
}

.loginBtn {
    float: right;
    width: 200px;
    height: 36px;
    color: white;
    border-radius: 10px;
    font-family: 'Abhaya Libre';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    background-color: #FF00FF;
    border-color: #FF00FF;
    margin-right: 40px;
}

.topMid2 {
    width: 100%;
    display: inline-block;
}

.makeAnAppointment {
    position: absolute;
    width: 625px;
    height: 450px;
    margin-left: 5px;
    margin-top: 100px;
    background: rgba(102, 116, 221, 0.85);
    box-shadow: inset 0px 4px 4px rgba(0, 0, 0, 0.25);
    border-radius: 30px;
}

.questions {
    width: 548px;
    height: 80px;
    margin-left: 25px;
    margin-top: 5px;
    font-family: 'Abhaya Libre';
    font-style: normal;
    font-weight: 600;
    font-size: 29px;
    line-height: 36px;
    color: #000000;
    padding: 0;
}

.questionsP {
    width: 540px;
    height: 116px;
    margin-left: 25px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 400;
    font-size: 24px;
    line-height: 29px;
    color: #FFFFFF;
    margin-bottom: 15px;
    margin-top: 0;
}

.makeAppointmentBtn {
    width: 222px;
    height: 28px;
    margin-left: 390px;
    margin-top: 135px;
    background: #FF00FF;
    border-radius: 10px;
    border-color: #FF00FF;
}

.patientImageDiv {
    float: left;
    width: 1325;
    height: 550px;
    margin-top: 48px;
    margin-left: 513px;
    border-radius: 30px;
}

.patientImg {
    width: 1325px;
    height: 550px;
    border-radius: 30px;
}

.expectnBot {
    width: 100%;
    margin-top: 25px;
    display: inline-block;
    height: 80px;
    position: relative;}

.expect {
    width: 695px;
    height: 54px;
    background: #6674DD;
    box-shadow: inset 0px 4px 4px rgba(0, 0, 0, 0.25);
    border-radius: 10px;
    position: absolute;
    margin-left: 30.5%;
    top: 50%;
    -ms-transform: translateY(-50%);
    transform: translateY(-50%);
    text-align: center;

}

.chatbotIcon {
    margin-left: 95.5%;
    float: right;
    position: absolute;
    top: 50%;
    -ms-transform: translateY(-50%);
    transform: translateY(-50%);

}

.expect p {
    color: #FFFFFF;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 400;
    font-size: 24px;
    line-height: 29px;
    margin-top: 1.9%;
}

.tableDiv {
    text-align: center;
}

table, th, td {
  border:1px solid black;
  text-align: center;
}

.circle1 {
    background-color: #FF00FF;
    color: #FFFFFF;
    border-radius: 50%;
    height: 50px;
    width: 50px;
    text-align: center;
    margin-left: auto;
    margin-right: auto;
}

.circle2 {
    background-color: #FF00FF;
    color: #FFFFFF;
    border-radius: 50%;
    height: 50px;
    width: 50px;
    text-align: center;
    margin-left: auto;
    margin-right: auto;
}

.circle3 {
    background-color: #FF00FF;
    color: #FFFFFF;
    border-radius: 50%;
    height: 50px;
    width: 50px;
    text-align: center;
    margin-left: auto;
    margin-right: auto;
}

</style>