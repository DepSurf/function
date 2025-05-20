# Function: <code>throtl_dequeue_tg</code>

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
In block/blk-throttle.c (ffffffff813da723)
Location: block/blk-throttle.c:498
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_drain_bios
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
In block/blk-throttle.c (ffffffff814218c1)
Location: block/blk-throttle.c:492
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff8143c451)
Location: block/blk-throttle.c:492
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff8144b445)
Location: block/blk-throttle.c:707
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff81477ec1)
Location: block/blk-throttle.c:705
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff814ac541)
Location: block/blk-throttle.c:703
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff814c68f8)
Location: block/blk-throttle.c:694
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff814c42c0-ffffffff814c42fe: throtl_dequeue_tg.part.23 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff814f5138)
Location: block/blk-throttle.c:694
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff814f2a30-ffffffff814f2a94: throtl_dequeue_tg.part.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff8150e7b8)
Location: block/blk-throttle.c:696
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff8150bfb0-ffffffff8150c014: throtl_dequeue_tg.part.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff8156ecc0)
Location: block/blk-throttle.c:714
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff81589a70)
Location: block/blk-throttle.c:709
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff8159037e)
Location: block/blk-throttle.c:709
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff815f72ff)
Location: block/blk-throttle.c:712
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff816aa096)
Location: block/blk-throttle.c:572
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
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
In block/blk-throttle.c (ffffffff81768133)
Location: block/blk-throttle.c:565
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
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
In block/blk-throttle.c (ffffffff817a7292)
Location: block/blk-throttle.c:564
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
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
In block/blk-throttle.c (ffffffff817eb00f)
Location: block/blk-throttle.c:564
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
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
In block/blk-throttle.c (ffff800010612454)
Location: block/blk-throttle.c:696
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffff80001060fb68-ffff80001060fbe8: throtl_dequeue_tg.part.0 (STB_LOCAL)
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
In block/blk-throttle.c (c07bcc20)
Location: block/blk-throttle.c:696
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
c07ba26c-c07ba2e4: throtl_dequeue_tg.part.0 (STB_LOCAL)
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
In block/blk-throttle.c (c0000000007b0830)
Location: block/blk-throttle.c:696
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
c0000000007ad050-c0000000007ad0fc: throtl_dequeue_tg.part.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffe000449b48)
Location: block/blk-throttle.c:696
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffe000447a48-ffffffe000447abe: throtl_dequeue_tg.part.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff81506d98)
Location: block/blk-throttle.c:696
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff81504590-ffffffff815045f4: throtl_dequeue_tg.part.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff814f7258)
Location: block/blk-throttle.c:696
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff814f4a50-ffffffff814f4ab4: throtl_dequeue_tg.part.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff81502e28)
Location: block/blk-throttle.c:696
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff81500620-ffffffff81500684: throtl_dequeue_tg.part.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff8151c2b8)
Location: block/blk-throttle.c:696
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
Direct callers:
  - block/blk-throttle.c:tg_drain_bios
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff81519630-ffffffff81519694: throtl_dequeue_tg.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
