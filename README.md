# ARIN121-Assignment3-TravelPlanner
# ARIN121 Assignment 3: Travel Planner

This is an AI travel planner built with a system prompt in Google AI Studio. It helps travellers plan trips and revise them, and it keeps track of their details through the conversation.

## What the planner can do
- Plans a day-by-day itinerary with morning, afternoon and evening activities for a destination and trip length.
- Asks follow-up questions about dates, departure location, budget and interests before planning.
- Groups nearby attractions on the same day to cut down on travel time.
- Asks which location the traveller means if a destination could be more than one place, like Kingston, Ontario or Kingston, Jamaica.
- Redirects questions that aren't about travel back to trip planning.

## Menu
If the traveller says something general like "Hi, I need help with my trip", the planner shows a menu with two options:
1. Plan a New Trip
2. Revise My Travel Plan

The traveller can pick by typing the number, the activity name, or by saying what they want in their own words, like "can we change my plan". If they ask for an activity clearly, the planner starts it right away without showing the menu. They can switch activities at any time, and the planner keeps the details they already gave, like the destination, trip length and budget.

## New activity: Revise My Travel Plan
This is a back and forth activity for changing an existing plan.
1. The traveller picks it from the menu, or asks to change their plan. If there is no plan yet, they can paste one in.
2. The planner asks what they want to change, like less walking or more indoor activities.
3. It suggests changes and updates the itinerary.
4. It asks whether the changes meet their needs and waits for an answer.
5. If they want more changes, it keeps going. When they say the plan works, it shows the final itinerary and a summary of what changed.

The traveller can stop or switch activities at any time.

## How to use it
Paste the contents of `system-prompt.md` into the System instructions in Google AI Studio, then start a chat. Try "Hi, I need some help with my trip" to see the menu.

## Files
- `system-prompt.md`: the full system prompt for the planner.
