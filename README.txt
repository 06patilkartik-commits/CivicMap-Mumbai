CivicMap Mumbai - My Complaints + Image Upload Update

Changes:
- Removed the Image Path field.
- Added real image selection from the computer.
- Added image preview.
- Dashboard-added complaint images are stored in browser localStorage as Data URLs.
- My Complaints now displays image, heading, description, location, Report ID and status.
- Remove Complaint exists only in My Complaints.
- Removing a complaint from My Complaints does NOT remove it from Civic Complaints and Progress.
- Existing streetlight, water, pothole and drain demo images continue to display.
- FastAPI/SQLite backend is preserved.

Run:
    cd D:\CEP_Project
    py -m uvicorn backend.main:app --host 127.0.0.1 --port 8000 --reload

Open:
    http://127.0.0.1:8000/dashboard.html

Uploaded dashboard images: JPG/JPEG/PNG/WEBP, maximum 5 MB.
