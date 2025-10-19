# Project Reflection – WeatherWise

## AI Tools Used  
For this project, I mainly used **ChatGPT** to help me when I got stuck or wasn’t sure how to approach a problem.  
It guided me through debugging and gave me explanations that helped me understand the logic behind Python functions, APIs, and visualisation.  
Instead of just copying answers, I tried to ask why things worked the way they did.  
For example, when deciding between using wttr.in or OpenWeatherMap, I discussed the pros and cons with ChatGPT and ended up choosing wttr.in because it was simpler and didn’t need an API key.  
This way, I could focus more on learning the actual Python logic.

---

## Prompting Techniques  
I used a few **intentional prompting** strategies that I learned in this unit:  
- Restating my problem before asking for help, so I could think clearly about what I was actually struggling with  
- Asking for reasoning or pseudocode first before asking for code  
- Testing edge cases like invalid cities or missing data to make sure my code didn’t break  
- Requesting small design improvements step by step instead of big chunks of code  

These techniques helped me use AI in a more independent way, where I still did most of the thinking and used it more like a tutor or partner.

---

## What Worked Well  
I’m really proud of how the final app turned out.  
Everything connects smoothly—from getting the weather data to showing visualisations and responding in natural language.  
I especially liked improving the precipitation chart by adding a “No rain expected” message, because it makes the result clearer for users.  
Switching to a **menu system with pyinputplus** also made the app easier to use and more reliable.  
Adding caching and comparing two cities was also a highlight since it made the project feel more complete and practical.

---

## What Would You Do Differently  
At one point, I tried using ipywidgets for the interface, but it kept giving me strange metadata errors in Colab.  
After asking ChatGPT why that happened, I learned it was because widgets store state in the notebook.  
I then switched to pyinputplus, which worked much better.  
If I had more time, I’d like to make a web version using Streamlit and maybe add more APIs or longer forecasts to make the system more advanced and user-friendly.

---

## Final Thoughts  
This project was a great learning experience.  
I feel like it brought together everything I learned this semester—APIs, data visualisation, natural language processing, and modular design.  
More than that, I learned how to use AI tools thoughtfully, not just for quick fixes but to actually understand what I’m doing.  
I realised that coding isn’t just about making things work, but also about designing something people can use and understand.  
Working with AI helped me learn faster, but the final design and logic still came from me, and that’s what I’m most proud of.


