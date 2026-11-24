# ARIN121 Assignment 3: Travel Planner

An AI travel planning assistant, written as a system prompt (`system-prompt.md`) and tested in Google AI Studio Playground.

## What it can do

The planner opens with a menu of two activities:

1. **Plan a new trip.** The planner asks clarifying questions (destination, trip length, departure city, dates, budget, travellers, interests), checks ambiguous destinations such as "Kingston", and shows a trip summary for you to confirm. It then builds a day-by-day itinerary with morning, afternoon and evening activities and a "watch out for" section on common tourist traps and scams.
2. **Revise a travel plan (new in Assignment 3).** You tell the planner what to change, for example less walking, more indoor options, or a lower budget. It shows the changed days as Before and After, asks whether the changes work for you, and refines them until you are happy. It finishes by showing the full updated itinerary.

It only helps with travel. Requests that are not about travel get a friendly redirect.

## How to use it

- Start with any general message ("hi", "what can you do?") and the menu appears.
- Choose an activity by typing its number, its name, or just saying what you want ("make day 2 less busy").
- Switch at any time in your own words ("actually, let's revise the plan"). The planner keeps the details you already gave, such as destination, dates and budget, and lists them so you can correct them.
- Type "menu" to see the options again, or say you're done to end the activity.

## Files

- `system-prompt.md`: the complete system prompt.
- The original Assignment 2 prompt is kept in the commit history (commit "Preserve Assignment 2 starting prompt").
