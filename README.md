# Pune Date Spots

Just some shit I made ( still working on it )

**Page Link:** `https://mihir-robotics.github.io/pune_date_ideas_webpage/`

## Features

✨ **Smart Search & Filter**
- Search by place name or area
- Filter by vibe (romantic, foodie, relaxing, cultural)
- Filter by budget (₹ to ₹₹₹)
- Filter by best time (morning, afternoon, evening, night)

💾 **Save Favorites**
- Heart icon to save spots you love
- Favorites persist in your browser's local storage
- Quick access to "Favorites" view

🌙 **Dark Mode**
- Toggle between light and dark themes
- Your theme preference is saved
- Beautiful design in both modes

📱 **Fully Responsive**
- Works seamlessly on desktop, tablet, and mobile
- Optimized touch targets for mobile devices
- Fast and lightweight

🗺️ **Detailed Information**
- View venue photos
- Quick info (area, budget, duration, tips)
- Google Maps embed for directions
- Links to Google Images for more photos

🎲 **Surprise Me**
- Get a random spot recommendation
- Great when you can't decide!


## Data

The app includes 29 curated date spots in Pune with (lemme know if you have any spots):
- Name, area, and description
- Category (romantic, foodie, relaxing, cultural)
- Budget range (₹ to ₹₹₹)
- Best times to visit
- Duration estimate*
- Tips and suggestions
- Photo links
- Google Maps integration

All data is hardcoded in the app—no backend required.

## Privacy

✅ **Your data stays private:**
- All filtering happens locally in your browser
- Favorites are stored only in your browser (localStorage)
- No data is sent to any server
- No tracking or analytics
- No external data requests except for images and maps

## Contributing

Found a great date spot? Want to add it?

1. Fork the repository
2. Edit `index.html` and add your spot to the `dateIdeas` array
3. Submit a pull request

### Spot Template

```javascript
{
    id: 30,
    name: "Spot Name",
    type: "romantic|foodie|relaxing|cultural|adventure",
    area: "Area Name",
    description: "One-line description",
    blurb: "2-3 sentence detailed description",
    budget: "₹|₹₹|₹₹₹",
    bestTime: ["morning", "evening"],
    duration: "1.5–2 hrs",
    tips: ["Tip 1", "Tip 2"],
    photos: ["https://image-url.jpg"]
}
```

## License

MIT License – feel free to use this project for your own dating app!

