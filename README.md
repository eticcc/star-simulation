## Inspiration
We met in a physics class in high school and got closer through TAing together, so a physics application felt like a natural choice. We both love star gazing and staring at the night sky, so we wanted to create an aesthetic model of a physical system.

## What it does
In our game, users will first choose whether they want to use our presets or create any number of their own stars by initializing the star’s position, mass, and directional velocity. After the user is finished adding, the stars will start moving, following gravitational forces to orbit or crash into each other. If two stars crash, or if a star exits the bounds of the screen, they will disappear. Once all the stars are gone, the game will end.

## How we built it
We used pygame to program this game. To start off, Caroline programmed the technical calculations while Kate focused on the visualizations. After initial work was completed, we worked together to debug and implement additional features for functionality.

## Challenges we ran into
When two massive objects get very close to each other, they accelerate extremely quickly. Initially, when stars got too close, they would zoom through each other and off into the abyss. We made adjustments so that stars occupying the same space would “splat,” simulating a kilanova. In addition, pygame seemed to be lacking some of the features we needed for our game, such as taking user input and storing it into a variable. To bypass this, we needed to append each individual keyboard press into a string that we then converted to integers.

## Accomplishments that we're proud of
Neither of us have ever completed a hackathon project, so we weren’t initially sure our idea is feasible. We’re both extremely proud of each other for not just making a product that works, but one that is aesthetically appealing and useful.

## What we learned
In our programming classwork, we work on many projects, but we always have detailed and clear instructions. With this project, we got to follow an idea from conception to implementation, gaining technical knowledge along the way.

## What's next for Starry Night Physics
As is, our program doesn’t put limits on travel speed. With more time, we would apply principles of relativity to ensure no object accelerates past the speed of light. In addition, in the future, we could work more on dealing with improper user inputs.
