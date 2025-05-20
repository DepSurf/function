# Function: <code>gro_normal_list</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81935fd2)
Location: net/core/dev.c:5255
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
```
**Symbols:**

```
ffffffff81935610-ffffffff8193564b: gro_normal_list.part.0 (STB_LOCAL)
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
In net/core/dev.c (ffffffff81a0ab83)
Location: net/core/dev.c:5638
Inline: True
Inline callers:
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_receive
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
In net/core/dev.c (ffffffff81a0bd95)
Location: net/core/dev.c:5738
Inline: True
Inline callers:
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_receive
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
In net/core/dev.c (ffffffff819f2d85)
Location: net/core/dev.c:5862
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_receive
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
In net/core/dev.c (ffffffff81aa3bf5)
Location: net/core/dev.c:5832
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:napi_gro_receive
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
In net/core/dev.c (ffffffff81c1c5e4)
Location: include/net/gro.h:426
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_complete_done
```
```
In net/core/gro.c (ffffffff81c54698)
Location: include/net/gro.h:426
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
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
In net/core/dev.c (ffffffff81dcd600)
Location: include/net/gro.h:429
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_complete_done
```
```
In net/core/gro.c (ffffffff81e09de8)
Location: include/net/gro.h:429
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
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
In net/core/dev.c (ffffffff81e3e165)
Location: include/net/gro.h:435
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_complete_done
```
```
In net/core/gro.c (ffffffff81e7c5b2)
Location: include/net/gro.h:435
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
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
In net/core/dev.c (ffffffff81efca05)
Location: include/net/gro.h:435
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_complete_done
```
```
In net/core/gro.c (ffffffff81f3c902)
Location: include/net/gro.h:435
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
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
In net/core/dev.c (ffff800010bd4588)
Location: net/core/dev.c:5255
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
```
**Symbols:**

```
ffff800010bd3930-ffff800010bd396c: gro_normal_list.part.0 (STB_LOCAL)
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
In net/core/dev.c (c0cefd74)
Location: net/core/dev.c:5255
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
c0cee668-c0cee6a0: gro_normal_list.part.0 (STB_LOCAL)
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
In net/core/dev.c (c000000000cb3648)
Location: net/core/dev.c:5255
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
```
**Symbols:**

```
c000000000cb2600-c000000000cb265c: gro_normal_list.part.0 (STB_LOCAL)
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
In net/core/dev.c (ffffffe00075e3de)
Location: net/core/dev.c:5255
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
```
**Symbols:**

```
ffffffe00075dad0-ffffffe00075db0e: gro_normal_list.part.0 (STB_LOCAL)
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
In net/core/dev.c (ffffffff818d5fa2)
Location: net/core/dev.c:5255
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
```
**Symbols:**

```
ffffffff818d55e0-ffffffff818d561b: gro_normal_list.part.0 (STB_LOCAL)
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
In net/core/dev.c (ffffffff8188fdda)
Location: net/core/dev.c:5255
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
```
**Symbols:**

```
ffffffff8188f450-ffffffff8188f48b: gro_normal_list.part.0 (STB_LOCAL)
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
In net/core/dev.c (ffffffff81926fd2)
Location: net/core/dev.c:5255
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
```
**Symbols:**

```
ffffffff81926610-ffffffff8192664b: gro_normal_list.part.0 (STB_LOCAL)
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
In net/core/dev.c (ffffffff81948630)
Location: net/core/dev.c:5255
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_busy_loop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_complete
```
**Symbols:**

```
ffffffff81947bf0-ffffffff81947c2b: gro_normal_list.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
