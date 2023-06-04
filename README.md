### Greetings! My name is Suneet Tipirneni!

```hs
class Intro a where
  introduce :: a -> String

data Student = Student { name :: String, age :: Int, major :: String }

instance Intro Student where
  introduce a = "I'm " ++ name a ++ " and I'm " ++ show (age a) ++ " years old, and I am majoring in " ++ major a

me = Student "Suneet" 23 "Computer Vision"

main = do print $ introduce me
```

**``I'm Suneet and I'm 23 years old, and I am majoring in Computer Vision``**

#### Here's a little about me:

- 🔭 I’m currently working on any random thing that comes to mind.
- 👨‍💻 I'm interested in
  - AI/ML  
  - Functional programming
  - Rust
  - Haskell
  - Javascript/Typescript
- 🌱 I’m currently learning
  - Diffusion Models
  - Transformers

You can reach me via:
- [Discord](https://discordapp.com/users/386337006764032002)
- Email: suneet.tipirneni@knights.ucf.edu

### Checkout my blog

https://suneettipirneni.stream/blog

<!--
**suneettipirneni/suneettipirneni** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
  - Frontend Code + Desgin
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
