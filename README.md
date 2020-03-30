# UFOs

I have added additional filters to the web page we created in the Module 11 material, per the challenge instructions.  In addition to the date filter, the data returned can be refined further by utilizing a filter for city, state, country, or shape  of UFO....or by combining some or all of the five.

(note: I originally submitted the challenge without using the forEach Instructions provided.  When alerted to this requirement, I updated my files to adhere to this instruction.  I am resubmitting the challenge now on Sunday evening.)

I noticed in the data.js file that there was some data represented by HTML entities rather than standard characters (e.g. &#33 rather than !).  In notepad, I updated these entities to the characters that most people will recognize and understand, using search and replace.

The challenge asked for at least 3 additional Bootstrap elements.  I have added a card containing a photo of a San Diego UFO (contained in the repo's images folder along with the nasa.jpg file) and, within that card, have added a "New" badge.  The other element that was added was a warning alert, letting people know that Chicken Little has predicted an impending alien invasion.

Some further refinement is recommended.  Because the input for the filters is manual, through typed input, there is a strong possibility of input error (typos).  Adding a dropdown selector of available options (for each variable) or preventing entries not contained in the data would help diminish faulty results through user error.