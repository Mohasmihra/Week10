# Week10
CREATE DATABASE social_media_users;
USE social_media_users;

# Social Media Users Dataset

## Importing the Dataset

To import the Social Media Users dataset into MySQL Workbench, follow these steps:

1. Download the dataset and save it locally.
2. Open MySQL Workbench and connect to your MySQL server.
3. Create a new database:
   ```sql
   CREATE DATABASE social_media_users;
   USE social_media_users;
   
### Tips for a Smooth Import Process

- **Ensure Data Type Compatibility**: Before importing, inspect the dataset to determine appropriate MySQL data types (e.g., `INT` for numerical values, `VARCHAR` for text).
- **Handle Large Files**: If the file is large, consider increasing MySQL's `max_allowed_packet` parameter to avoid import issues.
  ```sql
  SET GLOBAL max_allowed_packet=1073741824;  -- 1GB

