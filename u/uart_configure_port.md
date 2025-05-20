# Function: <code>uart_configure_port</code>

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
In drivers/tty/serial/serial_core.c (ffffffff8150136c)
Location: drivers/tty/serial/serial_core.c:2210
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
In drivers/tty/serial/serial_core.c (ffffffff81551ebb)
Location: drivers/tty/serial/serial_core.c:2297
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
In drivers/tty/serial/serial_core.c (ffffffff8157ea60)
Location: drivers/tty/serial/serial_core.c:2259
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
In drivers/tty/serial/serial_core.c (ffffffff815931d9)
Location: drivers/tty/serial/serial_core.c:2263
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
In drivers/tty/serial/serial_core.c (ffffffff815f7d09)
Location: drivers/tty/serial/serial_core.c:2266
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
In drivers/tty/serial/serial_core.c (ffffffff81630d15)
Location: drivers/tty/serial/serial_core.c:2263
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
In drivers/tty/serial/serial_core.c (ffffffff8164eec5)
Location: drivers/tty/serial/serial_core.c:2322
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
In drivers/tty/serial/serial_core.c (ffffffff81683a77)
Location: drivers/tty/serial/serial_core.c:2328
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
In drivers/tty/serial/serial_core.c (ffffffff816a6125)
Location: drivers/tty/serial/serial_core.c:2329
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2340
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff8175aec0-ffffffff8175b03a: uart_configure_port.isra.0 (STB_LOCAL)
ffffffff8175c0ee-ffffffff8175c266: uart_configure_port.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2347
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff81775fa0-ffffffff8177611a: uart_configure_port.isra.0 (STB_LOCAL)
ffffffff81c07c6f-ffffffff81c07de7: uart_configure_port.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2344
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff81759740-ffffffff817598b2: uart_configure_port.isra.0 (STB_LOCAL)
ffffffff81bf980f-ffffffff81bf9987: uart_configure_port.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817ddb24)
Location: drivers/tty/serial/serial_core.c:2356
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8191c6a7)
Location: drivers/tty/serial/serial_core.c:2398
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a78656)
Location: drivers/tty/serial/serial_core.c:2527
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81ac310e)
Location: drivers/tty/serial/serial_core.c:2553
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b15fb2)
Location: drivers/tty/serial/serial_core.c:2588
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
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
In drivers/tty/serial/serial_core.c (ffff800010882414)
Location: drivers/tty/serial/serial_core.c:2329
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
In drivers/tty/serial/serial_core.c (c097f980)
Location: drivers/tty/serial/serial_core.c:2329
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
In drivers/tty/serial/serial_core.c (c000000000925778)
Location: drivers/tty/serial/serial_core.c:2329
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
In drivers/tty/serial/serial_core.c (ffffffe00054ca7c)
Location: drivers/tty/serial/serial_core.c:2329
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
In drivers/tty/serial/serial_core.c (ffffffff8166bb85)
Location: drivers/tty/serial/serial_core.c:2329
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
In drivers/tty/serial/serial_core.c (ffffffff8164ace5)
Location: drivers/tty/serial/serial_core.c:2329
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
In drivers/tty/serial/serial_core.c (ffffffff81699f65)
Location: drivers/tty/serial/serial_core.c:2329
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
In drivers/tty/serial/serial_core.c (ffffffff816b4b65)
Location: drivers/tty/serial/serial_core.c:2329
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
</details>
</li>
</ul>

## Differences
