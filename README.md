# tarairiu
Tarairiu is a script manager aimed to automate installation steps for users. NOT a package manager!

## The solution to a problem

Sometimes we need to automate installations, but it is not every time that we have a full lab with wake on lan set up. Also, we are constantly switching machines to new ones. With this experience, we saw that even if we tried to have a full atomated lab for all the machines, installation would eventually fail in one of these. What ended working for us was to use chocolatey to install software on Windows and whatever package manager on Linux. 

But it was frequent that we would prepare a batch/shell script, give this to one of our helpers and ask him/her to just double click or run that as an admin on the target PC. It would be a lot more useful if we've had a script repo, with all the steps to install a specific software and make the person just download that from this repo and run. So, this is the ideia behind *Trarairiu* (which btw is a name of a group of aborigen warriors from Brazil).

## Roadmap v0.1

[] - Create a requirements document to describe an overview of the idea;
[] - Create a database schema to understand the data involved in each script;
[] - Create a list to view all the scripts available (public);
[] - Create a view which show the details from a script (including a "download" button).
