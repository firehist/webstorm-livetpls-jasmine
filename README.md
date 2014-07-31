## webstorm-livetpls-jasmine

Embed live templates for jasmine (behavior-driven development framework for testing JavaScript code)

### Contributors

Feel free to purpose a Merge Request to improve this tools!

### Installation

You can use install bash file to launch copy of xml files to your WebStorm preferences folder.
Usage:
./install PATH

PATH is optional (it will be auto computed for Mac OS Platform and Webstorm6/7).

### Documentation

These live templates was made for [<i class="icon-share"></i> Jasmine testing framework](http://pivotal.github.io/jasmine/).

### List of available Live Templates

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

- spyon: spyOn(Obj, Key)
- spyonthrough: spyOn(Obj, Key).andCallThrough()
- spyonreturn: spyOn(Obj, Key).andReturn()
- spyoncallfake: spyOn(Obj, Key).andCallFake(fct)
