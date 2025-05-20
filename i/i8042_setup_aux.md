# Function: <code>i8042_setup_aux</code>

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
Location: drivers/input/serio/i8042.c:1401
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
Location: drivers/input/serio/i8042.c:1388
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
Location: drivers/input/serio/i8042.c:1421
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
Location: drivers/input/serio/i8042.c:1429
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
Location: drivers/input/serio/i8042.c:1429
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
Location: drivers/input/serio/i8042.c:1429
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
Location: drivers/input/serio/i8042.c:1443
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
Location: drivers/input/serio/i8042.c:1436
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
Location: drivers/input/serio/i8042.c:1442
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
int i8042_setup_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff82d23bbf)
Location: drivers/input/serio/i8042.c:1445
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff82d23bbf-ffffffff82d23d15: i8042_setup_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int i8042_setup_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff83011c13)
Location: drivers/input/serio/i8042.c:1468
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff83011c13-ffffffff83011d68: i8042_setup_aux (STB_LOCAL)
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
In drivers/input/serio/i8042.c (ffffffff8321cd64)
Location: drivers/input/serio/i8042.c:1468
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i8042_setup_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1472
Inline: False
```
**Symbols:**

```
ffffffff819b3690-ffffffff819b37f0: i8042_setup_aux (STB_LOCAL)
ffffffff81d22ed4-ffffffff81d22f6b: i8042_setup_aux.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i8042_setup_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1472
Inline: False
```
**Symbols:**

```
ffffffff81b12860-ffffffff81b129dd: i8042_setup_aux (STB_LOCAL)
ffffffff81eeec56-ffffffff81eeeced: i8042_setup_aux.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int i8042_setup_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1472
Inline: False
```
**Symbols:**

```
ffffffff81ca3620-ffffffff81ca3856: i8042_setup_aux (STB_LOCAL)
ffffffff820a65e0-ffffffff820a6608: i8042_setup_aux.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int i8042_setup_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1472
Inline: False
```
**Symbols:**

```
ffffffff81d0ace0-ffffffff81d0af14: i8042_setup_aux (STB_LOCAL)
ffffffff821279e7-ffffffff82127a0f: i8042_setup_aux.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int i8042_setup_aux();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1472
Inline: False
```
**Symbols:**

```
ffffffff81dc0970-ffffffff81dc0ba4: i8042_setup_aux (STB_LOCAL)
ffffffff82209368-ffffffff82209390: i8042_setup_aux.cold (STB_LOCAL)
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
Location: drivers/input/serio/i8042.c:1442
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
Location: drivers/input/serio/i8042.c:1442
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
Location: drivers/input/serio/i8042.c:1442
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
Location: drivers/input/serio/i8042.c:1442
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
Location: drivers/input/serio/i8042.c:1442
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
