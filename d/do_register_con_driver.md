# Function: <code>do_register_con_driver</code>

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
In drivers/tty/vt/vt.c (ffffffff814f9542)
Location: drivers/tty/vt/vt.c:3589
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffff81549c12)
Location: drivers/tty/vt/vt.c:3588
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffff81576642)
Location: drivers/tty/vt/vt.c:3587
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffff8158a512)
Location: drivers/tty/vt/vt.c:3596
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffff815eead2)
Location: drivers/tty/vt/vt.c:3601
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffff81627e15)
Location: drivers/tty/vt/vt.c:3599
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffff81645585)
Location: drivers/tty/vt/vt.c:3914
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffff81679a65)
Location: drivers/tty/vt/vt.c:3970
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffff8169c255)
Location: drivers/tty/vt/vt.c:4001
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int do_register_con_driver(const struct consw *csw, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4011
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
```
**Symbols:**

```
ffffffff8174d4e0-ffffffff8174d632: do_register_con_driver (STB_LOCAL)
ffffffff81753f33-ffffffff81753f5d: do_register_con_driver.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int do_register_con_driver(const struct consw *csw, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4099
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
```
**Symbols:**

```
ffffffff81768a80-ffffffff81768bd2: do_register_con_driver (STB_LOCAL)
ffffffff81c0794c-ffffffff81c07976: do_register_con_driver.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int do_register_con_driver(const struct consw *csw, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4099
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
```
**Symbols:**

```
ffffffff8174c190-ffffffff8174c2e2: do_register_con_driver (STB_LOCAL)
ffffffff81bf9586-ffffffff81bf95b0: do_register_con_driver.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_register_con_driver(const struct consw *csw, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4104
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
```
**Symbols:**

```
ffffffff817cdcf0-ffffffff817cde96: do_register_con_driver (STB_LOCAL)
ffffffff81cf9559-ffffffff81cf9583: do_register_con_driver.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_register_con_driver(const struct consw *csw, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4104
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
```
**Symbols:**

```
ffffffff8190b990-ffffffff8190bb5e: do_register_con_driver (STB_LOCAL)
ffffffff81ec1763-ffffffff81ec178b: do_register_con_driver.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_register_con_driver(const struct consw *csw, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a662b0)
Location: drivers/tty/vt/vt.c:4103
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
```
**Symbols:**

```
ffffffff81a662b0-ffffffff81a66494: do_register_con_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_register_con_driver(const struct consw *csw, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab0a50)
Location: drivers/tty/vt/vt.c:4052
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
```
**Symbols:**

```
ffffffff81ab0a50-ffffffff81ab0c34: do_register_con_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_register_con_driver(const struct consw *csw, int first, int last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b036b0)
Location: drivers/tty/vt/vt.c:4052
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
```
**Symbols:**

```
ffffffff81b036b0-ffffffff81b03894: do_register_con_driver (STB_LOCAL)
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
In drivers/tty/vt/vt.c (ffff800010873a98)
Location: drivers/tty/vt/vt.c:4001
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (c0976794)
Location: drivers/tty/vt/vt.c:4001
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (c0000000009148e0)
Location: drivers/tty/vt/vt.c:4001
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffe000545440)
Location: drivers/tty/vt/vt.c:4001
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffff81661cb5)
Location: drivers/tty/vt/vt.c:4001
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffff81642035)
Location: drivers/tty/vt/vt.c:4001
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffff81690095)
Location: drivers/tty/vt/vt.c:4001
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
In drivers/tty/vt/vt.c (ffffffff816aa695)
Location: drivers/tty/vt/vt.c:4001
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_take_over_console
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
