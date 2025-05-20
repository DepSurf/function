# Function: <code>blk_mq_update_dispatch_busy</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff814aa7e1)
Location: block/blk-mq.c:1172
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814a7c00-ffffffff814a7c3a: blk_mq_update_dispatch_busy.part.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff814d82ab)
Location: block/blk-mq.c:1170
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814d5cc0-ffffffff814d5cfa: blk_mq_update_dispatch_busy.part.0 (STB_LOCAL)
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
In block/blk-mq.c (ffffffff814f165d)
Location: block/blk-mq.c:1186
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814eeff0-ffffffff814ef02a: blk_mq_update_dispatch_busy.part.0 (STB_LOCAL)
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
In block/blk-mq.c (ffffffff8154fdf2)
Location: block/blk-mq.c:1155
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff8156c45b)
Location: block/blk-mq.c:1245
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff81573bdc)
Location: block/blk-mq.c:1203
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff815da5fc)
Location: block/blk-mq.c:1209
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff81687f35)
Location: block/blk-mq.c:1738
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff81746305)
Location: block/blk-mq.c:1904
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff8177f15d)
Location: block/blk-mq.c:1897
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_issue_directly
  - block/blk-mq.c:__blk_mq_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff817c107d)
Location: block/blk-mq.c:1915
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_issue_directly
  - block/blk-mq.c:__blk_mq_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffff8000105f0d18)
Location: block/blk-mq.c:1186
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffff8000105ed5c8-ffff8000105ed624: blk_mq_update_dispatch_busy.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (c079cd48)
Location: block/blk-mq.c:1186
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
c079a4a8-c079a4f0: blk_mq_update_dispatch_busy.part.0 (STB_LOCAL)
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
In block/blk-mq.c (c0000000007878a4)
Location: block/blk-mq.c:1186
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffe00042fa06)
Location: block/blk-mq.c:1186
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814e9c3d)
Location: block/blk-mq.c:1186
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814e75d0-ffffffff814e760a: blk_mq_update_dispatch_busy.part.0 (STB_LOCAL)
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
In block/blk-mq.c (ffffffff814da19d)
Location: block/blk-mq.c:1186
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814d7b40-ffffffff814d7b7a: blk_mq_update_dispatch_busy.part.0 (STB_LOCAL)
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
In block/blk-mq.c (ffffffff814e5ccd)
Location: block/blk-mq.c:1186
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814e3660-ffffffff814e369a: blk_mq_update_dispatch_busy.part.0 (STB_LOCAL)
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
In block/blk-mq.c (ffffffff814fec5d)
Location: block/blk-mq.c:1186
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814fc760-ffffffff814fc79a: blk_mq_update_dispatch_busy.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
