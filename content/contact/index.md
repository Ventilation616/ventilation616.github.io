---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: 联系我们
      text: |-
        如果你闲着没事干想加群，请发送邮件给群主：
      email: 843762479@qq.com
      phone: 18079130240
      address:
        street: 安义中学
        city: 南昌市
        region: 江西省
        postcode: '330500'
        country: 中国
        country_code: CN
      directions: /tp InCl3
      office_hours:
        - 周一到周五下午五点之后
        - 周六到周日早上九点之后
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
