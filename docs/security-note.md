# Security Note

The original notebook contained execution outputs, including partial API key previews from a key-check cell. Before publishing this repository, all code cell outputs were cleared and the key-check cell was changed so that it only reports whether required environment variables are loaded.

Do not commit the following files or values:

- `api_key.txt`
- `.env`
- OpenAI API keys
- Tavily API keys
- generated audio/video outputs containing private material
- uploaded PPT files that are not intended for public release

If a real API key was ever shown in a notebook output or shared screen, rotate that key from the provider dashboard.
