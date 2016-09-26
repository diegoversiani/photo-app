# Project Manager SaaS

This is the SaaS Project App from the Complete Ruby on Rails Developer course

# Functionalities

- Plans
  - The user can opt to free or premium plan
  - For both plans the user has to pay an amount via credit card (Stripe Payment Gateway)
    - Premium $10
    - Amaze $20
- Authentication system
  - users can sign-up
  - log in / log out
- Images
  - Users can upload images
  - Images are processed and save with maximum 300x300 px

# Model Associations

```
User **one_to_many** Image
User **one_to_one** Payment
```

# Technologies

- Ruby 2.2.3
- Rails 4.2.6
- Devise 3.5.10
- Twitter Bootstrap (gem)
- Twitter Bootstrap for Devise (gem)
- Stripe Payment Gateway (gem)
- CarrierWave (gem)
- MiniMagick (gem)
- Fog (gem)

# Demo

Running demo at: https://saas-project-app-diegoversiani.herokuapp.com/
