# Function: <code>i8042_check_aux</code>

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
In drivers/input/serio/i8042.c (ffffffff81fb151d)
Location: drivers/input/serio/i8042.c:747
Inline: True
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
In drivers/input/serio/i8042.c (ffffffff81fde044)
Location: drivers/input/serio/i8042.c:747
Inline: True
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
In drivers/input/serio/i8042.c (ffffffff8201bc5b)
Location: drivers/input/serio/i8042.c:777
Inline: True
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
In drivers/input/serio/i8042.c (ffffffff820fe5d0)
Location: drivers/input/serio/i8042.c:785
Inline: True
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
In drivers/input/serio/i8042.c (ffffffff82707e75)
Location: drivers/input/serio/i8042.c:785
Inline: True
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
In drivers/input/serio/i8042.c (ffffffff827321d4)
Location: drivers/input/serio/i8042.c:785
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
In drivers/input/serio/i8042.c (ffffffff828eb6e9)
Location: drivers/input/serio/i8042.c:788
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
In drivers/input/serio/i8042.c (ffffffff82905c98)
Location: drivers/input/serio/i8042.c:781
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
In drivers/input/serio/i8042.c (ffffffff8290f6d3)
Location: drivers/input/serio/i8042.c:795
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int i8042_check_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff82d23942)
Location: drivers/input/serio/i8042.c:797
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
```
**Symbols:**

```
ffffffff82d23942-ffffffff82d23bbf: i8042_check_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int i8042_check_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff83011996)
Location: drivers/input/serio/i8042.c:820
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
```
**Symbols:**

```
ffffffff83011996-ffffffff83011c13: i8042_check_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int i8042_check_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8321c954)
Location: drivers/input/serio/i8042.c:820
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff8321c954-ffffffff8321cbd1: i8042_check_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i8042_check_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:824
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
```
**Symbols:**

```
ffffffff819b3390-ffffffff819b368d: i8042_check_aux (STB_LOCAL)
ffffffff81d22de2-ffffffff81d22ed4: i8042_check_aux.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i8042_check_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:824
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
```
**Symbols:**

```
ffffffff81b124d0-ffffffff81b12853: i8042_check_aux (STB_LOCAL)
ffffffff81eeeb1e-ffffffff81eeec56: i8042_check_aux.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int i8042_check_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:824
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
```
**Symbols:**

```
ffffffff81ca3200-ffffffff81ca360d: i8042_check_aux (STB_LOCAL)
ffffffff820a652c-ffffffff820a65e0: i8042_check_aux.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int i8042_check_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:824
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
```
**Symbols:**

```
ffffffff81d0a8c0-ffffffff81d0accd: i8042_check_aux (STB_LOCAL)
ffffffff82127933-ffffffff821279e7: i8042_check_aux.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int i8042_check_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:824
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_setup_aux
```
**Symbols:**

```
ffffffff81dc0550-ffffffff81dc095d: i8042_check_aux (STB_LOCAL)
ffffffff822092b4-ffffffff82209368: i8042_check_aux.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (c0000000013b327c)
Location: drivers/input/serio/i8042.c:795
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/input/serio/i8042.c (ffffffff828f6472)
Location: drivers/input/serio/i8042.c:795
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
In drivers/input/serio/i8042.c (ffffffff828ed8d9)
Location: drivers/input/serio/i8042.c:795
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
In drivers/input/serio/i8042.c (ffffffff8290a26a)
Location: drivers/input/serio/i8042.c:795
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
In drivers/input/serio/i8042.c (ffffffff82910735)
Location: drivers/input/serio/i8042.c:795
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
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
