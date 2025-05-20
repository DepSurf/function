# Function: <code>throtl_downgrade_state</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff81449f90)
Location: block/blk-throttle.c:1924
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
```
**Symbols:**

```
ffffffff81449f90-ffffffff8144a0d4: throtl_downgrade_state.constprop.26 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff81478679)
Location: block/blk-throttle.c:1922
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff814acd41)
Location: block/blk-throttle.c:1931
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff814c70de)
Location: block/blk-throttle.c:1917
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff814f5944)
Location: block/blk-throttle.c:1914
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff8150f044)
Location: block/blk-throttle.c:1916
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff8156d610)
Location: block/blk-throttle.c:1960
Inline: True
Direct callers:
  - block/blk-throttle.c:throtl_downgrade_check
```
**Symbols:**

```
ffffffff8156d610-ffffffff8156d6fd: throtl_downgrade_state.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void throtl_downgrade_state(struct throtl_data *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81588280)
Location: block/blk-throttle.c:1974
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_downgrade_check
```
**Symbols:**

```
ffffffff81588280-ffffffff8158838a: throtl_downgrade_state (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff81591f33)
Location: block/blk-throttle.c:1974
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff815f671b)
Location: block/blk-throttle.c:1985
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_downgrade_check
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
In block/blk-throttle.c (ffffffff816a7e0e)
Location: block/blk-throttle.c:1886
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_downgrade_check
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In block/blk-throttle.c (ffff800010612c4c)
Location: block/blk-throttle.c:1916
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (c07bcf00)
Location: block/blk-throttle.c:1916
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_downgrade_check
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
In block/blk-throttle.c (c0000000007b1284)
Location: block/blk-throttle.c:1916
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffe00044a214)
Location: block/blk-throttle.c:1916
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff81507624)
Location: block/blk-throttle.c:1916
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff814f7ade)
Location: block/blk-throttle.c:1916
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff815036b4)
Location: block/blk-throttle.c:1916
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff8151cb8a)
Location: block/blk-throttle.c:1916
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
