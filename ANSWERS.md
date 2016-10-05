## Questions

Go to `localhost:3000/teachers` in your browser; why does this not work?

Because the create method of TeachersController was empty.

What type of request did your browser just perform?

Going to localhost:3000/teachers/new performs a GET request.

Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?

Hmm mine still errors with a routing error? (No route matches [GET] "/teachers"...)
I checked Piazza and someone had a similar issue but their fix didn't work for me so I'm not sure what's going wrong.

Why does `localhost:3000/teachers` work now?

As per the above, I still can't navigate there directly. I can only get there through submitting the form in students/new then being redirected to /students.