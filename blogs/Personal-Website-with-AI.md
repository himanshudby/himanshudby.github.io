Writing blogs matters because the internet is about to drown in AI-generated content. The only real way to stand out is to write in your own voice first, then use AI only to clean it up. That’s the approach I’m taking, and it feels more authentic.

AI tools are everywhere now, and they make it easy to build things quickly. One model I’ve been exploring is Gemini, and the more I use it, the more useful it feels. I started experimenting with the Gemini 3.0 Pro model to build a personal website where I can share my research work and write about topics I enjoy. If you want to try the same, you’ll need access to a Gemini model through a corporate account or early access program, you can always purchase the subscription. The same can be very well achieved through chatgpt or your other favorite AI model.

The process begins at [https://aistudio.google.com/apps](https://aistudio.google.com/apps). Choose whichever model you have access to. Clear prompting matters, because the better you describe what you want, the closer the output matches what you pictured. I had a modern, clean design in mind, something similar to the iOS 16 liquid glass style but I began with a basic prompt: “Create a website to host my resume online.” Gemini generated a complete website and even showed a live preview.

![[Screenshot 2025-11-20 at 2.43.43 PM.png]]

After a few more prompts tuning the style and structure, the layout matched exactly what I wanted.

![[Pasted image 20251120144627.png]]

The next step was hosting. I wanted something free and maintenance-free. GitHub Pages turned out to be perfect. You can host a website there and use a **github.io** subdomain. If you prefer, you can connect your own custom domain later.

At first, Gemini produced files that required npm for deployment, but I wanted plain HTML and CSS so I could upload everything directly to GitHub Pages. After clarifying that, Gemini generated simple files that worked immediately.

I uploaded them to GitHub, waited a couple of minutes, and the site went live at:

**[https://himanshudby.github.io](https://himanshudby.github.io)**

One extra note: if you name your repository exactly like your desired domain, such as **himanshudby.github.io**, GitHub will host it at the root URL instead of a subfolder.
