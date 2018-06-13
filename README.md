# IDL Senior .NET Developer Recruitment Test

Please complete all 4 tasks.

1. Fix the Sorter.
    1. In the `TechnicalTests` project there is a simple bubble sort class called `Sorter`. Have a look at this class and fix any problems with it.
    2. Write unit tests to prove that the `Sorter` class works properly.

2. Create a Stack class.
    1. In the `TechnicalTests` project, write a custom `Stack` class that does not implement the .NET `System.Collections.Generic.Stack` class. Document any assumptions you make. Your class must have the following methods:
       - `Peek` - returns the top element leaving it in place.
       - `Pop` - Returns and removes the top element.
       - `Push` - Puts a new element on to the top of the stack.
       - `Clear` - Clears the stack of all elements.
    2. Write unit tests to prove that all methods in the `Stack` class perform as expected.

3. There is a web project 'MvcTests' and an API project 'MvcTestsApi' in the solution that are configured to run on http://localhost:49832/ and http://localhost:49869/ respectively.
    1. In the `MvcTests` project create a route to `/invitationdigital/tests/{index}` that takes an **optional** integer parameter `index`. 
    2. In the controller action for the route you just created, make an HTTP GET call to the API (http://localhost:49869/api/values/{index}) using the `index` parameter, and render the results in a view.
    3. When browsing the website with no path (i.e. http://localhost:49869/), it should default to the controller action above with no value for the `index` parameter
 
4. There is a test in the UnitTests project that is called `RaceConditionTests` - it is currently broken.
    1. Please make changes to the TechicalTests project so that the test passes but do not edit the test in any way. The test is to simulate multiple threads loading, updating and saving sessions. Ideally the solution should not block requests for separate sessions, if any locking is required then it should be on a per-session basis.

Either clone/download the files in this repository, or fork this repository in your own GitHub account. When finished, please let us know by emailing <hr@vouchercloud.com>.

If you've cloned/downloaded the repsitory, we will grant you access to a Google Drive folder that you can upload your completed solution to. Please include the `.git` folder with your completed solution so that we have access to any commits you have made.

If you've forked the repository, please let us know the URL.
