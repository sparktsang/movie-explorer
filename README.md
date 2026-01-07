# 🎬 Wikidata Movie Explorer

**"Cinema is a matter of what's in the frame and what's out."** — Martin Scorsese

But when it comes to *finding* great cinema, the search algorithms often leave too much out. They trap you in echo chambers of "Trending Now" and "Top 10," burying cinematic gems under layers of commercial noise.

**Wikidata Movie Explorer** is your lens to see the bigger picture.

It is a zero-tracking, ad-free, open-source tool that bypasses the algorithms and taps directly into the collective knowledge of humanity: **Wikidata**.

👉 **[Launch the Explorer](https://sparktsang.github.io/movie-explorer/)**

---

## 🌟 The Plot

Most movie databases are gated communities. You need an account, you see ads, and you only see what they want you to see.

This tool is different. It is a **SPARQL translator** disguised as a sleek, cinematic dashboard. It empowers you to perform complex data mining queries without writing a single line of code.

Want to find **Japanese Sci-Fi films from the 90s**?
Looking for **Body Horror movies with a 100% Rotten Tomatoes score**?
Curious about **French New Wave dramas**?

Just click, filter, and discover.

---

## 🎥 Features (The Director's Cut)

### 1. 🍅 Precision Filtering with Tomatometer
We don't just show you movies; we show you the *acclaimed* ones.
- **Smart Sorting:** Unlike basic lists, our engine weights the Tomatometer score against the number of reviews. A 100% score with 100 reviews will rightfully outrank a 100% score with only 5 reviews.
- **Deep Links:** One click takes you straight to the Rotten Tomatoes page or Wikipedia entry.

### 2. 🌍 A World of Cinema
Hollywood is not the only star. Our database covers the globe:
- **Countries:** From South Korea to France, India to Hong Kong.
- **Genres:** Over 30 specific genres including *Cyberpunk*, *Folk Horror*, *Wuxia*, and *Time-travel*.

### 3. 🛡️ Privacy & Performance
- **Zero Install:** Runs entirely in your browser.
- **Zero Tracking:** No cookies, no analytics, no creepy scripts.
- **Lightning Fast:** Powered by Wikidata's massive knowledge graph.

### 4. 💾 Take It With You
Found a curated list of obscure 80s slashers? Click **Export .XLSX** to download a spreadsheet complete with hyperlinks. Perfect for watchlists, research, or data hoarding.

---

## 🛠️ How It Works (Behind the Scenes)

When you click "Search," this tool performs a bit of magic. It dynamically constructs a **SPARQL query**—a specialized language for querying knowledge graphs—and sends it to the Wikidata Query Service.

It creates logic like this on the fly:
> *"Find me all entities that are instances of 'film', released between 2020 and 2024, originating from 'South Korea', classified as 'Horror', and—if available—fetch their Tomatometer score."*

It then cleans the messy data (deduplicating titles, normalizing dates, fixing genre names) and renders it into a beautiful, sortable table.

---

## 🤝 Fork This Repository

This project is open source and built with a single HTML file. It is as transparent as celluloid.

If you are a developer, a data nerd, or just a movie buff who knows a little HTML, **fork this repo**. Add your own filters (Cast? Directors? Awards?), tweak the UI, or just use it to build your own personal movie sanctuary.

**Cinema belongs to everyone. So should the data.**

---

*Directed by You. Powered by Wikidata.*
