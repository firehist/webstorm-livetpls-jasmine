## webstorm-livetpls-jasmine

Embed live templates for jasmine (behavior-driven development framework for testing JavaScript code)

### Contributors

Feel free to purpose a Merge Request to improve this tools!

### Installation

|System|Location|
|:-----|:-------|
|windows|`C:\Users\Administrator\.WebStorm8\config\templates`|
|linux|`~.[product name][version number]\config\templates`|
|mac|`~/Library/Preferences/[product name][version number]/templates`|

### Documentation

These live templates was made for [<i class="icon-share"></i> Jasmine testing framework](https://github.com/pivotal/jasmine).

### List of available jasmine Live Templates

- jasd: Jasmine describe template
- jasb: beforeEach
- jasa: afterEach
- it: Jasmine it template
- jasbi: beforeEach with Angular's inject
- jasbm: beforEach with AngularJS module
- iit: Jasmine it template with injectables
- jasctrl: Jasmine describe controller
- jasdir: Jasmine describe directive
- jasf: Jasmine describe filter
- jass: Jasmine describe service
- expectbe: Expect(X).toBe(Y)
- expectnotbe: Expect(X).not.toBe(Y)
- expectequal: Expect(X).toEqual(Y)
- expectmatch: Expect(X).toMatch(Y)
- expectnotmatch: Jasmine Expect(X).not.toMatch(Y)
- expectdefined: Expect(X).toBeDefined()
- expectundefined: Expect(X).toBeUndefined()
- expectnotundefined: Expect(X).toBeUndefined()
- expectnotdefined: Jasmine expect().not.toBeDefined()
- expectnull: Expect(X).toBeNull()
- expectnotnull: Expect(X).not.toBeNull()
- expecttrue: Expect(X).toBeTruthy(Y)
- expectfalse: Expect(X).toBeFalsy(Y)
- expectnotfalse: Expect(X).not.toBeFalsy(Y)
- expectnottrue: Expect(X).not.toBeTruthy(Y)
- expectcontain: Expect(X).toContain(Y)
- expectnotcontain: Expect(X).not.toContain(Y)
- expectlessthan: Expect(X).toBeLessThan(Y)
- expectgeaterthan: Expect(X).toBeGreaterThan(Y)
- expectcloseto: Expect(X).toBeCloseTo(Y, Z)
- expectthrow: Expect(X).toThrow()
- expectnotthrow: Expect(X).not.toThrow()
- expecthavebeencalled: Expect(X).toHaveBeenCalled()
- expecthavebeencalledwith: Expect(X).toHaveBeenCalledWith(Y)
- expectnumber: expect(X).toEqual(jasmine.any(Number))
- expectarray: expect(X).toEqual(jasmine.any(Array))
- expectfunc: expect(X).toEqual(jasmine.any(Function))
- expectobj: expect(X).toEqual(jasmine.any(Object))
- expectstr: expect(X).toEqual(jasmine.any(String))
- expectobjcontain: expect(X).toEqual(jasmine.objectContaining({}))
- createspy: jasmine.createSpy(Key)
- createspyobj: jasmine.createspyobj(Key, Array)
- spyon: spyOn(Obj, Key)
- spyonthrough: spyOn(Obj, Key).andCallThrough()
- spyonreturn: spyOn(Obj, Key).andReturn()
- spyoncallfake: spyOn(Obj, Key).andCallFake(fct)

### List of available jasmine-ajax Live Templates

- ajaxins: jasmine.Ajax.install()
- ajaxuni: jasmine.Ajax.uninstall()
- ajaxreqres: jasmine.Ajax.requests.mostRecent().response(ResponseText)
- ajaxreqstub: jasmine.Ajax.stubRequest(Url).andReturn(ResponseText)
- ajaxmock: jasmine.Ajax.withMock(function(){})
