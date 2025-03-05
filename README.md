#prompt utilizado : 
#Gemini Advanced trial version.
<pre>
    create a app & game review log using local storage html ,css and js please , 
    add a section to describe the previous steps before I found the right strategies 
    to complete the goals of each app and game.
</pre>

#Description
<pre>
    HTML Structure:

        The HTML sets up a basic form (reviewForm) for adding reviews, including fields for title, type (app/game), rating, previous strategies, and the review itself.

        It also creates a reviews section to display the saved reviews.
        It uses local storage to store the information.

        CSS Styling:

        Basic CSS provides minimal styling for readability.

    JavaScript Functionality:

        loadReviews():

            Retrieves reviews from localStorage (if any) and parses them.
            Dynamically creates HTML elements to display each review in the reviewList div.
            Adds a delete button to each review.

        saveReviews(reviews):

            Stringifies the reviews array and saves it to localStorage.
            Calls loadReviews() to refresh the displayed list.

        deleteReview(index):

            removes the review from the array at the given index.
            calls saveReviews to update the local storage.

        Event Listener for addReviewButton:

            When the "Add Review" button is clicked, it gathers the input values.
            Creates a newReview object.
            Retrieves existing reviews from localStorage, adds the new review, and saves the updated list.
            Clears the input fields.
            Includes a check to ensure all fields are filled.

        DOMContentLoaded Event:

            Ensures that the JavaScript code runs after the HTML document has been fully loaded.
            Calls loadReviews() to display any existing reviews when the page loads.

        How to Use:

            Save the code: Save the HTML, CSS, and JavaScript as an .html file (e.g., review.html).

            Open in a browser: Open the review.html file in your web browser.

            Add reviews: Fill out the form and click "Add Review."

            View reviews: The reviews will appear in the "Reviews" section.

            Delete reviews: Click the "Delete" button next to a review to remove it.

        Key Improvements:

            Previous Strategies Section: Added a strategies textarea and included it in the review display.

            Delete Functionality: added a delete button to each review.

            Error Checking: added a check to ensure all fields are filled before saving.

            Clearer Structure: improved the code structure and comments for better readability.

            Type Selection: added a select element to choose between app and game.

    #end of the text block.
</pre>
