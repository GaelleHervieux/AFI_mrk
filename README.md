| Location| Location | Scale |Shape |
|:--------:|:--------:|:--------:|:--------:|
| Test 0|  ~ 1 | ~ 1  |  ~ 1   | # eXtremes GEV computation (independent)
| Test 1|  ~ s(elevation("cr",k=10)) + s(cell("mrf",k=100))  | ~ s(elevation("cr",k=10)) + s(cell("mrf",k=100))  |  ~ s(elevation("cr",k=10)) + s(cell("mrf",k=100))   |
| Test 2|  ~ s(elevation("cr",k=20)) + s(cell("mrf",k=50))   | ~ s(elevation("cr",k=20)) + s(cell("mrf",k=50))   |  ~ s(elevation("cr",k=20)) + s(cell("mrf",k=50))   |
| Test 3|  ~ s(elevation("cr",k=10)) + s(cell("mrf",k=50))   | ~ s(elevation("cr",k=10)) + s(cell("mrf",k=50))  |  ~ s(elevation("cr",k=10)) + s(cell("mrf",k=50))    |
| Test 4|  ~ te(elevation("cr",k=10), cell("mrf",k=100))  | ~ 1  |  ~ 1   |
| Test 5|  ~ te(elevation("cr",k=20), cell("mrf",k=50))   | ~ 1  |  ~ 1   |
| Test 6|  ~ te(elevation("cr",k=10), cell("mrf",k=50))   | ~ 1  |  ~ 1   |
| Test 7|  ~ te(elevation("cr",k=10), cell("mrf",k=50))  |  ~ te(elevation("cr",k=10), cell("mrf",k=50))   |  ~ 1   |
| Test 8|  ~ te(elevation("cr",k=10), cell("mrf",k=50)) |  ~ te(elevation("cr",k=10), cell("mrf",k=50))   |  ~ te(elevation("cr",k=10), cell("mrf",k=50))  |

Test 7 crashed

test 3 running time ~ 5min (laptop)

test 8 running time ~ 5h (laptop)
