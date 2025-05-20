# Function: <code>throtl_rb_first</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct throtl_grp *throtl_rb_first(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff813d95a0)
Location: block/blk-throttle.c:410
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
```
**Symbols:**

```
ffffffff813d95a0-ffffffff813d95e2: throtl_rb_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct throtl_grp *throtl_rb_first(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8141f3c0)
Location: block/blk-throttle.c:404
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff8141f3c0-ffffffff8141f402: throtl_rb_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct throtl_grp *throtl_rb_first(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8143a980)
Location: block/blk-throttle.c:404
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff8143a980-ffffffff8143a9c2: throtl_rb_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct throtl_grp *throtl_rb_first(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81448630)
Location: block/blk-throttle.c:619
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
```
**Symbols:**

```
ffffffff81448630-ffffffff81448672: throtl_rb_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct throtl_grp *throtl_rb_first(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814751e0)
Location: block/blk-throttle.c:617
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
```
**Symbols:**

```
ffffffff814751e0-ffffffff81475222: throtl_rb_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct throtl_grp *throtl_rb_first(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814a9660)
Location: block/blk-throttle.c:615
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
```
**Symbols:**

```
ffffffff814a9660-ffffffff814a96a3: throtl_rb_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff814c42a0)
Location: block/blk-throttle.c:616
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
```
**Symbols:**

```
ffffffff814c42a0-ffffffff814c42c0: throtl_rb_first.isra.17 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff814f2a00)
Location: block/blk-throttle.c:616
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
```
**Symbols:**

```
ffffffff814f2a00-ffffffff814f2a22: throtl_rb_first.isra.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff8150e79a)
Location: block/blk-throttle.c:618
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff8156ec9e)
Location: block/blk-throttle.c:636
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff81589a52)
Location: block/blk-throttle.c:644
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff81590354)
Location: block/blk-throttle.c:644
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff815f72d0)
Location: block/blk-throttle.c:647
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff816aa060)
Location: block/blk-throttle.c:507
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_schedule_next_dispatch
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
In block/blk-throttle.c (ffffffff81767f23)
Location: block/blk-throttle.c:501
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_schedule_next_dispatch
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
In block/blk-throttle.c (ffffffff817a70b6)
Location: block/blk-throttle.c:500
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_schedule_next_dispatch
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
In block/blk-throttle.c (ffffffff817eae33)
Location: block/blk-throttle.c:500
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_schedule_next_dispatch
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
In block/blk-throttle.c (ffff800010612444)
Location: block/blk-throttle.c:618
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct throtl_grp *throtl_rb_first(struct throtl_service_queue *parent_sq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c07b99a4)
Location: block/blk-throttle.c:618
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
```
**Symbols:**

```
c07b99a4-c07b9a14: throtl_rb_first (STB_LOCAL)
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
In block/blk-throttle.c (c0000000007b0800)
Location: block/blk-throttle.c:618
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffe000449b34)
Location: block/blk-throttle.c:618
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff81506d7a)
Location: block/blk-throttle.c:618
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff814f723a)
Location: block/blk-throttle.c:618
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff81502e0a)
Location: block/blk-throttle.c:618
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff8151c29a)
Location: block/blk-throttle.c:618
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
