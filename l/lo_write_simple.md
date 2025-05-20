# Function: <code>lo_write_simple</code>

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
In drivers/block/loop.c (ffffffff81570f35)
Location: drivers/block/loop.c:283
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff815c6a03)
Location: drivers/block/loop.c:283
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff815f4f37)
Location: drivers/block/loop.c:283
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff81608fb1)
Location: drivers/block/loop.c:283
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff8167187a)
Location: drivers/block/loop.c:286
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816ad005)
Location: drivers/block/loop.c:288
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816cd1da)
Location: drivers/block/loop.c:289
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff81709308)
Location: drivers/block/loop.c:289
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff8172d671)
Location: drivers/block/loop.c:289
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff817e92d0)
Location: drivers/block/loop.c:301
Inline: True
Inline callers:
  - drivers/block/loop.c:do_req_filebacked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff817fd350)
Location: drivers/block/loop.c:298
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817fd350-ffffffff817fd49f: lo_write_simple.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff817e1ea0)
Location: drivers/block/loop.c:340
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817e1ea0-ffffffff817e1fef: lo_write_simple.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff8186d850)
Location: drivers/block/loop.c:330
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff8186d850-ffffffff8186d99f: lo_write_simple.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:263
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff819b6ba0-ffffffff819b6ebc: lo_write_simple.isra.0 (STB_LOCAL)
ffffffff81ece26a-ffffffff81ece293: lo_write_simple.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2be10)
Location: drivers/block/loop.c:263
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff81b2be10-ffffffff81b2c15f: lo_write_simple.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7c110)
Location: drivers/block/loop.c:263
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff81b7c110-ffffffff81b7c43d: lo_write_simple.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff81bd0140)
Location: drivers/block/loop.c:259
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff81bd0140-ffffffff81bd036d: lo_write_simple.isra.0 (STB_LOCAL)
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
In drivers/block/loop.c (ffff800010922d2c)
Location: drivers/block/loop.c:289
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (c0a08c1c)
Location: drivers/block/loop.c:289
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (c0000000009c9138)
Location: drivers/block/loop.c:289
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffe0005a1f14)
Location: drivers/block/loop.c:289
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816f3451)
Location: drivers/block/loop.c:289
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816cd551)
Location: drivers/block/loop.c:289
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff81720b31)
Location: drivers/block/loop.c:289
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff8173bef1)
Location: drivers/block/loop.c:289
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
</details>
</li>
</ul>

## Differences
