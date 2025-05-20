# Function: <code>spi_get_gpio_descs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8178fe05)
Location: drivers/spi/spi.c:2282
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff817b3819)
Location: drivers/spi/spi.c:2288
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int spi_get_gpio_descs(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2469
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81878000-ffffffff81878174: spi_get_gpio_descs (STB_LOCAL)
ffffffff8187d0b6-ffffffff8187d0ed: spi_get_gpio_descs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int spi_get_gpio_descs(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2545
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81886910-ffffffff81886a84: spi_get_gpio_descs (STB_LOCAL)
ffffffff81c18b19-ffffffff81c18b50: spi_get_gpio_descs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int spi_get_gpio_descs(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2565
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81869280-ffffffff8186942d: spi_get_gpio_descs (STB_LOCAL)
ffffffff81c0a911-ffffffff81c0a948: spi_get_gpio_descs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int spi_get_gpio_descs(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2699
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff818f8b90-ffffffff818f8d47: spi_get_gpio_descs (STB_LOCAL)
ffffffff81d0f7b8-ffffffff81d0f808: spi_get_gpio_descs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int spi_get_gpio_descs(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2807
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81a49fd0-ffffffff81a4a186: spi_get_gpio_descs (STB_LOCAL)
ffffffff81eda4c7-ffffffff81eda50e: spi_get_gpio_descs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int spi_get_gpio_descs(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2990
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81bd0790-ffffffff81bd096a: spi_get_gpio_descs (STB_LOCAL)
ffffffff8209cf26-ffffffff8209cf3f: spi_get_gpio_descs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int spi_get_gpio_descs(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2997
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81c284c0-ffffffff81c2869d: spi_get_gpio_descs (STB_LOCAL)
ffffffff8211de31-ffffffff8211de4a: spi_get_gpio_descs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int spi_get_gpio_descs(struct spi_controller *ctlr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3150
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff81cdac10-ffffffff81cdaded: spi_get_gpio_descs (STB_LOCAL)
ffffffff821ff38e-ffffffff821ff3a7: spi_get_gpio_descs.cold (STB_LOCAL)
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
In drivers/spi/spi.c (ffff8000109c786c)
Location: drivers/spi/spi.c:2288
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (c0ab07f0)
Location: drivers/spi/spi.c:2288
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (c000000000a88298)
Location: drivers/spi/spi.c:2288
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffe000617ff4)
Location: drivers/spi/spi.c:2288
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff817782f9)
Location: drivers/spi/spi.c:2288
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff817580a9)
Location: drivers/spi/spi.c:2288
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff817a8699)
Location: drivers/spi/spi.c:2288
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/spi/spi.c (ffffffff817c2529)
Location: drivers/spi/spi.c:2288
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
