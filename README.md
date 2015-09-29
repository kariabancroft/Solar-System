# Solar System Project
Let's make a planetary system!

## Baseline
- Create a `Planet` class with a name attribute. You should be able to instantiate a new `Planet` object with an associated name.

# Wave 1
## Primary Requirements
- Give your `Planet` class some additional properties like diameter, mass, number of moons, and any other properties you think a planet should have.
- You should be able to create many different planet objects with different properties, like Mercury, Venus, Earth, Mars, Jupiter, etc.

## Optional Enhancements
- Give each planet a rate of solar rotation
- Give each planet a `@distance_from_the_sun` attribute
- Write a _new_ program that asks for user input to query the planets using the `Planet` class you have created:
  - First, ask the user to select a planet they'd like to learn about.
  - Present the user with a list of planets from which they can choose. Something like:
    - `1. Mercury, 2. Venus, 3. Earth, 4. Secret Earth, 5. Mars, 6. Jupiter, ... 13. Exit`
  - Provide the user with well formatted information about the planet (diameter, mass, number of moons, primary export, etc.)
  - Then ask the user for another planet.


# Wave 2
## Primary Requirements
- Create a `SolarSystem` class that has an attribute `planets` that has zero to many `Planet` instances. To create the Planet associations, your `SolarSystem` should:
    - Have a method that adds a single planet to your solar system
    - Have a second method that adds an array of planets to the existing array of planets

## Optional Enhancements
- If you haven't already, add a `@distance_from_the_sun` attribute to your `Planet`. Using this data, add a method to your `SolarSystem` which will calculate the distance between any two planets provided (assuming planets are in a straight line from the sun)
- Give your solar system a formation year (in earth years).
- Define a method that returns the local year of the planet based on it's rotation since the beginning of the solar system
