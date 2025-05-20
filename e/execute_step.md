# Function: <code>execute_step</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff814fe320)
Location: block/sed-opal.c:382
Inline: True
Direct callers:
  - block/sed-opal.c:init_opal_dev
```
**Symbols:**

```
ffffffff814fe320-ffffffff814fe39a: execute_step.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8151c270)
Location: block/sed-opal.c:379
Inline: True
Direct callers:
  - block/sed-opal.c:init_opal_dev
```
**Symbols:**

```
ffffffff8151c270-ffffffff8151c2ea: execute_step.isra.0 (STB_LOCAL)
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
In block/sed-opal.c (ffffffff8157eab6)
Location: block/sed-opal.c:381
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
In block/sed-opal.c (ffffffff8159baf6)
Location: block/sed-opal.c:381
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
In block/sed-opal.c (ffffffff815a25e6)
Location: block/sed-opal.c:381
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
In block/sed-opal.c (ffffffff8160aeba)
Location: block/sed-opal.c:381
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
In block/sed-opal.c (ffffffff816beddf)
Location: block/sed-opal.c:381
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
In block/sed-opal.c (ffffffff817804e2)
Location: block/sed-opal.c:412
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
int execute_step(struct opal_dev *dev, const struct opal_step *step, size_t stepIndex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817bfa7b)
Location: block/sed-opal.c:418
Inline: True
Inline callers:
  - block/sed-opal.c:init_opal_dev
```
**Symbols:**

```
ffffffff817bce40-ffffffff817bcf06: execute_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int execute_step(struct opal_dev *dev, const struct opal_step *step, size_t stepIndex);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81806b62)
Location: block/sed-opal.c:519
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
  - block/sed-opal.c:init_opal_dev
```
**Symbols:**

```
ffffffff81801500-ffffffff818015c6: execute_step (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffff8000106245c0)
Location: block/sed-opal.c:379
Inline: True
Direct callers:
  - block/sed-opal.c:init_opal_dev
```
**Symbols:**

```
ffff8000106245c0-ffff800010624670: execute_step.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int execute_step(struct opal_dev *dev, const struct opal_step *step, size_t stepIndex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07cbaa8)
Location: block/sed-opal.c:379
Inline: False
Direct callers:
  - block/sed-opal.c:init_opal_dev
```
**Symbols:**

```
c07cbaa8-c07cbb58: execute_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (c0000000007c5760)
Location: block/sed-opal.c:379
Inline: True
Direct callers:
  - block/sed-opal.c:init_opal_dev
```
**Symbols:**

```
c0000000007c5760-c0000000007c5838: execute_step.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffe000456046)
Location: block/sed-opal.c:379
Inline: True
Direct callers:
  - block/sed-opal.c:init_opal_dev
```
**Symbols:**

```
ffffffe000456046-ffffffe0004560ec: execute_step.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81514850)
Location: block/sed-opal.c:379
Inline: True
Direct callers:
  - block/sed-opal.c:init_opal_dev
```
**Symbols:**

```
ffffffff81514850-ffffffff815148ca: execute_step.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81504b60)
Location: block/sed-opal.c:379
Inline: True
Direct callers:
  - block/sed-opal.c:init_opal_dev
```
**Symbols:**

```
ffffffff81504b60-ffffffff81504bda: execute_step.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff815108e0)
Location: block/sed-opal.c:379
Inline: True
Direct callers:
  - block/sed-opal.c:init_opal_dev
```
**Symbols:**

```
ffffffff815108e0-ffffffff8151095a: execute_step.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8152a0a0)
Location: block/sed-opal.c:379
Inline: True
Direct callers:
  - block/sed-opal.c:init_opal_dev
```
**Symbols:**

```
ffffffff8152a0a0-ffffffff8152a11a: execute_step.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
