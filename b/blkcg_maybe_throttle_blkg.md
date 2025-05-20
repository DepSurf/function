# Function: <code>blkcg_maybe_throttle_blkg</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c3295)
Location: block/blk-cgroup.c:1644
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff814f1964)
Location: block/blk-cgroup.c:1629
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff8150af59)
Location: block/blk-cgroup.c:1692
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blkcg_maybe_throttle_blkg(struct blkcg_gq *blkg, bool use_memdelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156a370)
Location: block/blk-cgroup.c:1588
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff8156a370-ffffffff8156a487: blkcg_maybe_throttle_blkg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blkcg_maybe_throttle_blkg(struct blkcg_gq *blkg, bool use_memdelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81584dc0)
Location: block/blk-cgroup.c:1641
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
**Symbols:**

```
ffffffff81584dc0-ffffffff81584eeb: blkcg_maybe_throttle_blkg (STB_LOCAL)
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
In block/blk-cgroup.c (ffffffff8158da4c)
Location: block/blk-cgroup.c:1646
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff815f34bc)
Location: block/blk-cgroup.c:1640
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff816a4a3d)
Location: block/blk-cgroup.c:1734
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff817637cd)
Location: block/blk-cgroup.c:1739
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff817a286d)
Location: block/blk-cgroup.c:1832
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff817e63af)
Location: block/blk-cgroup.c:1845
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffff80001060e88c)
Location: block/blk-cgroup.c:1692
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (c07b909c)
Location: block/blk-cgroup.c:1692
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (c0000000007abdf0)
Location: block/blk-cgroup.c:1692
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffe000446d22)
Location: block/blk-cgroup.c:1692
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff81503539)
Location: block/blk-cgroup.c:1692
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff814f39f9)
Location: block/blk-cgroup.c:1692
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff814ff5c9)
Location: block/blk-cgroup.c:1692
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff81518774)
Location: block/blk-cgroup.c:1692
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
</ul>
