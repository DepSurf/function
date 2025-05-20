# Function: <code>sock_cgroup_prioidx</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817676ae)
Location: include/linux/cgroup-defs.h:611
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817764eb)
Location: include/linux/cgroup-defs.h:611
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff8178555e)
Location: include/linux/cgroup-defs.h:611
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff817aa2de)
Location: include/linux/cgroup-defs.h:611
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff817946b6)
Location: include/linux/cgroup-defs.h:615
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817a376b)
Location: include/linux/cgroup-defs.h:615
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff817b2b6e)
Location: include/linux/cgroup-defs.h:615
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff817d8e1e)
Location: include/linux/cgroup-defs.h:615
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff817b48f1)
Location: include/linux/cgroup-defs.h:638
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817c185f)
Location: include/linux/cgroup-defs.h:638
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff817d037d)
Location: include/linux/cgroup-defs.h:638
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff817f804e)
Location: include/linux/cgroup-defs.h:638
Inline: True
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
In net/core/sock.c (ffffffff8182cb51)
Location: include/linux/cgroup-defs.h:758
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8183b263)
Location: include/linux/cgroup-defs.h:758
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81849cea)
Location: include/linux/cgroup-defs.h:758
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff8187590e)
Location: include/linux/cgroup-defs.h:758
Inline: True
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
In net/core/sock.c (ffffffff8187769b)
Location: include/linux/cgroup-defs.h:770
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818859e9)
Location: include/linux/cgroup-defs.h:770
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81893ee6)
Location: include/linux/cgroup-defs.h:770
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff818c6f9e)
Location: include/linux/cgroup-defs.h:770
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff81897aeb)
Location: include/linux/cgroup-defs.h:779
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818a6119)
Location: include/linux/cgroup-defs.h:779
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818b48d6)
Location: include/linux/cgroup-defs.h:779
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff818f010e)
Location: include/linux/cgroup-defs.h:779
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff818e200f)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818f15ab)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81901209)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff81941a7e)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff819141df)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819234fb)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81933539)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff8197698e)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff819e85f6)
Location: include/linux/cgroup-defs.h:819
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819f6ae0)
Location: include/linux/cgroup-defs.h:819
Inline: True
Inline callers:
  - net/core/scm.c:__scm_install_fd
```
```
In net/core/dev.c (ffffffff81a083a2)
Location: include/linux/cgroup-defs.h:819
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff81a4b6ce)
Location: include/linux/cgroup-defs.h:819
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff819e826f)
Location: include/linux/cgroup-defs.h:804
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff81a09931)
Location: include/linux/cgroup-defs.h:804
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff81a51337)
Location: include/linux/cgroup-defs.h:804
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff819ce3ad)
Location: include/linux/cgroup-defs.h:804
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/dev.c (ffffffff819f02a8)
Location: include/linux/cgroup-defs.h:804
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff81a36bac)
Location: include/linux/cgroup-defs.h:804
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/dev.c (ffffffff81aa16d8)
Location: include/linux/cgroup-defs.h:771
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff81c19715)
Location: include/linux/cgroup-defs.h:772
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff81dca755)
Location: include/linux/cgroup-defs.h:800
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff81e3b2d5)
Location: include/linux/cgroup-defs.h:800
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/dev.c (ffffffff81ef968f)
Location: include/linux/cgroup-defs.h:836
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
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
In net/core/sock.c (ffff800010bab1a8)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffff800010bbe5e4)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffff800010bd1640)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffff800010c1d398)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (c0cc9c74)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c0cda124)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (c0cec27c)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (c0d34fbc)
Location: include/linux/cgroup-defs.h:822
Inline: True
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
In net/core/sock.c (c000000000c819a4)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c000000000c979d0)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (c000000000caf9dc)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (c000000000d0e234)
Location: include/linux/cgroup-defs.h:822
Inline: True
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
In net/core/sock.c (ffffffe00073eb9c)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffe00074c558)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffe00075bb04)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffe000796dce)
Location: include/linux/cgroup-defs.h:822
Inline: True
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
In net/core/sock.c (ffffffff818b41df)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818c34fb)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff818d3539)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff819167fe)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff8186e12f)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8187d43b)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff8188d3c9)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff818d05ae)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff819051df)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819144fb)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff81924539)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff8196798e)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff81926290)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff81935639)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/dev.c (ffffffff819459c9)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/netprio_cgroup.c (ffffffff81989cce)
Location: include/linux/cgroup-defs.h:822
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
```
</details>
</li>
</ul>

## Differences
