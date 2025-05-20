# Function: <code>skb_frag_size_sub</code>

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
In net/core/skbuff.c (ffffffff8170934e)
Location: include/linux/skbuff.h:254
Inline: True
Inline callers:
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:254
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff817746bc)
Location: include/linux/skbuff.h:254
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff8176efe9)
Location: include/linux/skbuff.h:340
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:340
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff817e1588)
Location: include/linux/skbuff.h:340
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff8179c4d9)
Location: include/linux/skbuff.h:340
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:340
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81811a58)
Location: include/linux/skbuff.h:340
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff817bd423)
Location: include/linux/skbuff.h:343
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:343
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81831dec)
Location: include/linux/skbuff.h:343
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff818357f5)
Location: include/linux/skbuff.h:343
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:343
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff818b0faf)
Location: include/linux/skbuff.h:343
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff8187fd20)
Location: include/linux/skbuff.h:343
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff8188da97)
Location: include/linux/skbuff.h:343
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81906643)
Location: include/linux/skbuff.h:343
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff818a0991)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff818ae934)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff8193483d)
Location: include/linux/skbuff.h:345
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff818eb3ca)
Location: include/linux/skbuff.h:360
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff818fa222)
Location: include/linux/skbuff.h:360
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff8199850a)
Location: include/linux/skbuff.h:360
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff8191d52a)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff8192c362)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff819cf113)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff819efacf)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff819ff872)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81abbffa)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff819ef778)
Location: include/linux/skbuff.h:357
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff819ff5d2)
Location: include/linux/skbuff.h:357
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81ac773a)
Location: include/linux/skbuff.h:357
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff819d7f32)
Location: include/linux/skbuff.h:358
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff819e5d43)
Location: include/linux/skbuff.h:358
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81ab274a)
Location: include/linux/skbuff.h:358
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81a87d82)
Location: include/linux/skbuff.h:362
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff81a97f23)
Location: include/linux/skbuff.h:362
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f607)
Location: include/linux/skbuff.h:362
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81bfd1bd)
Location: include/linux/skbuff.h:573
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81c3f72e)
Location: include/linux/skbuff.h:573
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
```
```
In net/core/gro.c (ffffffff81c538e3)
Location: include/linux/skbuff.h:573
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/ipv4/tcp_output.c (ffffffff81cfecc6)
Location: include/linux/skbuff.h:573
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81dac131)
Location: include/linux/skbuff.h:396
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81df3c3e)
Location: include/linux/skbuff.h:396
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
```
```
In net/core/gro.c (ffffffff81e09093)
Location: include/linux/skbuff.h:396
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/ipv4/tcp_output.c (ffffffff81ec3cb2)
Location: include/linux/skbuff.h:396
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81e1bf78)
Location: include/linux/skbuff.h:399
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81e63619)
Location: include/linux/skbuff.h:399
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
```
```
In net/core/gro.c (ffffffff81e7b6e4)
Location: include/linux/skbuff.h:399
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/ipv4/tcp_output.c (ffffffff81f22c85)
Location: include/linux/skbuff.h:399
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff81ed9678)
Location: include/linux/skbuff.h:398
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/filter.c (ffffffff81f279ce)
Location: include/linux/skbuff.h:398
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_frags_shrink_tail
```
```
In net/core/gro.c (ffffffff81f3b974)
Location: include/linux/skbuff.h:398
Inline: True
Inline callers:
  - net/core/gro.c:gro_pull_from_frag0
  - net/core/gro.c:skb_gro_receive
  - net/core/gro.c:skb_gro_receive
```
```
In net/ipv4/tcp_output.c (ffffffff81fe7b15)
Location: include/linux/skbuff.h:398
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffff800010bb7ed4)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffff800010bcece8)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffff800010c81f40)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (c0cd4ab8)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (c0ce4a74)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (c0d90b04)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (c000000000c8fd64)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (c000000000ca5078)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (c000000000d8cd24)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffe000747808)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffe000755174)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffe0007e3a40)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff818bd52a)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff818cc362)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff8196ef83)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff8187746a)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff818863f2)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff81928a73)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff8190e52a)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff8191d362)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff819d9753)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
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
In net/core/skbuff.c (ffffffff8192f65a)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_gro_receive
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:__pskb_pull_tail
```
```
In net/core/dev.c (ffffffff8193e882)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/ipv4/tcp_output.c (ffffffff819e33b3)
Location: include/linux/skbuff.h:355
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
</details>
</li>
</ul>

## Differences
