# Visual Studio Code Jasmine Snippets ES5
This code snippets is based on [Sublime Jasmine Snippets](https://github.com/caiogondim/jasmine-sublime-snippets).

## Installation
Type `cmd-shift-p`/`ctrl-shift-p` to launch command palette and choose `Extensions: Install Extension`. Search this package and install.

## Snippets
Below is a list of all snippets and the triggers.

*The ⇥ means the TAB key.*

### Specs
| Trigger  | Description |
| -------  | ----------- |
| `desc→`  | describe method |
| `xdesc→` | xdescribe method |
| `fdesc→` | fdescribe method |
| `it→`    | it method |
| `xit→`   | xit method |
| `fit→`   | fit method |
| `ba→`    | before all method |
| `aa→`    | after all method |
| `be→`    | before each method |
| `ae→`    | after each method |

### Expectations
| Trigger  | Description |
| -------  | ----------- |
| `exp→` 	 | expect |
| `tb→`    | expect().toBe |
| `tbct→`  | expect().toBeCloseTo |
| `tbd→`   | expect().toBeDefined |
| `tbf→`   | expect().toBeFalsy |
| `tbgt→`  | expect().toBeGreaterThan |
| `tblt→`  | expect().toBeLessThan |
| `tbn→`   | expect().toBeNul |
| `tbt→`   | expect().toBeTruthy |
| `tbu→`   | expect().toBeUndefined |
| `tc→`    | expect().toContain |
| `te→`    | expect().toEqual |
| `thbc→`  | expect().toHaveBeenCalled |
| `thbcw→` | expect().toHaveBeenCalledWith |
| `tm→`    | expect().toMatch |
| `tt→`    | expect().toThrow |
| `tte→`   | expect().toThrowError |
| `nb→`    | expect().not.toBe |
| `nct→`   | expect().not.toBeCloseTo |
| `nd→`    | expect().not.toBeDefined |
| `nf→`    | expect().not.toBeFalsy |
| `ngt→`   | expect().not.toBeGreaterThan |
| `nlt→`   | expect().not.toBeLessThan |
| `nn→`    | expect().not.toBeNull |
| `nt→`    | expect().not.toBeTruthy |
| `nu→`    | expect().not.toBeUndefined |
| `nc→`    | expect().not.toContain |
| `ne→`    | expect().not.toEqual |
| `nm→`    | expect().not.toMatch |
| `nt→`    | expect().not.toThrow |
| `any→`   | jasmine.any |
| `oc→`    | jasmine.objectContaining |

### Spies
| Trigger  | Content |
| -------  | ------- |
| `so→`    | spyOn |
| `sct→`   | spyOn.and.callThrough |
| `scf→`   | spyOn.and.callFake |
| `srv→`   | spyOn.and.returnValue |
| `ss→`    | spyOn.and.stub |
| `ste→`   | spyOn.and.throwError |
| `ca→`    | spy.calls.all |
| `caa→`   | spy.calls.allArgs |
| `ca→`    | spy.calls.any |
| `caf→`   | spy.calls.argsFor |
| `cc→`    | spy.calls.count |
| `cf→`    | spy.calls.first |
| `cmr→`   | spy.calls.mostRecent |
| `cr→`    | spy.calls.reset |
| `cs→`    | createSpy |
| `cso→`   | createSpyObj |

## License
[MIT License](http://opensource.org/licenses/MIT)
