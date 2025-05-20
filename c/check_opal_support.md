# Function: <code>check_opal_support</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8145abdd)
Location: block/sed-opal.c:1968
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff8148697d)
Location: block/sed-opal.c:1980
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff814bb8aa)
Location: block/sed-opal.c:1997
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff814cfc6a)
Location: block/sed-opal.c:1997
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff814fe42a)
Location: block/sed-opal.c:1978
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff8151c37a)
Location: block/sed-opal.c:1990
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff8157ea97)
Location: block/sed-opal.c:2105
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff8159bad7)
Location: block/sed-opal.c:2105
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff815a25c7)
Location: block/sed-opal.c:2105
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff8160ae9b)
Location: block/sed-opal.c:2105
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff816bedc2)
Location: block/sed-opal.c:2105
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff817804bb)
Location: block/sed-opal.c:2145
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
  - block/sed-opal.c:init_opal_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int check_opal_support(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817bfa5e)
Location: block/sed-opal.c:2335
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
Direct callers:
  - block/sed-opal.c:sed_ioctl
  - block/sed-opal.c:sed_ioctl
```
**Symbols:**

```
ffffffff817bf8c0-ffffffff817bf987: check_opal_support (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int check_opal_support(struct opal_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff818043fb)
Location: block/sed-opal.c:2472
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
Direct callers:
  - block/sed-opal.c:sed_ioctl
  - block/sed-opal.c:sed_ioctl
```
**Symbols:**

```
ffffffff818041d0-ffffffff81804297: check_opal_support (STB_LOCAL)
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
In block/sed-opal.c (ffff8000106246f0)
Location: block/sed-opal.c:1990
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (c07cbbe8)
Location: block/sed-opal.c:1990
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (c0000000007c58dc)
Location: block/sed-opal.c:1990
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffe00045615a)
Location: block/sed-opal.c:1990
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff8151495a)
Location: block/sed-opal.c:1990
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff81504c6a)
Location: block/sed-opal.c:1990
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff815109ea)
Location: block/sed-opal.c:1990
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
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
In block/sed-opal.c (ffffffff8152a1aa)
Location: block/sed-opal.c:1990
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
