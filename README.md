
## Getting Started

### Prerequisites

Before you begin, ensure you have the following prerequisites installed on your machine:

-   **Ruby**: Version 2.7 or later
-   **Rails**: Version 6.0 or later
-   **Bundler**: Manage gem dependencies


### Installation

1.  **Clone the repository**:
    
   
    ```shell 
    git clone https://github.com/chrk-Dev/password-manager
    cd password-manager
    ```

2.  **Install dependencies**:
    
   
    ```shell 
    bundle install 
    ```
    

    
3.  **Setup the database**:
    

    ```shell 
    rails db:create
    rails db:migrate
    rails db:seed
     ```
    

### Configuration

1.  **Environment Variables**: Create a `.env` file in the root directory and add the necessary environment variables. Refer to the `.env.example` file for guidance.
    
2.  **Database Configuration**: Ensure the `config/database.yml` file is properly configured for your database.
    

## Usage

### Running the Application

To start the Rails server, run:

 ```shell 
 rails server
```
