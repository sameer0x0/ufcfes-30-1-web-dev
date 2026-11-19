# Brand identity and colour report

Prepared by Sameer Roy, UWE Bristol (UFCFES-30-1 Web Development)

## 1. Brief
An independent, multi-club Premier League ticket platform. Calm, premium, with heritage and classic character. Audience: fans buying tickets who want clear prices. The site must stay pure HTML and CSS, and seat selection and checkout are deferred.

## 2. Competitor observations (what was actually seen)
Ticketmaster UK (home page, 15 Nov 2026):
- A dense home page: a four-field search bar (location, dates, search), a mixed carousel of music, sport and theatre, then a long "happening this week" list across 20 events.
- Football is one entry in a Sport menu and a "Sports Guide", not the focus. No prices were visible on the home page.
- Blue and white, busy, promotional.

AXS UK: Busy Design, and Hard to find tickets and prices for someone not that tech inclined.

Opportunity: a football-only experience with prices visible on the fixture list, a quiet layout and no promotional clutter.

## 3. Name proposals
| Name | Why |
|---|---|
| **Turnstile** (working name, in use) | Matchday entry point, neutral, easy to say, (and I lack creativity so I was listening to a band with the same name ) |
| Terrace | Football heritage, warm |
| Kickoff Row | Seats and start of play | 
| Paddock | Classic, calm | 
| Matchday Ledger | Clarity of prices |

## 4. Logo (Due to lack of creativity AI was used)
- **Wordmark:** "Turnstile" set in Fraunces SemiBold, mixed case, slight positive tracking. Serif for heritage; soft optical contour for calm.
- **Monogram:** a cream "T" in a deep green circle. Doubles as favicon (`assets/favicon.svg`) and footer mark (inverted: green on cream).
- **Clear space:** one monogram diameter on all sides. Minimum size 24px.
- **Don'ts:** no football icons, no crest imitations, no gradients on the mark.

## 5. Colour palette (I am bad with colors so AI was used)
| Role | Name | Hex | Notes |
|---|---|---|---|
| Background | Cream | `#F6F1E4` | Page canvas |
| Surface | Paper | `#FBF8EF` | Cards |
| Primary | Pitch green | `#0F3B2A` | Hero, footer, monogram |
| Support | Turf | `#1D5A41` | Gradients, hover |
| Accent | Clay | `#AA5736` | Buttons, links, highlights |
| Accent dark | Brick | `#8D4428` | Hover, small accent text |
| Text | Ink | `#1B1F1C` | Body |
| Quiet text | Stone grey | `#5D645D` | Captions |
| Lines | Sand | `#E6DEC9` | Borders, badges |

Contrast (WCAG): ink on cream 14.8:1; cream on pitch green 11.1:1; stone grey on cream 5.4:1; brick on cream 5.3:1; white on clay 5.1:1. All meet AA for normal text. (The first clay choice, #B8613F, scored 4.36 and was darkened.)

Usage ratio: about 60% cream/paper, 25% pitch green, 10% ink, 5% clay. Clay is reserved for actions.

## 6. Typography 
- Display and headings: **Fraunces** (Google Fonts), 400 for headlines, 600 for the wordmark. Fallback Georgia.
- Body and UI: **DM Sans** 400/500/700. Fallback system sans.
- Scale: h1 clamp 2.4 to 5.2rem; h2 1.7 to 2.6rem; body 1rem/1.6.

## 7. Layout and UI principles
Borrowed from sereinwealth.com: full-bleed rounded hero, generous whitespace, pill buttons, quiet serif-led headings, rounded image panels, hamburger menu on small screens. Applied to ticketing: price on every fixture, plain categories, a visible "sample data" label, no popups.

## 8. Imagery and motion
Natural light, muted warm tones, no sponsor logos. One silent looping hero video with a poster image. Motion is limited to hover states and the easter egg; reduced-motion preferences are respected.

## 9. Voice
Plain, warm, specific. "One clear price", not "unbeatable deals". No urgency tricks.

## 10. Easter eggs
1. A tiny "7" in the footer opens a dark tribute page to the Manchester United number 7s (Best, Cantona, Beckham, Ronaldo). Typography only, no club marks.
2. On the Clubs page, the Manchester United card opens https://www.instagram.com/cristiano/ in a new tab. It is deliberately unmarked.
