<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Best Friend Message</title>

<style>
    body {
        margin: 0;
        padding: 20px;
        background-color: #add8e6; /* Light Blue */
        font-family: 'Segoe UI', sans-serif;
    }

    .container {
        background: white;
        padding: 25px;
        border-radius: 15px;
        box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        max-width: 800px;
        margin: auto;
    }

    h1 {
        text-align: center;
        color: #0077b6;
        margin-top: 0;
    }

    p {
        font-family: 'Segoe Print', 'Bradley Hand', 'Comic Sans MS', cursive;
        font-size: 16px;
        line-height: 1.8;
        color: #333;
        white-space: pre-line;
    }

    .writing-word {
        display: inline-block;
        clip-path: inset(0 100% 0 0);
        animation: write-word 0.3s ease-out forwards;
        animation-delay: calc(var(--word-index) * 180ms);
    }

    @keyframes write-word {
        to { clip-path: inset(0 0 0 0); }
    }

    @media (prefers-reduced-motion: reduce) {
        .writing-word {
            animation: none;
            clip-path: none;
        }
    }
</style>

</head>
<body>

<div class="container">
    <h1>FOR MY BEST FRIEND 🫂💗</h1>

    <p>
Dear Bestieee ❤️🥹🫶🏻,

I honestly don't know where to start because no words will ever be enough to explain how much you mean to me. 🥺❤️ 
You are not just my best friend; you are my happiness, my comfort person, my secret keeper, my personal therapist, my partner in crime, and one of the most beautiful parts of my life. 🫂💗 
I feel so lucky to have someone like you because finding a person who understands you without explaining everything, who notices when something is wrong even when you say you're fine, and who stays beside you even when you're not at your best is truly a blessing. 🧿❤️ 
You have become such an important part of my life that I honestly cannot imagine my days without our conversations, our stupid jokes, our random talks, our endless gossip, our laughter over the smallest things, and even our little arguments. 😂😭💞 
Sometimes we talk about the most serious things, and sometimes we laugh at things that don't even make sense, but that's what makes our friendship so special. Every little moment with you becomes a memory that I want to keep forever. 🥹💕 
Thank you for listening to my nonsense, tolerating my mood swings, understanding my silence, supporting me when I feel low, and making even my worst days a little better. 🫶🏻❤️ 
Thank you for being someone I can talk to without being scared of being judged, someone I can be completely myself around, and someone who makes me feel that I don't have to pretend to be okay all the time. 🫂💖 
You have seen different sides of me, my happy side, my emotional side, my overthinking side, my angry side, and my childish side, yet you continue to be here, and that means more to me than you could ever imagine. 🥺💗 
I know I'm not always the perfect friend. Sometimes I may act weird, get irritated over small things, overthink situations, or fail to express how much I care about you, but please always remember that my love and respect for you will never depend on a single argument or misunderstanding. ❤️‍🩹🫶🏻 
If we ever fight, I hope we always choose to understand each other instead of giving up on our friendship. I hope we never allow our egos, misunderstandings, distance, or other people to destroy something so precious that we have built together. 🧿💞 
I want us to stay friends through every phase of life, through our happiest days and our hardest nights, through our successes, failures, changes, and new beginnings. I want to see you achieve every dream you've ever had, become the person you want to be, and experience all the happiness this world has to offer. 🥹❤️ 
And whenever life gets difficult, I hope you remember that you don't have to face everything alone because you will always have someone who genuinely cares about you and wants to see you happy. 🫂💗 
I want to celebrate your smallest achievements as if they were my own, encourage you when you doubt yourself, remind you of your worth when you forget it, and stand beside you when the whole world feels against you. You deserve a friendship where you feel loved, respected, appreciated, and safe, and I hope I can always give you that feeling. 💖✨ 
I wish I could freeze some of our moments forever because sometimes the simplest memories become the most precious ones. One day, we'll look back at all our crazy conversations, silly pictures, embarrassing moments, late-night talks, and all the things we thought were ordinary, and we'll realize that those were some of the best days of our lives. 🥹📸💗 
I hope that even when we grow older, become busy with our careers, meet new people, and get caught up in our own lives, we never become strangers to each other. I hope we still call each other for the smallest reasons, share every little update, laugh at our old jokes, and remember how our friendship started. 🫶🏻❤️ 
I want a friendship that lasts beyond school, college, work, distance, and time. I want us to be those best friends who can go months without meeting but still feel the same connection the moment we talk again. 🧿💞 
No matter how many people enter our lives, you will always have a special place in my heart that nobody else can replace. You are one of those people who have made my life brighter simply by being in it, and I hope you know how incredibly precious you are to me. 🥺💗 
If I could give you one thing in life, it would be the ability to see yourself through my eyes, because then you would understand how amazing, lovable, strong, and special you truly are. ❤️✨ 
Never think that you are alone, never think that you are not enough, and never forget that there is someone who is genuinely grateful that you exist. 🫂💖 
Thank you for being YOU, for coming into my life, for creating memories with me, and for giving me a friendship that I will always treasure. I may not say it every day, but I appreciate you more than you know, and I am genuinely thankful for every moment we have shared. 🥹❤️ 
If life gave me the chance to choose my best friend all over again, I would still choose you, with all your craziness, your flaws, your beautiful heart, and everything that makes you who you are. 💗🫶🏻 
You are not just a chapter in my story; you are one of the people who make my story worth remembering. 🥹📖❤️ 
I hope our friendship keeps growing stronger, our bond keeps getting deeper, and our memories keep getting crazier. 😂💞 
No matter what happens tomorrow or where life takes us, please always remember that you are important to me, you are appreciated, and you will always be my bestie. 🫂🧿❤️ 
I love you more than these words can explain, bestieee! Thank you for being my favourite human, my safe place, my unpaid therapist, my partner in crime, and my forever kind of friend. 😭💗🫶🏻 
Best friends today, tomorrow, and hopefully until we're old, wrinkly, and still gossiping about absolutely everything. 😂👵🏻👵🏻💖 
Forever us, forever this friendship, and forever grateful for you. ❤️🧿♾️✨
    </p>
</div>

<script>
    const message = document.querySelector('.container p');
    let wordIndex = 0;
    const parts = message.textContent.split(/(\s+)/);

    message.replaceChildren(...parts.map((part) => {
        if (!part.trim()) return document.createTextNode(part);

        const word = document.createElement('span');
        word.className = 'writing-word';
        word.style.setProperty('--word-index', wordIndex++);
        word.textContent = part;
        return word;
    }));
</script>

</body>
</html>
