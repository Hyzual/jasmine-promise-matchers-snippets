# Jasmine Promise Matchers SublimeText Snippets

[Jasmine Promise Matchers][jasmine-promise-matchers] are custom [Jasmine][jasmine] matchers to make testing [Angular promises][angular-promises] easier.

## Snippets

Below is a list of all snippets currently supported by this package and the <kbd>Tab</kbd> trigger of each one.

### BeforeEach

To use the expectations, please first install them with the following snippet in a `BeforeEach`, after having called [angular.mock.module][angular-mocks-module]:

- `installPromiseMatchers();` - ipm<kbd>Tab</kbd>

### Expectations

- `expect(promise).toBeResolved();` - tbrs<kbd>Tab</kbd>
- `expect(promise).toBeResolvedWith('result');` - tbrsw<kbd>Tab</kbd>
- `expect(promise).toBeRejected();` - tbrj<kbd>Tab</kbd>
- `expect(promise).toBeRejectedWith('error');` - tbrjw<kbd>Tab</kbd>


[angular-promises]: http://docs.angularjs.org/api/ng/service/$q
[angular-mocks-module]: https://docs.angularjs.org/api/ngMock/function/angular.mock.module
[jasmine]: https://jasmine.github.io/
[jasmine-promise-matchers]: https://github.com/bvaughn/jasmine-promise-matchers
