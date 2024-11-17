/personal-budget-tracker
│
├── config/                    # Symfony configuration files
├── src/
│   ├── Controller/            # Controllers for handling routes and logic
│   ├── Entity/                # Doctrine entities for database tables (User, Transaction, Category)
│   ├── Form/                  # Symfony form classes for input handling
│   ├── Repository/            # Custom repository classes for complex queries
│   ├── Security/              # Security and authentication logic
│   └── Service/               # Business logic services (e.g., budget calculations)
│
├── templates/                 # Twig templates for frontend views
│   └── base.html.twig         # Base layout template
│
├── public/                    # Public assets (CSS, JavaScript, images)
│   └── js/                    # JavaScript files for client-side functionality
│
├── migrations/                # Database migrations
├── var/                       # Cache and logs
├── tests/                     # PHPUnit test cases
├── .env                       # Environment configuration
└── composer.json              # Composer dependencies
