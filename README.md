# Ryzen kernel compiler patch

This patch adds additional optimization/tuning for kernel builds by adding more micro-architectures options accessible under:
```
 Processor type and features  --->
 Processor family --->
```

## Expanded CPUs include
<table>
  <tr>
    <th>CPU Family</th>
    <th>-march=</th>
    <th>Min GCC Ver</th>
    <th>Min Clang Ver</th>
  </tr>
    <tr>
    <td>AMD Family 17h (Zen)</td>
    <td>znver1</td>
    <td>9.3</td>
    <td>9.0</td>
  </tr>
  <tr>
    <td>AMD Family 17h (Zen 2)</td>
    <td>znver2</td>
    <td>9.3</td>
    <td>9.0</td>
  </tr>
  <tr>
    <td>AMD Family 19h (Zen 3)</td>
    <td>znver3</td>
    <td>10.3</td>
    <td>12.0</td>
  </tr>
  </table>
  
  ## Credit
  
  original patch - https://github.com/graysky2/kernel_compiler_patch
