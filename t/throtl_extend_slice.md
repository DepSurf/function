# Function: <code>throtl_extend_slice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void throtl_extend_slice(struct throtl_grp *tg, bool rw, long unsigned int jiffy_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff813d9f80)
Location: block/blk-throttle.c:590
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff813d9f80-ffffffff813da19b: throtl_extend_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void throtl_extend_slice(struct throtl_grp *tg, bool rw, long unsigned int jiffy_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8141fcc0)
Location: block/blk-throttle.c:584
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff8141fcc0-ffffffff8141fe6f: throtl_extend_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void throtl_extend_slice(struct throtl_grp *tg, bool rw, long unsigned int jiffy_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8143b150)
Location: block/blk-throttle.c:584
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff8143b150-ffffffff8143b2b3: throtl_extend_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void throtl_extend_slice(struct throtl_grp *tg, bool rw, long unsigned int jiffy_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81449320)
Location: block/blk-throttle.c:810
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff81449320-ffffffff81449477: throtl_extend_slice (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff814763b9)
Location: block/blk-throttle.c:808
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff814aa9f0)
Location: block/blk-throttle.c:806
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff814c4dd6)
Location: block/blk-throttle.c:797
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff814f358f)
Location: block/blk-throttle.c:797
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff8150cc1b)
Location: block/blk-throttle.c:799
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void throtl_extend_slice(struct throtl_grp *tg, bool rw, long unsigned int jiffy_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8156c8a0)
Location: block/blk-throttle.c:817
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff8156c8a0-ffffffff8156c9a2: throtl_extend_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void throtl_extend_slice(struct throtl_grp *tg, bool rw, long unsigned int jiffy_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81588390)
Location: block/blk-throttle.c:814
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff81588390-ffffffff815884b7: throtl_extend_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void throtl_extend_slice(struct throtl_grp *tg, bool rw, long unsigned int jiffy_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8158efe0)
Location: block/blk-throttle.c:814
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff8158efe0-ffffffff8158f107: throtl_extend_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void throtl_extend_slice(struct throtl_grp *tg, bool rw, long unsigned int jiffy_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815f51b0)
Location: block/blk-throttle.c:822
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff815f51b0-ffffffff815f5399: throtl_extend_slice (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff816a8bc3)
Location: block/blk-throttle.c:678
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff817678d1)
Location: block/blk-throttle.c:682
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff817a6a55)
Location: block/blk-throttle.c:681
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff817ea7d8)
Location: block/blk-throttle.c:681
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffff800010610a34)
Location: block/blk-throttle.c:799
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (c07bb0dc)
Location: block/blk-throttle.c:799
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (c0000000007ae4b4)
Location: block/blk-throttle.c:799
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffe0004484a2)
Location: block/blk-throttle.c:799
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff815051fb)
Location: block/blk-throttle.c:799
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff814f56bb)
Location: block/blk-throttle.c:799
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff8150128b)
Location: block/blk-throttle.c:799
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff8151a5a6)
Location: block/blk-throttle.c:799
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_may_dispatch
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
