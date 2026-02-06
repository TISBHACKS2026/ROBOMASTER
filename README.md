# Earn Your Scroll - Browser Extension

## Problem
Students are nowadays too adicted to their gadgets, instead of studying they are always on their phone. The traditional parental controls are too rigid which makes the students despise studying even more.

## Solution
Gamified extension/app that restricts access to addictive sites( such as YouTube, Instagram, TikTok, Reddit, Facebook), the user gets to visit the restircted website only when they answer correctly answer the question shown on the flashcard. Correct answers unlock 60 seconds of guilt-free browsing.

## How It Works
1. User tries accessing restricted site
2. Full-screen flashcard quiz appears on their screen
3. Answer the flashcard to get access to the restricted site
4. ✅ Correct → 60-second browsing access granted + stats increment
5. ❌ Wrong → Answers shuffle, try again
6. After 60 seconds, next access requires new quiz

## Key Features
- **Smart Blocking** - Pre-set sites (YouTube, Instagram, TikTok, Reddit, Facebook)
- **Custom Sites** - Add/remove domains as needed
- **Educational Component** - Random flashcard questions from curated database
- **Progress Tracking** - Lifetime statistics dashboard
- **Non-dismissible** - Full-screen mode prevents cheating

## For Adults
✅ Boost work productivity - Eliminate Reddit/YouTube time-waste
✅ Guilt-free breaks - Earned browsing feels deserved
✅ Continuous learning - 50+ questions, 70-100 facts/week
✅ Mental health - Reduced anxiety, better focus
✅ Models behavior - Teach children healthy habits

## For Children & Teens
✅ Homework support - Parents gate breaks behind learning
✅ Screen time control - Gentle enforcement vs. harsh blocking
✅ Digital literacy - Teaches consequences and rewards
✅ Parental customization - Add curriculum-relevant questions

## Advantages
- **Lightweight** - 50KB, minimal RAM
- **Privacy-First** - All data local, no cloud sync
- **Customizable** - Block only the sites you want
- **Gamified** - Makes restriction feel rewarding
- **Cross-Platform** - Edge and Chrome
- **Access** - Very easy to access and user-friendly

## Technical Details
- **Storage**: Chrome storage API (restricted sites, custom sites, stats, bypass timer)
- **Injection**: Content script monitors domain, injects overlay on restricted sites
- **Communication**: Service worker manages inter-process messages
- **Architecture**: Local-first, zero-server dependency

## Installation
1. Download repository
2. Open `edge://extensions/`
3. Enable Developer Mode (toggle top-right)
4. Click "Load unpacked" → Select folder
5. Extension appears immediately in toolbar

## Future Roadmap
- Spaced repetition algorithm
- Difficulty levels (Easy/Medium/Hard)
- Category-based questions (Math, Science, History, etc.)
- Parents can set what their ward has to learn
- Leaderboard & achievements
- Analytics (session history, focus insights)
- Multi-language support
- Mobile sync

## Real Impact ##
Students want to spend more time on social media while parents want them to study, our solution satisfies both their requests (a win-win situation).

## Our progrees ##
Day 1 - Started discussing ideas
Day 2- Fixed on the idea and started barinstorming ways to make the extension
Day 3 - Started coding
Day 4 - Got access to GitHub and started pushing our code to GitHub
day 5 - Coming soon

**Status**: Active Development | **License**: MIT | **Version**: 1.0
