# WitrynaZadanie

#KOD

.skills-info-cont {
        background-color: var(--bgc);
        color: var(--main-color);
        padding: 20px 0;
    }
    .skills-info {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    
    .skill {
        background-color: var(--bgc);
        color: var(--main-color);
    }
    
    .h3-cont h3 {
        text-align: center;
        font-size: 45px;
        padding-left: 0;
        background-color: var(--bgc);
        color: var(--main-color);
    }
    
    .skills-desc {
        font-size: 25px;
        padding-left: 10px;
        flex-basis: 50%;
        padding-right: 0;
    }
    .t-cont {
        display: flex;
        justify-content: center;
        font-size: 30px;
    }
    .t-cont h3 {
        text-align: center;
        padding: 0%;
    }
    
    .skills-cont {
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        margin:10px 30px;
    }
    .skill-card {
        margin: 10px;
        height: 300px;
        width: 300px;
        background-color: var(--projects-color);
        color: var(--main-color);
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        border-radius: 10px;
    }
    .s-img-cont img {
        height: 300px;
        width: 350px;
    }
    .skill-card h4 {
        font-size: 25px;
    }
    .skill-outline {
        font-size: 30px;
        color: #0903bb;
        -webkit-text-stroke: #0903bb 2px;
    }
    .line-hor {
        background: var(--main-color);
        border: var(--main-color) solid 0px;
        border-radius: 0;
        width: 0;
        height: 0;
    }
    .line-up {
        background: var(--main-color);
        border: var(--main-color) solid 3px;
        border-radius: 10px;
        width: 10px;
        margin-left: 100px;
        height: 80px;
    }
    
    .line-mid {
        background: var(--main-color);
        border: var(--main-color) solid 3px;
        border-radius: 10px;
        width: 10px;
        margin-left: 100px;
        height: 150px;
    }
    .begin {
        display: flex;
        text-align: center;
        font-size: 20px;
        padding-right: 10px;
    }
    
    .school {
        display: flex;
        text-align: center;
        font-size: 20px;
        padding-right: 10px;
    }
    
    .go {
        display: flex;
        text-align: center;
        font-size: 20px;
        padding-right: 10px;
    }
    
    .learn {
        display: flex;
        text-align: center;
        font-size: 20px;
        padding-right: 10px;
    }
    .bug-outline {
        color: #03fc41;
        -webkit-text-stroke: #03fc41 2px;
    }
    
    .contact-form {
        background-color: var(--main-color);
        color: var(--bgc);
        padding-top: 35px;
    }
    
    .contact-info {
        display: flex;
        flex-direction: column-reverse;
        align-items: center;
    }
    
    input {
        border-bottom: 3px solid #03fc41;
        border-top: transparent;
        border-left: transparent;
        border-right: transparent;
        background-color: var(--main-color);
        color: var(--bgc);
        padding: 15px;
        margin: 10px;
        font-size: 25px;
    }
    
    input:focus {
        outline: none;
        font-size: 25px;
    }
    
    .contact-form h3 {
        text-align: right;
        font-size: 50px;
        padding-right: 100px;
    }
    
    form {
        display: flex;
        flex-direction: column;
        width: 400px;
        padding: 100px;
        flex-basis: 40%;
    }
    
    .submit-cont {
        display: flex;
        justify-content: center;
    }
    
    .submit {
        width: 50%;
        border-radius: 10px;
        padding: 10px;
        margin: 20px;
        background-color: #03fc41;
        cursor: pointer;
        font-size: 25px;
        font-weight: bold;
    }
    .contact-desc {
        text-align: center;
        font-size: 25px;
        padding: 0;
    }
    
    textarea {
        border: #03fc41 1px solid;
        background: var(--main-color);
        color: var(--bgc);
        font-size: 25px;
        margin: 10px;
    }
    textarea:focus {
        outline: none;
    }
    label {
        font-size: 30px;
    }
