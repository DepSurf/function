# Function: <code>dev_xmit_recursion_inc</code>

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
In net/core/dev.c (ffffffff81901879)
Location: include/linux/netdevice.h:3040
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81929883)
Location: include/linux/netdevice.h:3040
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff81933b95)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8195beef)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff81a07f4d)
Location: include/linux/netdevice.h:3167
Inline: True
Inline callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81a31124)
Location: include/linux/netdevice.h:3167
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
In net/core/dev.c (ffffffff81a0966b)
Location: include/linux/netdevice.h:3321
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81a335b4)
Location: include/linux/netdevice.h:3321
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
In net/core/dev.c (ffffffff819effdb)
Location: include/linux/netdevice.h:3388
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81a1a35d)
Location: include/linux/netdevice.h:3388
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
In net/core/dev.c (ffffffff81aa140b)
Location: include/linux/netdevice.h:3400
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81ac7714)
Location: include/linux/netdevice.h:3400
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
In net/core/dev.c (ffffffff81c192cf)
Location: include/linux/netdevice.h:3191
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81c43f92)
Location: include/linux/netdevice.h:3191
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
In net/core/dev.c (ffffffff81dca2cf)
Location: include/linux/netdevice.h:3216
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81df82e2)
Location: include/linux/netdevice.h:3216
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
In net/core/dev.c (ffffffff81e3ae4f)
Location: include/linux/netdevice.h:3279
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81e69954)
Location: include/linux/netdevice.h:3279
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
In net/core/dev.c (ffffffff81ef91da)
Location: include/linux/netdevice.h:3358
Inline: True
Inline callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81f28fc1)
Location: include/linux/netdevice.h:3358
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
In net/core/dev.c (ffff800010bd1c74)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffff800010c0145c)
Location: include/linux/netdevice.h:3053
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
In net/core/dev.c (c0cec9e8)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (c0d1856c)
Location: include/linux/netdevice.h:3053
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
In net/core/dev.c (c000000000cafce0)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (c000000000ce8ed8)
Location: include/linux/netdevice.h:3053
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
In net/core/dev.c (ffffffe00075bcee)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffe00077ff0c)
Location: include/linux/netdevice.h:3053
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
In net/core/dev.c (ffffffff818d3b95)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818fbebf)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff8188da25)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818b5cef)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff81924b95)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8194ceef)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
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
In net/core/dev.c (ffffffff81946054)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8196e8af)
Location: include/linux/netdevice.h:3053
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
</ul>

## Differences
