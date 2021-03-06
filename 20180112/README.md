# 2018/1/12

- QuantEcon.py
  - [x] `from future import ...` をすべて消す (Very easy)
  - [ ] Vectorize `ecdf`:
    [Issue #97](https://github.com/QuantEcon/QuantEcon.py/issues/97)
  - [x] robustlq.py: Add `method` option:
    [Issue #366](https://github.com/QuantEcon/QuantEcon.py/issues/366)
  - [x] kalman.py: Add `method` option:
    [Issue #367](https://github.com/QuantEcon/QuantEcon.py/issues/367)
  - [x] pure_nash_brute: Add `tol` option:
    [Issue #381](https://github.com/QuantEcon/QuantEcon.py/issues/381) (Easy)
    → [Merged](https://github.com/QuantEcon/QuantEcon.py/pull/385)

* QuantEcon.jl
  * Some Projects that are Available for Future Work:
    [Issue #83](https://github.com/QuantEcon/QuantEcon.jl/issues/83)
  - [x] Drop `num_actions` from DiscreteDP:
    [Issue #103](https://github.com/QuantEcon/QuantEcon.jl/issues/103) (Very easy)
  - [x] DiscreteDP: Add backward_induction:
    [Issue #172](https://github.com/QuantEcon/QuantEcon.jl/issues/172)
  - [x] Fix deprecation warning in test_lae.jl:
    [Issue #200](https://github.com/QuantEcon/QuantEcon.jl/issues/200) (Very easy)

- Games.jl
  - [x] Add tol option to best response related methods:
    [Issue #21](https://github.com/QuantEcon/Games.jl/issues/21)
  * [x] Add is_dominated:
    [Issue #44](https://github.com/QuantEcon/Games.jl/issues/44)
  - [x] Return type of support_enumeration:
    [Issue #63](https://github.com/QuantEcon/Games.jl/issues/63) (Easy)

* [QuantEcon.notebooks](https://github.com/QuantEcon/QuantEcon.notebooks)
  * Python 版を Julia に翻訳する
    * [ ] [DiscreteDP Example: Automobile Replacement](http://nbviewer.jupyter.org/github/QuantEcon/QuantEcon.notebooks/blob/master/ddp_ex_rust96_py.ipynb)

* [MatchingMarkets.jl](https://github.com/oyamad/MatchingMarkets.jl)
  * 入出力の type を設計・実装する
