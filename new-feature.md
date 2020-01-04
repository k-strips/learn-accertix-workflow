- _[link to new feature #1](https://github.com/k-strips/learn-accertix-workflow/issues/1)_
eg:
```
[feature: sign in functionality #1234]()
```

---

**user experience and user interface design plan (if applicable)**

- [Link to UI/UX workflow prototype](https://yourlinkhere.com)
  (ensure design is created for the various screen types to be supported)

---

**engineering and implementation plan**

_for each step_

- briefly state the step,
- define any implementation details right under the step.
  - details can be expressed in pseudocode, but the closer to the real implementation, the better.
  - when unsure about how to implement a particular feature, isolated experiments and demos can prove very helpful.
  - these codesandbox experiments and demos for individual steps can be linked right under the step.
- then define the various tests that will be written for that particular implementation detail
- eg:

```
  ...

5. Create sign in input validation function
   - validate (string username, string password):
        handle invalid input errors
        sanitize the input
        return sanitized input

    - unit tests
         - returns correct value for correct input
         - handles invalid input well.
            - empty username or password ...
            - undefined, null, invalid non-alphanumeric characters,

   ...

```

NB: implementing the UI is part of the steps to be indicated here. details should be provided as well.

- eg:

```

   ...

7. Create 3 column view, with button in the middle, right underneath
   - <div class='container'>
       <div class='row'>
        <div class='col-4 sm-col-12'></div>
        <div class='col-4 sm-col-12'></div>
        <div class='col-4 sm-col-12'></div>
       </div>
       <button class='center'>Update</button>
     </div>

   ...

```

pseudocode or even real code in codesandboxes are ideal.

_after all the steps have been listed_

- integration tests

- end-to-end tests
