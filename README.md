# Oh Geez

**Feeds, flushes and supplies, sorted.**

Oh Geez is a free, open-source app for parents and caregivers of kids with feeding tubes. It turns the feeding plan from the GI team, dietitian and speech therapist into one simple daily view, and keeps track of the supplies you reorder from your medical supply company.

It started as a tool for one family's daughter with a G-tube and is shared so other families can use it too. It was inspired by Peter Yang's free `/fuck-cancer` caregiver brief.

## What it does

- **Today:** check off each tube feed (amount, time, what was in it, how it went), track water toward the daily goal, and see the percent of the planned volume, including when you go over.
- **Daily care:** site cleaning, creams and ointments, with limits like "max 3 a day" and editable times.
- **By mouth:** log purées, puffs, yogurt melts and other tastes in oz, tsp, tbsp or pieces.
- **History:** step back to earlier days to review or fill in anything that was missed.
- **Supplies:** counts that go down by the day, by logged feeds, or when you open a new container, plus a countdown that tells you when to reorder.
- **Order history:** keep packing slips on record.
- **Brief:** a one-page summary for appointments, with the plan, the last 7 days and plain-English terms. Copy it into a message or patient portal.

## Your data stays on your phone

Oh Geez has **no accounts, no server and no analytics.** Everything you enter is saved in your browser's storage on your own device. Nobody else can see it, including the people who make Oh Geez.

That also means nobody can recover it for you. Use **Plan > Your data > Save a backup file** now and then. A backup file can also be loaded on a partner's phone so you both start with the same records.

## Install it on your phone

1. Open the app in Safari (iPhone) or Chrome (Android).
2. iPhone: tap **Share**, then **Add to Home Screen**. Android: tap the menu, then **Install app**.
3. Open Oh Geez from your home screen from then on. On iPhone, the home screen app keeps its own storage, separate from Safari, so start logging there.

It works offline once it has been opened.

## Not medical advice

Oh Geez organizes what your care team prescribes. It never calculates or changes feed amounts, rates or textures. Always check changes with your child's care team.

## Run it yourself

It is a single `index.html` with no build step. Serve the folder with any static host, or open it locally with a small server:

```sh
npx serve .
```

The included `netlify.toml` deploys it to Netlify as is.

## Contributing

Ideas and fixes from tube-feeding families, clinicians and developers are welcome. Open an issue to describe what would help your family, or send a pull request.

## License

MIT
