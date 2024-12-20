---
title: 'Home'
date: 2024-10-11
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    id: principal
    content:
      title: Crie atividades educacionais fantásticas
      text: Questionários gerados automaticamente a partir de conteúdo multimodal (texto, audio ou vídeos)
      primary_action:
        text: Começe aqui
        url: solucao/
        icon: rocket-launch
      #secondary_action:
        #text: Read the docs
        #url: https://docs.hugoblox.com
      announcement:
        text: "Produzindo conhecimento juntos"
        #link:
          #text: "Read more"
          #url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: learnice_background.png
          filters:
            brightness: 0.5
  #- block: stats
    #content:
      #items:
        #- statistic: "1M+"
          #description: |
            #Websites built  
            #with Hugo Blox
        #- statistic: "10k+"
          #description: |
            #GitHub stars  
            #since 2016
        #- statistic: "3k+"
          #description: |
            #Discord community  
            #for support
    #design:
      # Section background color (CSS class)
      #css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      #spacing:
        #padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: solucao
    content:
      title: Nossa Solução
      text: Desenhada para aprimorar aprendizagem e avaliação
      items:
        - name: Geração Assistida
          icon: sparkles
          description: Auxilia na geração automática assistida de atividades avaliativas de qualidade.
        - name: Rápido
          icon: bolt
          description: Questionários criados a partir de um conteúdo chegam rapidamente no seu e-mail para serem compartilhados
        - name: Fácil
          icon: face-smile
          description: Você envia contéudo (por exemplo o link de um vídeo) através de um formulário simples para a geração das atividades
        - name: Engajamento
          icon: cursor-arrow-rays
          description: Desenvolve engajamento dos envolvidos e propicia avaliação periódica simplificada.
        - name: Prático
          icon: star
          description: Facilita e otimiza a rotina de professores e gestores.
        - name: Alunos Ativos
          icon: beaker
          description: Promove ambiente digital com estudantes ativos e protagonistas na aprendizagem!
  - block: cta-image-paragraph
    id: sobre
    content:
      items:
        - title: Impulsionamos o ensino e a aprendizagem com nossa tecnologia digital inteligente 
          text: Com poucos cliques é possível alcançar
          feature_icon: check
          features:
            - "Avaliação continua e de qualidade."
            - "Feedbacks automáticos e precisos de desempenho. "            
            - "Percepção e análise da aprendizagem."            
          # Upload image to `assets/media/` and reference the filename here
          image: imagem.png
          button:
            text: Quero Usar
            url: solucao/
        - title: Nossa Missão
          text: Criar experiências encantadoras de ensino e aprendizagem via tecnologias digitais com inteligência artificial generativa.
          feature_icon: bolt
          features:
            - "Impulsionar engajamento, autonomia e agilidade para professores e alunos."
            - "Aprimorar construção de conhecimento no digital."            
          # Upload image to `assets/media/` and reference the filename here
          image: imagem2.png
          #button:
            #text: Join Discord
            #url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"   
 # - block: buttons
  #  content:
   #   buttons:
    #    - title: Read my latest paper on LLMs
     #     icon: brands/arxiv
      #    url: https://arxiv.org/abs/2304.01852
      #  - title: Watch my new YouTube video to achieve 20x productivity
      #    icon: brands/youtube
      #    url: https://youtube.com
      #  - title: Connect with me on LinkedIn
      #    icon: brands/linkedin
      #    url: https://linkedin.com
  #- block: testimonials
    #content:
      #title: ""
      #text: ""
      #items:
        #- name: "Hugo Smith"
          #role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          #image: "testimonial-1.jpg"
          #text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
    #design:
      #spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        #padding: ["6rem", 0, 0, 0]
  #- block: cta-card
    #id: sobre
    #content:
      #title: Nossa missão é 
      #text: Abc
      #button:
        #text: Get Started
        #url: https://hugoblox.com/templates/
    #design:
      #card:
        # Card background color (CSS class)
        #css_class: "bg-primary-700"
        #css_style: ""         
---
