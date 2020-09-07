FROM nginx

HEALTHCHECK --interval=5s --timeout=3s --retries=3 CMD curl http://localhost/index.html || exit 1
