---
title: Home
client_logos:
  - name: "OpenAI"
    logo: "/images/logos/openai.png"
  - name: "Anthropic"
    logo: "/images/logos/anthropic.png"
  - name: "Gemini"
    logo: "/images/logos/gemini.png"
  - name: "OpenRouter"
    logo: "/images/logos/openrouter.png"
  - name: "Ollama"
    logo: "/images/logos/ollama.png"
#testimonials:
#  - name: "John Smith"
#    title: "CTO at TechStartup"
#    avatar: "/images/testimonial-1.svg"
#    quote: "We built our SaaS website in record time. The performance is incredible, and our users love the modern, clean design."
#  - name: "Sarah Johnson"
#    title: "Founder at WebFlow"
#    avatar: "/images/testimonial-1.svg"
##    quote: "The combination of Hugo and TailwindCSS delivers lightning-fast performance. Our website loads instantly, which has significantly improved our conversion rates."
#  - name: "Michael Chen"
#    title: "Lead Developer at CloudTech"
#    avatar: "/images/testimonial-1.svg"
#    quote: "This theme made it easy to create a professional SaaS website. The build times are incredibly fast, and the code is clean and maintainable."
---

{{< hero 
    headline="Intelligence at Your Command"
    sub_headline="Crafting open intelligent solutions, one step at a time."
    primary_button_text="Get it on Google Play"
    primary_button_url="https://play.google.com/store/apps/details?id=org.verbli.chatforge"
    hero_image="/images/hero-dashboard.svg"
    gradient-from="#ffffff"
    gradient-to="#008080"
    gradient-angle="180"
>}}

{{< client-logos animate="true" >}}

{{< features-section 
    title="Advanced, Private, and Versatile AI Chat"
    description="Experience secure, local-first data storage, multi-provider AI integrations, and feature-rich conversations - all wrapped in one user-friendly platform."
>}}

{{< feature
    title="Privacy-First Architecture"
    description="Conversations stay local on your device, free from data logs. Minimal, anonymized analytics only - ensuring your messages remain private."
    badge="Privacy"
    badgeColor="#2563eb"
    image="/images/feature-1.svg"
    buttonText="Learn More"
    buttonLink="/features/privacy/"
    features="Local SQLite storage,Anonymized analytics,Fully open source - GNU GPLv3"
    imagePosition="right"
>}}

{{< feature
    title="Powerful AI Integrations"
    description="Effortlessly switch between multiple AI providers for cutting-edge LLM capabilities. Enjoy a flexible, future-proof chat experience with a broad range of model options."
    badge="Performance"
    badgeColor="#7c3aed"
    image="/images/feature-2.svg"
    buttonText="Learn More"
    buttonLink="/features/design-system/"
    features="Connect with leading AI providers,Effortlessly switch models on the fly,Smart context management keeps responses relevant,Local LLM support"
    imagePosition="left"
>}}

{{< feature
    title="Advanced Chat Features"
    description="Manage multiple conversations and edit messages on the fly. Take advantage of ephemeral chat sessions that self-delete when you're done."
    badge="UI/UX"
    badgeColor="#16a34a"
    image="/images/feature-3.svg"
    buttonText="Learn More"
    buttonLink="/features/developer-experience/"
    features="Multiple conversations,Edit and regenerate messages,Ephemeral chat mode"
    imagePosition="right"
>}}

{{< /features-section >}}

{{< testimonials 
    title="Connect to Leading AI Providers"
    description="Tap into the power of your favorite LLMs"
    animate="true"
    background-color="#f1f5f9"
>}}

{{< cta >}}
