---
widget: 'github.shoginn.pricing-cards'

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 1

# Title at the top of the Section
title: Our Prices

# Subtitle
subtitle: What do I get for that price?

# Maximum number of cards wide (Defaults to flex aka no number)

max_card_columns: 4

############################
# Block Configuration Items
############################

# Currency defaults to USD ($)

# Icon Packs Can be any of the icon packs supported by wowchemy 
# (Emoji, fas, fab, custom SVG, OR image)

# Pricing Cards Array (Each name creates a box)

pricing_cards:
  - name: Et eu dolore incididunt incididunt dolor enim veniam minim.
    description: Eu et ex laboris in commodo culpa veniam commodo commodo commodo dolore adipisicing.
    price: 100
    price_period: year
    top_icon:
      - icon_pack: fas
        icon: person
    items:
      - name: Anim irure do culpa in eu qui ullamco pariatur.
        icon_pack: emoji
        icon: ∞
    button:
      - icon_pack: fas
        icon: calendar-alt
        icon_label: Order Now
        url: /order

  - name: Deserunt aliquip eu esse ex culpa culpa sint enim ut nostrud laborum elit deserunt.
    description: Exercitation in est deserunt tempor labore aliqua.
    price: 10
    price_period: month
    top_icon:
      - icon_pack: custom
        icon: test-tube
        icon_css: width:100px;height:100px;
    items:
      - name: Veniam excepteur magna do occaecat excepteur ullamco sunt ut officia.
        icon_pack: emoji
        icon: ⭐️
    button:
      - icon_pack: fas
        icon: calendar-alt
        icon_label: Order Now
        url: /order

  - name: This card has a disabled hover effect, as well as the default horizontal rule!
    default_hr: true
    hover_disabled: true
    description: I also changed the size of the icon! See the font-awesome css ref
    price: 10
    price_period: day
    currency_symbol: €
    currency_suffix: true
    top_icon:
      - icon_pack: fas
        icon: person
        icon_css: fa-xl
    items:
      - name: Deserunt voluptate qui adipisicing consectetur ullamco ea anim commodo est consequat fugiat velit eiusmod eiusmod.
        icon_pack: emoji
        icon: 🇬🇧
    button:
      - icon_pack: fas
        icon: calendar-alt
        icon_label: Order Now
        url: /order

---

Content Below