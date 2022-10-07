# toBeCheckedWithConfigFolder
the same files contained in "CypressToBeChecked" with json and js config files. \

Στον φάκελο cypress/e2e περιέχονται όλα τα test files.

Το πιο περιεκτηκό είναι το "CalulatorsCheck.cy.js"
Ουσιαστικά, τα περισσότερα test έχουν γίνει στο route "Calculators", 
όπου βρίσκονται όλα τα Calcs και οι φόρμες συγκεντρωμένες.

Στο πρώτο code block "beforeEach" , ουσιαστικά τρέχει όλα τα routes του Homepage (local 3000) και με το που βρει το Calculators το χτυπάει. 

Στην συνέχεια , γίνεται check στα εξής elements : 

1. Submission form : Εισάγονται ανα πεδίο random inputs , τα οποία είναι κατάλληλου τύπου (on submit βγαίνει όπως αναμένεται network error). 

2. Check sto exc rate : Ta input πεδία , τους selectors one by one καθώς και settarisma να παίρνει ο datepicker κάθε φορά που θα τρέχει το test την current hm/nia.

3. Στην ίδια λογική checked και το iban gen , green car loan calc , loan calc , etc.
