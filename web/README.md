# Ward Lab browser adaptation

Original notebook remains unchanged. The demo executes Ward linkage on population-standardized two-column numeric data. Synthetic example only; no original dataset is claimed. No pretrained model, backend, or paid service. Ties may yield a different valid merge order. Original categorical and missing-value preprocessing is not reproduced.

Local: from this directory run python -m http.server 8000 and open http://localhost:8000. Unit tests: node --test cluster.test.mjs. Vercel root directory: web; framework: Other; static files, no build required. Browser tests and numerical comparison against SciPy remain pending. No production URL is claimed.
