# Bulk Export MaskGen Project Folders

Collects all subdirectories containing a project file (.json), zips them, and uploads them to Amazon storage (S3).

# Usage

% python bulk_export.py -d *directory* -s *bucket/dir*

 - directory is the directory containing project subdirectories to upload.
 - bucket/dir is the location on S3 to upload to.

# Dependencies
pip install boto3