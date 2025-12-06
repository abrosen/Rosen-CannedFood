# Rosen-CannedFood
Adding more canned food to the canner from [Vanilla Cooking Expanded](https://github.com/Vanilla-Expanded/VanillaCookingExpanded)

## Original 

[Original code ~blatantly stolen~ used with permission](https://steamcommunity.com/sharedfiles/filedetails/?id=2947358933)


# Objectives and Brainstorming

Objectives in order.

## Canned Meals

- Canned Simple Meals (CSM) should take a in a simple meal and output a canned meal.
  - Original code took .6 nutrition to output a canned meal, on par with Packaged Survival Meal (PSM).
  - To me, it makes sense to cook a meal and can it. 
- Balance Considerations
  - Two stage vs One stage with two seperate production benches.
    - This is fine.
  - This is more nutritionally efficient than a Packaged Survival Meal (PSM).
    - This can easily be remidied by making CSM less nutritious than a simple meal.  0.8 would be nutrition parity, 0.7 would be worse, 0.6 would be 1 to 1 with raw.
    - [Eoral Milk's canned food](https://steamcommunity.com/sharedfiles/filedetails/?id=3240910602)  production chain gets three 0.6 canned meals produced from two input 0.9 meals.
  - We don't know if you can get food poisoning.
 
  - Canned Fine meals?  Why not, but they should not be as good as a fine meal.
  - Canned Lavish meal?  Sounds funny; maybe after fabrication and uses plasteel? 

## Make Canned "RAW" Food Less appealing
  - Current testing seems that canned ingredients do not count as raw food.
    - Eat a raw can of beans and tell me whether you get a negative moodlet or not.
  - Current thoughts about thoughts:
    - -4 Ate uncooked canned ingredient
    - -2 Ate canned simple meal
    - +2 Ate canned fine meal
    - -6 Ate canned nutrient paste meal
      - "Why would someone make this?  I'd rather eat cooked bugs!"
    - VCE has a ate canned food thought.  We can override that and set that to -2
