# candidate-assessment
A web development task to demonstrate technical thought process and development approach.

### Web developer task

Given a JSON collection of vehicles, we'd like you to create a simple ASP.NET MVC web application that lists the car information supplied.

The application should initially list 10 cars, with a load more button to dynamically retrieve a further 10 cars at a time.
The data can be passed in as simple in-memory objects.

Image paths referenced within the supplied JSON file (e.g. within `obj/image/large`, `obj/image/full`, and `obj/image/small`) should be prepended with ‘https://listers.co.uk’ as the base URI - this would mean an object with the value `/img/a/l/24456/van` should use the URL `https://listers.co.uk/img/a/l/24456/van`.

Consideration over techniques for sorting and filtering the data along with unit tests would be very useful.

Please include a read me file in your project describing how to interact with your application along with the significance of any automated tests you may have added to your solution.
