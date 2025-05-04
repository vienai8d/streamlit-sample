# streamlit-sample

```bash
docker build -t vienai8d/streamlit-samplt .
docker push vienai8d/streamlit-samplt
```

```bash
docker run -d --rm -p 8501:8501 vienai8d/streamlit-samplt
```

## Note on Reverse Proxy Configuration

If you are using Synology NAS with a reverse proxy, make sure to enable WebSocket support in the reverse proxy settings. Streamlit relies on WebSocket communication for real-time updates, and failing to configure this may result in connection issues.