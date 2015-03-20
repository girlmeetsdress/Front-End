# As a marketing person, I want to ask new customers of how they heard of MS by way of an Exit poll, so that see the impact of marketing activities.

### AC 

AC

- Add a new page that can accessed here: https://www.marleyspoon.de/admin/general_settings/edit called “Exit Poll”

- There will be a fixed question: "Wie hast du von Marley Spoon erfahren?"

- I can add, activate & deactivate answers. 

- To start we'll have the following answers there: 
-- Facebook Werbung
-- Google Werbung
-- Banner Werbung
-- Magazin/Zeitung
-- Persönliche Empfehlung
-- Social Media, z.B. Twitter
-- Sonstiges




# As a first-time customer who's just ordered, I see an exit poll on the order confirmation page

### AC

- First time users only
- Poll isn't mandatory (user can click to the side or on the X to close the modal window
- See wireframe
- Randomize the order of the answers for each view
- Only 1 answer can be given
- CTA is "SENDEN" below
- Show a "Danke!" after that while the modal fades out

Please stick to the style guide for the UI. 



# As a marketing person, I want to see the exit poll report below the exit poll's answers, so that I can see the performance of marketing activities

### AC

- 2 report sections are needed: (i) mobile/via API and (ii) Web (Exit poll via API covered in another story)

- Should sit in https://www.marleyspoon.de/admin/reports

- I can set a date-range 

The data reports: 

2 of the following (Web & Mobile)

1. Top section 
- Select date range + "go" CTA
- Total times exit poll was shown
- Total times answered
- Response rate  = % of people that saw the exit poll and answered 

2. Main section
- All the answers (channels) active & non-active with absolute values and % next to them.
