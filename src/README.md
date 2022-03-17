Injectable
==========

### Introduction

Let's continue with our work on the _api_ module.

In order to access the _RESTful resources_ we'd like to have remote _Injectables_. 

### Task

#### event.resource.ts / EventResource - Injectable

1. Use the CLI to create a _service_: `ng g s api/event/event`
2. In order to change the sterotype of the just created _service_ into _resource_, rename the file into _event.resource.ts_ and the class into _EventResource_.
3. Provide the Method `findAll(): EventResponse[]`
4. For now, copy & paste the dataset as located at http://localhost:3000/events as result for this method.

#### profile.resource.ts / ProfileResource - Injectable

1. Use the CLI to create a _service_: `ng g s api/profile/profile`
2. In order to change the sterotype of the just created _service_ into _resource_, rename the file into _profile.resource.ts_ and the class into _ProfileResource_.
3. Provide the Method `findAll(): ProfileResponse[]`
4. For now, copy & paste the dataset as located at http://localhost:3000/profiles as result for this method.

### NOTE

As we will see later on, the result type of the _findAll()_ methods is not "final".
