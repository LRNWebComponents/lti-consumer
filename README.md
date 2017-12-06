# \<lti-consumer\>

A LTI Consumer
# lti-consumer

### Desired workflow.

1. Faculty member decides they don't want to use the LMS for their course/project but they do want to use some number of LTI tools.
2. Faculty member decides on a tech stack for their course/project that doesn't know a thing about LTI, such as many CMSs, frameworks, or plain ole HTML.
3. Faculty member places this component in their stack. 
    * If they are just writing HTML, it's inline somewhere.
    * If they are using a CMS like Grav or Wordpress or lower-level {insert programming language here} framework, they leverage the plugin architectures those platforms provide. We could go the extra step of building these in separate repos as well.
4. This component then renders in their tech stack a secure, compliant LTI consumer workflow.
 
### Things missing to enable this workflow.

* this component
* lti credential storage (is it really though?)
* 


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
