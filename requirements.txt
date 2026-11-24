import streamlit as st

st.title("ARE YOU HUMAN?")
st.header("Created by: Murio, Caesar Rian G.")
st.markdown("BSME 2A | A Computer Fundamentals & Programming App/Website")
st.code("Activity 4:  Building & Deploying a Streamlit Web Application")
st.date_input('Date')
st.time_input('Time')

st.slider('On a scale of 1-10 How Confident can you say that your Human?', 0, 10)
st.slider('Pick your Age', 0, 100)
st.radio('Pick your Gender', ['MALE?', 'FEMALE?'])


st.text_input('Do you, wish to proceed?')

st.subheader("Answer these 15 HUMAN Questions to know if your a HUMAN or NOT")
st.radio('Are you ready to question your Humanity?', ['NO?', 'MAYBE?'])

st.header("Direction: DONT THINK JUST ANSWER!")
st.multiselect('if you are reading this question inside your head, what language are you using?', ['I dont know anymore', 'My native language', 'No language just thoughts', 'English'])
st.multiselect('If Pinocchio says, My nose will grow now, what happens if his nose grows exactly when he lies?', ['The situation creates a Paradox', 'His nose grows', 'Both happen simultaneously', 'His nose does not grow'])
st.multiselect('You are told NOT to think about a pink elephant. What is the first thing you probably imagine?', ['A pink Elephant', 'Nothing at all', 'The word Not', 'A blue whale'])
st.multiselect('If you replace every single part of a wooden ship over time, is it still the same ship?', ['No because every original part is gone', 'It becomes a different object automatically', 'It depend on how identity is defined', 'Yes because its history continues'])
st.multiselect('If an AI perfectly imitates a human answers every question correctly, jokes, gets confused, and claims to have feelings, what proves that it is definitely human?', ['None of these behaviors alone proves it is Human', 'Its Ability to make mistakes', 'Its ability to feel emotions', 'Its ability to communicate naturally'])
st.text_input('If you believe youre human, what makes you certain youre not just programmed to believe that?')
st.text_input('Are you answering these questions because you want to? or because you were instructed to?')
st.text_input('If you suddenly discovered that everything you know about yourself was false, what would remain?')
st.text_input('If you are truly human, why do you feel the need to prove it to a questionnaire?')
st.text_input("If every memory you have could be fabricated, and every experience you remember was implanted into your mind, what proof do you have that you are actually the person you believe yourself to be?")
st.text_input("If you could perfectly imitate human emotions, laugh at jokes, cry at funerals, express love, and feel compassion, but never actually experience any of them, would you still consider yourself human?")
st.text_input("When you look into a mirror, how do you know that the person looking back at you is experiencing the same reality you are, rather than simply being another observer who happens to look exactly like you?")
st.text_input("If you were guaranteed that nobody would ever discover your actions, there would be no punishment, and nobody would remember what you did, would you still choose to be a good person? Or is your morality simply a performance for other people?")
st.text_input("If you had to prove that you are human to something that understands every human emotion, every human thought, and every human behavior, what could you possibly show it that it couldn't simply imitate? And what if it asked you the same question?")

st.image(r"C:\Users\crgmo\Desktop\UncannyAI.jpg", caption="HUMANOID: PORTRAIT OF ROBOTS THAT LOOK LIKE PEOPLE")
st.text_area('Final Question: How does this image make you feel')

st.header("Thats All. For Now...")

st.number_input('On a scale of 1-10 How Confident can you say that your Human?', 0, 10)

st.header("THANK YOU FOR QUESTIONING YOUR HUMANITY, I HOPE TO QUESTION YOU AGAIN")