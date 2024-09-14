# Front-End Developer Question 

## Task:
Using the PokeAPI, create a dynamic Pokémon dashboard that allows users to:

- Search for Pokémon by name or ID.
- Display Pokémon information dynamically, with an emphasis on handling and presenting the data effectively:
  - Display Pokémon name, stats, abilities, and sprite images.
  - Use charts or visual elements to represent the base stats (e.g., HP, Attack, Defense, Speed). (Optional)
- **Compare multiple Pokémon**: Allow users to search for and display two Pokémon at once, side-by-side, to compare their stats visually.
- **Fetch and display Pokémon abilities**: For each Pokémon, fetch additional details about their abilities. These are links found in the JSON response under the "abilities" key. Retrieve and display the ability name and effect.

## Requirements:

### Search and Compare:
- Provide two input fields, allowing users to search for two different Pokémon (by name or ID).
- Fetch data for both Pokémon from the PokeAPI and display them in side-by-side panels for comparison.
- Ensure the following details are displayed for each Pokémon:
  - Name
  - Abilities (fetch and display the ability details from linked URLs, including the ability name and effect).
  - Base stats (represented visually using charts or graphs).
  - Sprite image.


### Error Handling and UX:
- Handle errors gracefully if the user inputs an invalid Pokémon name/ID.
