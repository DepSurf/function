# Function: <code>throtl_start_new_slice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void throtl_start_new_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff813da1a0)
Location: block/blk-throttle.c:572
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
**Symbols:**

```
ffffffff813da1a0-ffffffff813da3b5: throtl_start_new_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void throtl_start_new_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8141fe70)
Location: block/blk-throttle.c:566
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff8141fe70-ffffffff8142001e: throtl_start_new_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void throtl_start_new_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8143afe0)
Location: block/blk-throttle.c:566
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff8143afe0-ffffffff8143b145: throtl_start_new_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void throtl_start_new_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81448f90)
Location: block/blk-throttle.c:792
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff81448f90-ffffffff81449111: throtl_start_new_slice (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff814769a4)
Location: block/blk-throttle.c:790
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
In block/blk-throttle.c (ffffffff814aaee8)
Location: block/blk-throttle.c:788
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
In block/blk-throttle.c (ffffffff814c52e3)
Location: block/blk-throttle.c:779
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
In block/blk-throttle.c (ffffffff814f3af8)
Location: block/blk-throttle.c:779
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
In block/blk-throttle.c (ffffffff8150d1c9)
Location: block/blk-throttle.c:781
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_may_dispatch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void throtl_start_new_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8156f449)
Location: block/blk-throttle.c:799
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff8156c780-ffffffff8156c89b: throtl_start_new_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void throtl_start_new_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8158a23b)
Location: block/blk-throttle.c:796
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff815886b0-ffffffff815887ee: throtl_start_new_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void throtl_start_new_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81590d39)
Location: block/blk-throttle.c:796
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff8158f300-ffffffff8158f43e: throtl_start_new_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void throtl_start_new_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815f7d4e)
Location: block/blk-throttle.c:801
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff815f5590-ffffffff815f5855: throtl_start_new_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void throtl_start_new_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff816a931b)
Location: block/blk-throttle.c:659
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff816a6ca0-ffffffff816a6f3f: throtl_start_new_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void throtl_start_new_slice(struct throtl_grp *tg, bool rw, bool clear_carryover);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81768539)
Location: block/blk-throttle.c:658
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff81765ca0-ffffffff81765fae: throtl_start_new_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void throtl_start_new_slice(struct throtl_grp *tg, bool rw, bool clear_carryover);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817a769c)
Location: block/blk-throttle.c:657
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff817a4d70-ffffffff817a507e: throtl_start_new_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void throtl_start_new_slice(struct throtl_grp *tg, bool rw, bool clear_carryover);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817eb426)
Location: block/blk-throttle.c:657
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff817e8940-ffffffff817e8c4e: throtl_start_new_slice (STB_LOCAL)
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
In block/blk-throttle.c (ffff800010610f7c)
Location: block/blk-throttle.c:781
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
In block/blk-throttle.c (c07bb5b4)
Location: block/blk-throttle.c:781
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
In block/blk-throttle.c (c0000000007aea44)
Location: block/blk-throttle.c:781
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
In block/blk-throttle.c (ffffffe000448940)
Location: block/blk-throttle.c:781
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
In block/blk-throttle.c (ffffffff815057a9)
Location: block/blk-throttle.c:781
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
In block/blk-throttle.c (ffffffff814f5c69)
Location: block/blk-throttle.c:781
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
In block/blk-throttle.c (ffffffff81501839)
Location: block/blk-throttle.c:781
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
In block/blk-throttle.c (ffffffff8151aace)
Location: block/blk-throttle.c:781
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool clear_carryover</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
