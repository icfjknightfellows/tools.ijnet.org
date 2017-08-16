STEP 1: Open the index.html file in tools.ijnet.org folder

STEP 2: Add data-tag='name_of_tag' for the cards that you want to show for that particular tag. For rest of the cards, keep the data-tag=""

STEP 3: The description for the text in the home page can be updated inside div id = "home_paragraph_text"

STEP 4: Create <p> tag with class 'conference_paragraph_text' and add data-tag='name_of_tag'. The name of tag should be matching with the url tag. The description of the conference can be updated in this tag.

STEP 5: To get cards related to particular tag name, in the url add ?tag=name_of_tag which should match the value entered in variable in step 2

Eg: http://tools.ijnet.org?tag=ona2017

STEP 6: Add the tag inside the dropdown with id="conference-dropdown" and direct it to the url generated in step 5.

NOTE: I have added tag 'icfj' just for demo purpose.
