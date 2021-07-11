# Lists in Markdown

    Unordered Lists:

        * <ITEM>
        - <ITEM>
        + <ITEM>

    Ordered Lists:

        <NUMBER> .
        <NUMBER> .
        <NUMBER> .

    Note:  
            1. Just use any Non-Incremental Number. And the parser will take care of Numbering. Just try not to mess the parser with Incremental Number if you can do it right.

            2. And, The <Number> . on the first item will determine from What number should the numbering Start. 
                Example: 
                        0. <ITEM_1>
                        0. <ITEM_2>  will make the parser start numbering from '0'.

## Unordered Lists:

* Bread
- Butter
+ Jam

## Ordered Lists:

1. Cat
1. Dog
1. Hamster

## Nested Lists and Indentations:

1. Foods
    1. Break Fast
        * Bread
        * Butter
        * Jam
    1. Lunch
        1. Rice and Curry
        1. Roti and Dal
1. Pets
    * Cat Family
        * Lion
        * Cheetah
        * Siberian Cat

    1. Dog Family
        1. Vodafone Dog
        1. Golden Retriever
    
    * Hamster

1. Paragraphs, Images inside Lists:

    1. This is an Item Containing Paragraph: 
        
        This is a Paragraph. Leave a Line and Type. You'll get the Paragraph.

    1. This is an Item Containing Paragraph and an Image:

        This is another Paragraph which gonna have an image below. You can choose to make it inline by marking Image Syntax right below the paragraph or make it display in a separate line by leaving a line below the paragraph.

        ![Random Image](http://unsplash.it/500/500?random)
        
        Seriously, API Calls Wouldn't work now?

        ```java
        System.out.println("Hello, World!");
        ```