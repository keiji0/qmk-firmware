# Matrix Diagram for ASH1800

```
┌───┐┌───┬───┬───┬───┐┌───┬───┬───┬───┐┌───┬───┬───┬───┐      ┌───┬───┬───┬───┐
│00 ││01 │02 │03 │60 ││61 │62 │63 │04 ││05 │06 │07 │08 │      │54 │55 │56 │57 │
└───┘└───┴───┴───┴───┘└───┴───┴───┴───┘└───┴───┴───┴───┘      ├───┼───┼───┼───┤
                                                              │64 │65 │66 │67 │
┌───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───┬───────┐ ├───┼───┼───┼───┤
│10 │11 │12 │13 │70 │71 │72 │73 │14 │15 │16 │17 │18 │19     │ │74 │75 │76 │77 │
├───┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─────┤ ├───┼───┼───┼───┤     ┌─────┐
│20   │21 │22 │23 │80 │81 │82 │83 │24 │25 │26 │27 │28 │29   │ │84 │85 │86 │87 │     │38   │
├─────┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴┬──┴─────┤ ├───┼───┼───┼───┤  ┌──┴┐    │ ISO Enter
│30    │31 │32 │33 │90 │91 │92 │93 │34 │35 │36 │37 │38      │ │94 │95 │96 │97 │  │29 │    │
├────┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴─┬─┴────┬───┘ ├───┼───┼───┼───┤  └───┴────┘
│40  │41 │42 │43 │A0 │A1 │A2 │A3 │44 │45 │46 │47 │48    │┌───┐│A4 │A5 │A6 │A7 │
├────┼───┴┬──┴─┬─┴───┴───┴───┴───┴───┴──┬┴───┴┬──┴──┬───┘│A9 │└───┼───┼───┤   │
│50  │51  │52  │53                      │B4   │B7   │┌───┼───┼───┐│B5 │B6 │   │
└────┴────┴────┴────────────────────────┴─────┴─────┘│A8 │B8 │B9 │└───┴───┴───┘
                                                     └───┴───┴───┘
┌────────┐
│40      │ 2.25u LShift
└────────┘
┌─────┬─────┬───────────────────────────┬─────┬─────┐
│50   │51   │53                         │B4   │B7   │ WKL
└─────┴─────┴───────────────────────────┴─────┴─────┘
```
