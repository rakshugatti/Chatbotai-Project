## Configuration

Create a `secrets.toml` file in the project root:

```toml
OPENROUTER_API_KEY = "your_openrouter_api_key"
```

Or set it as an environment variable:

```bash
export OPENROUTER_API_KEY="your_openrouter_api_key"
```

### Streamlit Configuration

If using Streamlit, place the file at:

```text
.streamlit/secrets.toml
```

Example:

```toml
OPENROUTER_API_KEY = "your_openrouter_api_key"
```

## Security Notes

- Never commit API keys to GitHub.
- Add `secrets.toml` to `.gitignore`.
- Rotate any key that has been exposed publicly.

Example `.gitignore`:

```gitignore
secrets.toml
.streamlit/secrets.toml
.env
```
