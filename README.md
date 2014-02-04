webstorm-livetpls-jasmine
=========================

Embed live templates for jasmine (behavior-driven development framework for testing JavaScript code)

# Installation

You can use install bash file to launch copy of xml files to your WebStorm preferences folder.
Usage:
./install PATH

PATH is optional (it will be auto computed for Mac OS Platform and Webstorm6/7).

# Documentation

These live templates was made for [<i class="icon-share"></i> Jasmine testing framework](http://pivotal.github.io/jasmine/).

# List of available Live Templates

- jasd: Jasmine describe template
- jasi: Jasmine it template
- jasbi: beforeEach with Angular's inject
- jasbm: beforEach with AngularJS module
- jasb: beforeEach
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
- spyon: spyOn(Obj, Key)
- spyonthrough: spyOn(Obj, Key).andCallThrough()
- spyonreturn: spyOn(Obj, Key).andReturn()
- spyoncallfake: spyOn(Obj, Key).andCallFake(fct)
- expecthavebeencalled: Expect(X).toHaveBeenCalled()
- expecthavebeencalledwith: Expect(X).toHaveBeenCalledWith(Y)
- it: Jasmine it template
- jasa: afterEach
- expecttypeof: Expect(typeof X).toEqual(Y)
- expectnumber: Expect(typeof X).toEqual('number')
- expectarray: Expect(X.length).toBeDefined()
- expectfunc: Expect(typeof X).toEqual('function')
- expectobj: Expect(typeof X).toEqual('object')
- expectstr: Expect(typeof X).toEqual('string')
