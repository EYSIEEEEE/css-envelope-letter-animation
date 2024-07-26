<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Envelope + Letter (Open/Close on Click)</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <div class="container">
        <div class="envelope-wrapper">
            <div class="envelope">
                <div class="letter">
                    <div class="text">
                        <strong>Dear Langga</strong>
                        <p>
                            I know you’re aware of my feelings because I admit them every day HAHAHHAHAHA,
                            but I just want to remind you again. You bring so much joy to my life without even realizing it.Your presence means more to me than words can express,
                            and I’m incredibly grateful to have you in my life.I thank the Lord every day for giving me the chance to know and care about you
                            There are no words that can fully define nor express how much you mean to me and how much you brighten my life.

                            I apologize that this is all I can offer right now, 
                            just a simple digital letter but i know you how appreciative you are, so never akong mapapagod gumawa ng mga bagay na ganto even if it might seem a bit cringey. 

                            I really, really admire you. Good luck with your classes and activities. I know you can handle it, and if you ever need help, I’m always here.

                            FIGHTING LANGGAAAAA!!
                        </p>
                    </div>
                </div>
            </div>
            <div class="heart"></div>
        </div>
    </div>
    <script>
        const envelope = document.querySelector('.envelope-wrapper');
        envelope.addEventListener('click', () => {
            envelope.classList.toggle('flap');
        });
    </script>
</body>
</html>
