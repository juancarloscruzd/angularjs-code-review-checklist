I'm not the author of this amazing checklist, i've only copied it in a readable and printable way.
The original site if [here](https://angularcodereview.com/angularjs/)

#Code Style

- [ ]  Is all code intention-revealing?
- [ ]  Is all code linted/hinted?
- [ ]  Is `controller as` syntax used?
- [ ]  Is DOM manipulation handled only by directives?

- [ ]  Are names prefixed with `$ ` avoided?

- [ ]  Is direct use of globals avoided?

- [ ]  Are AngularJS specific directives put after standard attributes in templates?

- [ ]  Are built-in AngularJS dependencies injected before custom ones?

- [ ]  Are modules named correctly?

- [ ]  Are controllers named correctly?

- [ ]  Are directives named correctly?

- [ ]  Are filters named correctly?


- [ ]  Are services named correctly?
- [ ]  Are factories named correctly?

- [ ]  Are built-in AngularJS directives used whenever possible?


- [ ]  Are built-in AngularJS services used whenever possible?


- [ ]  Is ng-cloak used to prevent content from flashing

- [ ]  Is console.log() avoided?

- [ ]  Is code minification safe?

# Architecure

- [ ]  Is there a component-driven structure?


- [ ]  Do directives communicate correctly?

- [ ]  Is business logic defined in services?

- [ ]  UI-Router: has a default route been configured?

- [ ]  ngRoute: has a default route been configured?

- [ ]  ngRoute: are route errors handled properly?

- [ ]  UI-Router: are state change errors handled properly?

- [ ]  Are exceptions handled properly?

- [ ]  Are resolves used where needed?

# Security

- [ ]  Is Strict Contextual Escaping enabled?

- [ ]  UI-Router: are private parts of application properly protected?


# Performance

- [ ]  Are scripts at bottom of the document?

- [ ]  Are styles in HEAD?

- [ ]  Is expensive logic avoided in filters?

- [ ]  Is filtering logic handled in controller if needed?


- [ ]  Are expensive operations cached?

- [ ]  Are complex expressions avoided in templates?

- [ ]  Is one-time binding used where possible?

- [ ]  Is logic in watchers kept as simple as possible?

- [ ]  Is $watchCollection used instead of deep watch where possible?

- [ ]  Is `$applyAsync` used when possible?

- [ ]  Do timers skip `$digest` cycle when possible?

- [ ]  Are resources cleaned up when scope is destroyed?

- [ ]  Are templates bundled with main JavaScript file?

- [ ]  Is ngModelOptions used where possible?




