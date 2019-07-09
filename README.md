## Excel to Director Invoice Exporter - Releases

# v1.0
Added Continuous Delivery for the app with Squirrel as a feature. New notifications for updates.

# v1.1
Changing access file to handle both local and remote connections.

# v1.2 - v1.3
Bug fixing: update problem - Squirrel wasn't properly configured.

# v1.4
Minor (but critical) change: New process to numerate accounts.

# v1.5
Migrated to Entity Framework. About the test suite: New UI tests with Selenium. More unit tests added - coverage up +15%. New DB tests added, now that everything DB-related runs on EF.

# v1.6
Adding missing .msi files as part of the main installation file - latest .NET connector is not compatible with EF+MySQL, so it's mandatory to store a backup of the previous version.

# v1.7
Bug fixing: the program doesn't allow having duplicate CIFs anymore.

# v1.8
Bug fixing: 'Create new company' feature was duplicating the generic DB schema instead of the chosen one.
