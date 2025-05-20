# Function: <code>uart_report_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81501482)
Location: drivers/tty/serial/serial_core.c:2176
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81551fae)
Location: drivers/tty/serial/serial_core.c:2262
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8157eb87)
Location: drivers/tty/serial/serial_core.c:2224
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81593330)
Location: drivers/tty/serial/serial_core.c:2229
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f7e66)
Location: drivers/tty/serial/serial_core.c:2232
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81630e40)
Location: drivers/tty/serial/serial_core.c:2229
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164eff4)
Location: drivers/tty/serial/serial_core.c:2288
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81683bae)
Location: drivers/tty/serial/serial_core.c:2294
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a625c)
Location: drivers/tty/serial/serial_core.c:2295
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8175af6e)
Location: drivers/tty/serial/serial_core.c:2306
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8177604e)
Location: drivers/tty/serial/serial_core.c:2313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817597e6)
Location: drivers/tty/serial/serial_core.c:2310
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2314
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff817d9fc0-ffffffff817da0a0: uart_report_port.constprop.0 (STB_LOCAL)
ffffffff81cf99e7-ffffffff81cf9ad8: uart_report_port.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2356
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff81918cf0-ffffffff81918dd3: uart_report_port.constprop.0 (STB_LOCAL)
ffffffff81ec1c71-ffffffff81ec1d7b: uart_report_port.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a74a40)
Location: drivers/tty/serial/serial_core.c:2485
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff81a74a40-ffffffff81a74c5d: uart_report_port.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abeea0)
Location: drivers/tty/serial/serial_core.c:2511
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
```
**Symbols:**

```
ffffffff81abeea0-ffffffff81abf09c: uart_report_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b11cd0)
Location: drivers/tty/serial/serial_core.c:2546
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
```
**Symbols:**

```
ffffffff81b11cd0-ffffffff81b11ecc: uart_report_port.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff800010882530)
Location: drivers/tty/serial/serial_core.c:2295
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097fa88)
Location: drivers/tty/serial/serial_core.c:2295
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c0000000009258e4)
Location: drivers/tty/serial/serial_core.c:2295
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054cad8)
Location: drivers/tty/serial/serial_core.c:2295
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166bcbc)
Location: drivers/tty/serial/serial_core.c:2295
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164ae1c)
Location: drivers/tty/serial/serial_core.c:2295
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8169a09c)
Location: drivers/tty/serial/serial_core.c:2295
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b4c9c)
Location: drivers/tty/serial/serial_core.c:2295
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
</ul>

## Differences
