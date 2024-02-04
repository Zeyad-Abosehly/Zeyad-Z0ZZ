<div>
    <style>
        body {
            font-family: 'Courier New', monospace;
            text-align: center;
            padding: 20px;
            background-color: #f0f0f0;
            color: #333;
        }
  
  <div id="sentence-container">
    <p id="sentence">Loading...</p>
  </div>
  
  <script>
    const sentences = [
      { text: "Hi 👋, I'm Zeyad Abosehly", style: "bold-blue:color: #007BFF;" },
      { text: "An IT student at SVU 3rd year", style: "bold-blue:color: #007BFF;"},
      { text: "I'am a problem solver", style: "bold-blue:color: #007BFF;"},
      { text: "Now, I'm interested in CTF",  style: "bold-blue:color: #007BFF;"}
    ];
    
    function displaySentence(index, charIndex) {
        const sentenceElement = document.getElementById('sentence');
        const currentSentence = sentences[index];
        
        if (charIndex <= currentSentence.text.length) {
          sentenceElement.textContent = currentSentence.text.slice(0, charIndex);
            setTimeout(() => displaySentence(index, charIndex + 1), 100); 
        } else {
            setTimeout(() => {
              sentenceElement.textContent = "Loading...";
              displaySentence((index + 1) % sentences.length, 0);
            }, 1000); 
        }
        
        sentenceElement.className = currentSentence.style;
    }

    displaySentence(0, 0);
  </script>
</div>


<h2 dir="auto"><a id="user-content--about-me" class="anchor" aria-hidden="true" tabindex="-1" href="#-about-me"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/140204239cd0dda1fd4200544361abdcb4c11a71d02d3d5322894e15a16c7338/68747470733a2f2f692e70696e696d672e636f6d2f6f726967696e616c732f33662f37652f34652f33663765346566663763393665396665346238623462316666336637626462352e676966"><img src="https://camo.githubusercontent.com/140204239cd0dda1fd4200544361abdcb4c11a71d02d3d5322894e15a16c7338/68747470733a2f2f692e70696e696d672e636f6d2f6f726967696e616c732f33662f37652f34652f33663765346566663763393665396665346238623462316666336637626462352e676966" width="6.5%" data-animated-image="" data-canonical-src="https://i.pinimg.com/originals/3f/7e/4e/3f7e4eff7c96e9fe4b8b4b1ff3f7bdb5.gif" style="max-width: 100%;"></a> About me</h2>

🔭 I’m study in SVU Fci Universty

🌱 I’m currently learning cybersecurty 

🤝 I’m Competitive Programmer in Codeforces & Leetcode

👯 I’m a mentor at SVU ACPC Community

## 🚀 Tracker
![Zeyad's GitHub stats](https://github-readme-stats.vercel.app/api?username=Zeyad-Z0ZZ&show_icons=true&theme=transparent)

## 🚀 Technologies

<p align="center">
  <a href="https://cplusplus.com/">
    <img src="https://skillicons.dev/icons?i=cpp" />
  </a>
  <a href="">
    <img src="https://skillicons.dev/icons?i=css" />
  </a>
  <a href="">
    <img src="https://skillicons.dev/icons?i=html" />
  </a>
  <a href="">
    <img src="https://skillicons.dev/icons?i=js" />
  </a>
  <a href="">
    <img src="https://skillicons.dev/icons?i=c" />
  </a>

</p>

</body>
