# AlgoMaths Exercises

## How to add a new exercise?

1. Copy an id from here, this will be the id of the exercise:

    https://www.epochconverter.com/hex

2. If the exercise has only one topic, add a `{id}.md` file to the corresponding topic folder.

    If the exercise has multiple topics, add a `{id}.md` file to the `multi_topic` folder.

    This markdown file should have the following structure:

    ```
    <!-- 
        Topics: [geometry, applied, something]
        Difficulty: [7, 8, 9]
        Source: Leaving Cert 2023 Paper 1 Higher Level
    -->

    <!-- Question -->

    How many 0.5cm slices can you cut from a bread that is 25cm long?

    ![](123ABCDEF.png)

    <!-- Choices -->

    1. 50 <!-- Correct -->
    2. 25
    3. 100
    4. 12.5

    <!-- Solution -->

    To find the number of slices, we divide the length of the bread by the thickness of each slice.

    $$\frac{25}{0.5}=50$$

    Therefore, you can cut 50 slices from the bread.
    ```

3. Images can be added to the same folder, name them `{id}.png`.

    If there are multiple images for the same exercise, use this format: `{id}_1.png`, `{id}_2.png`, etc.

    An image named `123ABCDEF.png` can be referenced in the markdown file like this:
    
    `![](123ABCDEF.png)`

4. If you want, add an image of the original exercise as well, name it `{id}_original.png`.