# Function: <code>xfrm_aevent_is_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff817b73d6)
Location: include/net/xfrm.h:1672
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff817bc8c7)
Location: include/net/xfrm.h:1672
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81824409)
Location: include/net/xfrm.h:1670
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff818299ba)
Location: include/net/xfrm.h:1670
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81855d59)
Location: include/net/xfrm.h:1670
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff8185b38a)
Location: include/net/xfrm.h:1670
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff818799c9)
Location: include/net/xfrm.h:1740
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff8187f6a5)
Location: include/net/xfrm.h:1740
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff818fa420)
Location: include/net/xfrm.h:1743
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff819007cf)
Location: include/net/xfrm.h:1743
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819520f0)
Location: include/net/xfrm.h:1775
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff81957298)
Location: include/net/xfrm.h:1775
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81985390)
Location: include/net/xfrm.h:1781
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff8198beee)
Location: include/net/xfrm.h:1781
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819ef1bd)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff819f7493)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a2608d)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a2e0e3)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b1778d)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b2100d)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b25851)
Location: include/net/xfrm.h:1726
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b2f9e1)
Location: include/net/xfrm.h:1726
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b14431)
Location: include/net/xfrm.h:1727
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b1d6e8)
Location: include/net/xfrm.h:1727
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81bd83c1)
Location: include/net/xfrm.h:1749
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff81be262f)
Location: include/net/xfrm.h:1749
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81d6d059)
Location: include/net/xfrm.h:1752
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff81d7964a)
Location: include/net/xfrm.h:1752
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f384b9)
Location: include/net/xfrm.h:1826
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff81f460da)
Location: include/net/xfrm.h:1826
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f97ea9)
Location: include/net/xfrm.h:1832
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff81fa5a5f)
Location: include/net/xfrm.h:1832
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff82065219)
Location: include/net/xfrm.h:1834
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff82072daf)
Location: include/net/xfrm.h:1834
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffff800010ce4b20)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffff800010ced090)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (c0deb980)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (c0df4e6c)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (c000000000e05384)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (c000000000e11438)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffe000831de0)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffe00083a5c0)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819c571d)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff819cd773)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff8198250d)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff8198a563)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a3019d)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a381f3)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a3a6ef)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a44258)
Location: include/net/xfrm.h:1720
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
</ul>

## Differences
