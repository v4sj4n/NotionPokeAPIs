# Pokedex
This Node.js application automates the retrieval and addition of data to a Notion database by utilizing the PokeAPI to retrieve information about various Pokemons and store them in the Notion database. An integration has been created within Notion to generate a private key and grant permissions to access the specific page where the database is located (you also need the database ID).

The application utilizes the [Notion Developers API](https://developers.notion.com/reference/intro) Reference for making changes and implementing additional features. The resulting Notion page serves as a [Pokedex](https://www.notion.so/Notion-Pok-dex-77a7d52f13164148ad6d9f9e6d5fc4c6), containing information about various Pokemons. Developers can refer to the API Reference to further customize the application and add new functionality.

To utilize this application, Node.js must first be installed, after which the command "npm install" should be run in the terminal. Additionally, a .env file must be created, and environment variables must be added like this 

    NOTION_KEY="secret_xxxxx"
    NOTION_DATABASE_ID="xxxxx"