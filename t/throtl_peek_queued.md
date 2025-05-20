# Function: <code>throtl_peek_queued</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bio *throtl_peek_queued(struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff813d9380)
Location: block/blk-throttle.c:264
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_may_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
```
**Symbols:**

```
ffffffff813d9380-ffffffff813d93cd: throtl_peek_queued (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bio *throtl_peek_queued(struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8141f190)
Location: block/blk-throttle.c:258
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff8141f190-ffffffff8141f1e1: throtl_peek_queued (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bio *throtl_peek_queued(struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8143a750)
Location: block/blk-throttle.c:258
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff8143a750-ffffffff8143a7a1: throtl_peek_queued (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff8144b452)
Location: block/blk-throttle.c:424
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bio *throtl_peek_queued(struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81474fc0)
Location: block/blk-throttle.c:423
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff81474fc0-ffffffff81474fe6: throtl_peek_queued (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bio *throtl_peek_queued(struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814a9310)
Location: block/blk-throttle.c:421
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff814a9310-ffffffff814a9335: throtl_peek_queued (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bio *throtl_peek_queued(struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814c3720)
Location: block/blk-throttle.c:420
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff814c3720-ffffffff814c3745: throtl_peek_queued (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bio *throtl_peek_queued(struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f1dc0)
Location: block/blk-throttle.c:420
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
ffffffff814f1dc0-ffffffff814f1de7: throtl_peek_queued (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff8150e7cd)
Location: block/blk-throttle.c:420
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff8156e40c)
Location: block/blk-throttle.c:424
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_dispatch_tg
  - block/blk-throttle.c:throtl_dispatch_tg
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff81589940)
Location: block/blk-throttle.c:424
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_dispatch_tg
  - block/blk-throttle.c:throtl_dispatch_tg
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff81590392)
Location: block/blk-throttle.c:424
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff815f7315)
Location: block/blk-throttle.c:427
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
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
In block/blk-throttle.c (ffffffff816aa0aa)
Location: block/blk-throttle.c:275
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff81767f5f)
Location: block/blk-throttle.c:275
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff817a70f2)
Location: block/blk-throttle.c:275
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff817eae6f)
Location: block/blk-throttle.c:275
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffff800010612464)
Location: block/blk-throttle.c:420
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bio *throtl_peek_queued(struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c07b9a14)
Location: block/blk-throttle.c:420
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_may_dispatch
```
**Symbols:**

```
c07b9a14-c07b9a8c: throtl_peek_queued (STB_LOCAL)
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
In block/blk-throttle.c (c0000000007b0844)
Location: block/blk-throttle.c:420
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffe000449b50)
Location: block/blk-throttle.c:420
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff81506dad)
Location: block/blk-throttle.c:420
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff814f726d)
Location: block/blk-throttle.c:420
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff81502e3d)
Location: block/blk-throttle.c:420
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff8151c2cd)
Location: block/blk-throttle.c:420
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
