# Event Planner (PHP)

A simple event planner PHP project.

## Requirements
- PHP 7.4+ (or your project PHP version)
- MySQL (import SQL files in /database if needed)
- (optional) Composer if you use composer packages

## Setup
1. Copy `.env.example` to `.env` and set DB credentials.
2. Import database SQL: `mysql -u root -p your_db < database/events.sql` (repeat for users/locations)
3. Start PHP dev server: `php -S localhost:8000`
   or run via XAMPP/Apache by placing the project under htdocs.

## Notes
- `.env` is ignored by git. Do not commit secrets.
- If you need composer dependencies, create `composer.json` or run `composer init`.

