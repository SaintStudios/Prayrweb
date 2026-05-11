# Prayr Brand Design Guide

  ## Brand Basics

  **Product name:** Prayr
  **Internal app/bundle:** `com.praytowin.app`
  **Category:** Christian prayer habit + Screen Time app blocker
  **Core promise:** Pray first. Scroll later.
  **Audience:** Christians who want to reduce distracting screen time and build a daily prayer habit.

  Prayr should feel warm, calm, spiritual, premium, and intentional. It is not a productivity app with religious decoration. It
  is a prayer-first experience that uses app blocking as accountability.

  ## Brand Positioning

  Prayr helps users put God before their phone by blocking distracting apps until they complete a short prayer. The app combines
  Screen Time blocking, personalized prayer, Bible verses, streaks, and gentle reflection.

  Primary emotional qualities:

  - Peaceful
  - Convicting but not harsh
  - Warm and intimate
  - Spiritually grounded
  - Simple and focused
  - Premium but humble

  Avoid:

  - Loud startup/SaaS styling
  - Cold corporate blue
  - Overly childish religious visuals
  - Generic stock photos
  - Heavy gradients everywhere
  - Aggressive productivity language

  ## Color Palette

  ### Light Mode

  | Token | Hex | Use |
  |---|---:|---|
  | Manifest Black | `#0F1110` | Primary text, primary buttons |
  | Morning Cream | `#FFF5EA` | Main background |
  | Apricot | `#FFD2A6` | Soft accent, highlights |
  | Apricot Dark | `#E6B88A` | Secondary accent |
  | Growth Green | `#3D5C35` | Success, streaks, completed prayer |
  | Clay Terra | `#D97C56` | Main warm accent, emphasized words |
  | Mist Lavender | `#E6E1F0` | Soft secondary background/accent |
  | Golden Hour | `#EBC25E` | Notifications, milestones, warmth |
  | Burnt Red | `#BF3F3F` | Danger, warnings, emergency unlock |

  ### Dark Mode

  | Token | Hex | Use |
  |---|---:|---|
  | Dark Background | `#1C1C1B` | Main dark background |
  | Dark Surface | `#2A2A28` | Cards/panels |
  | Dark Text | `#F2EFE9` | Primary dark text |
  | Dark Apricot | `#C98B5E` | Dark mode accent |

  ## Typography

  Use Apple system fonts.

  ### Headings

  Use **serif system font** for emotional, prayerful, reflective moments.

  Examples:
  - Page titles
  - Prayer text
  - Onboarding questions
  - Hero headline

  Recommended CSS equivalent:

  ```css
  font-family: ui-serif, Georgia, "Times New Roman", serif;
  font-weight: 700;

  ### Body

  Use system sans-serif for clarity.

  font-family: -apple-system, BlinkMacSystemFont, "SF Pro Text", "Inter", sans-serif;

  ### Type Scale

  | Role | Size | Weight |
  |---|---:|---|
  | Hero title | 40-56px desktop, 32-38px mobile | 700 serif |
  | Page title | 28-36px | 700 serif |
  | Section title | 20-24px | 600 serif |
  | Body | 16-18px | 400 |
  | Small label | 12-14px | 600, uppercase optional |
  | Button | 16-18px | 600 |

  ## Layout Style

  Use a mobile-first layout because the product is an iOS app.

  Preferred layout:

  - Warm cream background
  - Large calm whitespace
  - Rounded but not overly playful cards
  - Soft shadows
  - Content max width around 720px for policy/support pages
  - Wider max width around 1120px for landing/brand pages
  - Cards radius: 24px
  - Inputs radius: 12px
  - Buttons: full pill radius

  Spacing scale:

  | Token | Value |
  |---|---:|
  | XS | 4px |
  | SM | 8px |
  | MD | 16px |
  | LG | 24px |
  | XL | 32px |
  | XXL | 64px |

  ## Buttons

  Primary button:

  - Background: #0F1110
  - Text: #FFF5EA
  - Border radius: 999px
  - Padding: 14px 32px
  - Font weight: 600

  Accent button:

  - Background: #D97C56
  - Text: white
  - Border radius: 999px

  Secondary button:

  - Translucent/soft material look
  - Dark text
  - Minimal border

  ## Logo And Assets

  Use the existing app logo from the iOS project:

  - PrayLockApp/Assets.xcassets/AppLogo.imageset/PTW.png
  - PrayLockApp/Assets.xcassets/AppIcon.appiconset/PTW.png
  - Shield extension logo: PTWShieldConfiguration/PTWLogo.png

  The logo should be shown clearly on support/privacy pages, preferably at the top left or centered above the page title.

  ## Imagery

  Use real app screenshots, app icon, and simple product UI previews.

  Good imagery:

  - iPhone mockups showing blocked app flow
  - Prayer screen
  - Streak screen
  - Screen Time app selection
  - Warm light backgrounds
  - Soft Christian visual cues

  Avoid:

  - Generic praying hands stock images
  - Dark dramatic church photos
  - Random crosses everywhere
  - Overly dramatic spiritual imagery
  - Neon gradients

  ## Voice And Copy

  Tone should be direct, warm, and spiritually grounded.

  Use:

  - “Pray first. Scroll later.”
  - “Build a daily prayer habit.”
  - “Block distracting apps until you pray.”
  - “Start with God, not the world.”
  - “Your prayer history stays private on your device.”

  Avoid:

  - “Hack your dopamine”
  - “Beat addiction fast”
  - “Guaranteed spiritual growth”
  - Overpromising results
  - Medical/mental health claims

  ## Website Pages

  ### Support Page

  Design should be practical and easy to scan.

  Sections:

  1. Header with Prayr logo
  2. “How can we help?”
  3. Contact support email
  4. Quick help topics
  5. App blocking FAQ
  6. Subscriptions and purchases
  7. Privacy/data link
  8. Legal contact details

  ### Privacy Page

  Design should be plain, trustworthy, and readable.

  Sections:

  1. Effective date
  2. Who we are
  3. What data stays on device
  4. What data may be sent to services
  5. Apple Screen Time permissions
  6. Notifications
  7. AI prayer generation
  8. Subscriptions and Superwall
  9. Children/minors note
  10. User choices and deletion
  11. Contact

  Privacy page should avoid marketing language. Keep it clear and factual.


  And here’s the matching brand info block:

  ```md
  # Prayr Brand Info

  ## One-Liner

  Prayr blocks distracting apps until you pray, helping Christians put God before their phone.

  ## Short Description

  Prayr is a Christian prayer habit app that uses Apple Screen Time to block selected apps, categories, and websites. Users
  complete a short prayer or reflection to unlock distractions and build a daily rhythm of prayer.

  ## Longer Description

  Prayr helps users trade mindless scrolling for intentional prayer. During onboarding, users share simple spiritual and habit
  context, then Prayr creates a personalized prayer experience. The app can block distracting apps through Apple Screen Time,
  guide users through prayer, show Bible verses, track prayer history, and build streaks over time.

  ## Key Features

  - Block selected apps, categories, and websites
  - Unlock apps after completing prayer
  - Personalized AI-generated Christian prayers
  - Bible verse prompts
  - Mood and connection check-ins
  - Prayer history and streaks
  - Daily reset for app blocking
  - Emergency unlock
  - Local notifications
  - English and German support
  - Subscription/paywall support

  ## Core Audience

  Christians who want to:
  - Spend less time scrolling
  - Build a consistent prayer habit
  - Put God first in the morning
  - Replace distraction with reflection
  - Use stronger accountability than reminders alone

  ## Brand Taglines

  - Pray first. Scroll later.
  - Start with God, not your phone.
  - Block distraction. Build devotion.
  - Turn screen time into prayer time.
  - Put Him before the scroll.

  ## Product Values

  - Prayer before distraction
  - Privacy and trust
  - Gentle accountability
  - Spiritual consistency
  - Simplicity
  - Warmth
  - Honesty

  ## Contact Placeholders

  Support email: `support@theprayr.com`
  Website: `https://theprayr.com`
  Support URL: `https://theprayr.com/support`
  Privacy URL: `https://theprayr.com/privacy`
  German privacy URL: `https://theprayr.com/de/datenschutz`
