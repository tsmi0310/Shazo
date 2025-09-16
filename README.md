@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');

body {
    background-color: #f7d2e7;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
    font-family: 'Poppins', sans-serif;
    text-align: center;
    color: #4b4b4b;
    overflow: hidden;
    position: relative;
}

.container {
    background: white;
    padding: 30px;
    border-radius: 20px;
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
    max-width: 90%;
    width: 400px;
    box-sizing: border-box;
    animation: fadeIn 1.5s ease-in-out;
}

.kitty-container {
    width: 150px;
    height: 150px;
    margin: 0 auto 20px;
}

.kitty-gif {
    width: 100%;
    border-radius: 50%;
    border: 5px solid #ff99c4;
    animation: pulse 2s infinite;
}

h1 {
    font-size: 1.8em;
    color: #ff66a3;
    margin-bottom: 20px;
}

.quiz-container {
    margin-top: 20px;
}

#question-box {
    font-size: 1.2em;
    margin-bottom: 20px;
    min-height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.options-box {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.option-btn {
    background-color: #ff99c4;
    color: white;
    border: none;
    padding: 12px 20px;
    font-size: 1em;
    border-radius: 50px;
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.2s ease;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.option-btn:hover {
    background-color: #ff66a3;
    transform: translateY(-2px);
}

.option-btn:active {
    transform: translateY(0);
}

.hidden {
    display: none;
}

.final-message {
    font-size: 1.5em;
    color: #ff66a3;
    animation: popUp 0.8s ease-out;
}

/* Animations */
@keyframes fadeIn {
    from {
        opacity: 0;
        transform: scale(0.9);
    }
    to {
        opacity: 1;
        transform: scale(1);
    }
}

@keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.05); }
    100% { transform: scale(1); }
}

@keyframes popUp {
    0% { transform: scale(0.5); opacity: 0; }
    80% { transform: scale(1.1); opacity: 1; }
    100% { transform: scale(1); }
}# Shazo
