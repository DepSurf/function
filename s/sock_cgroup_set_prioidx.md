# Function: <code>sock_cgroup_set_prioidx</code>

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
In net/core/sock.c (ffffffff817676a7)
Location: include/linux/cgroup-defs.h:627
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817764e4)
Location: include/linux/cgroup-defs.h:627
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffff817aa2d7)
Location: include/linux/cgroup-defs.h:627
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
In net/core/sock.c (ffffffff817946af)
Location: include/linux/cgroup-defs.h:631
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817a3764)
Location: include/linux/cgroup-defs.h:631
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffff817d8e17)
Location: include/linux/cgroup-defs.h:631
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
In net/core/sock.c (ffffffff817b48ea)
Location: include/linux/cgroup-defs.h:654
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817c17ba)
Location: include/linux/cgroup-defs.h:654
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffff817f8047)
Location: include/linux/cgroup-defs.h:654
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
In net/core/sock.c (ffffffff8182cb4a)
Location: include/linux/cgroup-defs.h:774
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8183b1ca)
Location: include/linux/cgroup-defs.h:774
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffff81875907)
Location: include/linux/cgroup-defs.h:774
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
Location: include/linux/cgroup-defs.h:786
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818859e9)
Location: include/linux/cgroup-defs.h:786
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffff818c6f97)
Location: include/linux/cgroup-defs.h:786
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
Location: include/linux/cgroup-defs.h:795
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818a6119)
Location: include/linux/cgroup-defs.h:795
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffff818f0107)
Location: include/linux/cgroup-defs.h:795
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
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818f15ab)
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffff81941a77)
Location: include/linux/cgroup-defs.h:838
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
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819234fb)
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffff81976987)
Location: include/linux/cgroup-defs.h:838
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
In net/core/sock.c (ffffffff819e85ef)
Location: include/linux/cgroup-defs.h:835
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819f6ad9)
Location: include/linux/cgroup-defs.h:835
Inline: True
Inline callers:
  - net/core/scm.c:__scm_install_fd
```
```
In net/core/netprio_cgroup.c (ffffffff81a4b6c7)
Location: include/linux/cgroup-defs.h:835
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
In net/core/sock.c (ffffffff819e8267)
Location: include/linux/cgroup-defs.h:820
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netprio_cgroup.c (ffffffff81a51330)
Location: include/linux/cgroup-defs.h:820
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
In net/core/sock.c (ffffffff819ce3a5)
Location: include/linux/cgroup-defs.h:820
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netprio_cgroup.c (ffffffff81a36ba0)
Location: include/linux/cgroup-defs.h:820
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff81a7dc6a)
Location: include/linux/cgroup-defs.h:789
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netprio_cgroup.c (ffffffff81aec97e)
Location: include/linux/cgroup-defs.h:789
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff81bf256c)
Location: include/linux/cgroup-defs.h:790
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netprio_cgroup.c (ffffffff81c6f49e)
Location: include/linux/cgroup-defs.h:790
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff81d9e6fc)
Location: include/linux/cgroup-defs.h:818
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netprio_cgroup.c (ffffffff81e272be)
Location: include/linux/cgroup-defs.h:818
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff81e0cf0c)
Location: include/linux/cgroup-defs.h:818
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netprio_cgroup.c (ffffffff81e9c82e)
Location: include/linux/cgroup-defs.h:818
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
In net/core/sock.c (ffffffff81ec989c)
Location: include/linux/cgroup-defs.h:854
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netprio_cgroup.c (ffffffff81f5efce)
Location: include/linux/cgroup-defs.h:854
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
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
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffff800010bbe5e4)
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffff800010c1d394)
Location: include/linux/cgroup-defs.h:838
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
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c0cda120)
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (c0d34fb4)
Location: include/linux/cgroup-defs.h:838
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
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c000000000c979d0)
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (c000000000d0e230)
Location: include/linux/cgroup-defs.h:838
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
In net/core/sock.c (ffffffe00073eb94)
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffe00074c3c4)
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffe000796dca)
Location: include/linux/cgroup-defs.h:838
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
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818c34fb)
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffff819167f7)
Location: include/linux/cgroup-defs.h:838
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
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8187d43b)
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffff818d05a7)
Location: include/linux/cgroup-defs.h:838
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
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819144fb)
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffff81967987)
Location: include/linux/cgroup-defs.h:838
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
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff81935639)
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netprio_cgroup.c (ffffffff81989cc7)
Location: include/linux/cgroup-defs.h:838
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:update_netprio
```
</details>
</li>
</ul>

## Differences
