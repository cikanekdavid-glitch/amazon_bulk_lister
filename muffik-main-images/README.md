# MUFFIK main product images (Amazon UK)

Static host for the main product images of the MUFFIK Orthopedic Mats Amazon UK
listings. Amazon's SP-API sets a listing's main image by URL — Amazon fetches the
file itself — so these need a public HTTPS address.

Each file is named after the ASIN it belongs to. Backgrounds were flattened to
pure white (RGB 255,255,255) to meet Amazon's main-image standard; the source
photography is otherwise unmodified.

Added 24 Aug 2026. Safe to delete once Amazon has ingested the images — Amazon
copies them to its own CDN (`m.media-amazon.com`) on ingestion and does not
re-fetch this URL afterwards.
