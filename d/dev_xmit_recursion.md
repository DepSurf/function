# Function: <code>dev_xmit_recursion</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819013a0)
Location: include/linux/netdevice.h:3034
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff819298a2)
Location: include/linux/netdevice.h:3034
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/dev.c (ffffffff819336d0)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8195bf0b)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/dev.c (ffffffff81a0843c)
Location: include/linux/netdevice.h:3161
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81a31101)
Location: include/linux/netdevice.h:3161
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/dev.c (ffffffff81a099d0)
Location: include/linux/netdevice.h:3315
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81a33591)
Location: include/linux/netdevice.h:3315
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/dev.c (ffffffff819f033f)
Location: include/linux/netdevice.h:3382
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81a1a33a)
Location: include/linux/netdevice.h:3382
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/dev.c (ffffffff81aa1764)
Location: include/linux/netdevice.h:3394
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81ac75b3)
Location: include/linux/netdevice.h:3394
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/dev.c (ffffffff81c197a0)
Location: include/linux/netdevice.h:3185
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81c43e2f)
Location: include/linux/netdevice.h:3185
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/dev.c (ffffffff81dca7e0)
Location: include/linux/netdevice.h:3210
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81df817f)
Location: include/linux/netdevice.h:3210
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/dev.c (ffffffff81e3b360)
Location: include/linux/netdevice.h:3273
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81e697ef)
Location: include/linux/netdevice.h:3273
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/dev.c (ffffffff81ef97d0)
Location: include/linux/netdevice.h:3352
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81f28e5c)
Location: include/linux/netdevice.h:3352
Inline: True
Inline callers:
  - net/core/filter.c:bpf_out_neigh_v6
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/dev.c (ffff800010bd17b4)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffff800010c01438)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/dev.c (c0cec40c)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (c0d18548)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/dev.c (c000000000cafb7c)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (c000000000ce8eb0)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/dev.c (ffffffe00075bc30)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffe00077fede)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/dev.c (ffffffff818d36d0)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818fbedb)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/dev.c (ffffffff8188d560)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818b5d0b)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/dev.c (ffffffff819246d0)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8194cf0b)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/dev.c (ffffffff81945b60)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8196e8cb)
Location: include/linux/netdevice.h:3047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
</ul>

## Differences
