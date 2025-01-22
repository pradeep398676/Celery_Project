# Celery_Project
How to run celery beat and celery worker...

# First run your project

# To run celery worker
celery -A djcelery worker --pool=solo -l info

# To run celery beat
celery -A djcelery beat -l info
