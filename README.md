# AutoAvail for GCal

## About AutoAvail for GCal
AutoAvail for GCal is a Chrome extension that enhances email communication by integrating with Google Calendar to suggest available meeting times. When a user types "{availability}" while composing an email, the extension instantly retrieves their free time slots from their calendar and inserts them into the message. It also offers customizable settings, such as restricting availability to 9 AM - 5 PM on weekdays, ensuring users share only their preferred time windows.


Our platform offers:
- **Time-saving**: Automates the process of checking and listing available times, reducing manual effort.  
- **Accuracy**: Pulls real-time data from Google Calendar to prevent scheduling errors or double-bookings.  
- **Convenience**: Seamlessly integrates into the email composition flow with a simple trigger word.  
- **Customizable**: Lets users define availability preferences, like 9-5 on weekdays, to match their work habits.  
- **Productivity boost**: Speeds up meeting coordination, allowing users to focus on their core tasks.

## Project Structure
- `USER-STORIES.md`: Contains detailed user stories and feature requirements
- `layouts/`: Contains the HTML templates
- `assets/`: Contains SCSS and images
- `content/`: Contains the site content
- `themes/`: Contains the Hugo theme

## Development
This site is built using:
- Hugo static site generator
- Bootstrap for styling
- SCSS for custom styling

### Local Development
1. Install Hugo (extended version)
bash
brew install hugo
2. Clone the repository
git clone [[repository-url](https://github.com/Natalielim/autoavail.git)]
cd [repository-name]autoavail
3. Start the Hugo server
hugo server