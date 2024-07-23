## Design for a Flask Application to Build Performance Dashboards

## HTML Files

**- index.html**

- This is the main page of the application.
- It should contain a navigation bar with links to the sales plays and Book of Business dashboards.
- The body of the page should contain a section for each dashboard, with placeholders for the graphs and charts.

**- sales_plays_dashboard.html**

- This page will display the sales plays dashboard.
- It should include graphs and charts that show the performance of each sales play.

**- book_of_business_dashboard.html**

- This page will display the Book of Business dashboard.
- It should include graphs and charts that show the performance of the Book of Business.

## Routes

**- /sales_plays**

- This route will handle requests for the sales plays dashboard.
- It will render the sales_plays_dashboard.html template.

**- /book_of_business**

- This route will handle requests for the Book of Business dashboard.
- It will render the book_of_business_dashboard.html template.

## Additional Features

- The application can be further enhanced by adding features such as:
   - Authentication and authorization
   - Data filtering and sorting
   - Custom reports
   - Email notifications

## Deployment

The application can be deployed to a web server using a deployment service such as Heroku or AWS Elastic Beanstalk. This will allow the application to be accessed by FSRs from anywhere with an internet connection.