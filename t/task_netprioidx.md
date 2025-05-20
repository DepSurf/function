# Function: <code>task_netprioidx</code>

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
In net/core/sock.c (ffffffff8170142b)
Location: include/net/netprio_cgroup.h:30
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81767690)
Location: include/net/netprio_cgroup.h:28
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817764c9)
Location: include/net/netprio_cgroup.h:28
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffff81794698)
Location: include/net/netprio_cgroup.h:28
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817a3749)
Location: include/net/netprio_cgroup.h:28
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffff817b48d6)
Location: include/net/netprio_cgroup.h:28
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817c1840)
Location: include/net/netprio_cgroup.h:28
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffff8182cb36)
Location: include/net/netprio_cgroup.h:28
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8183b248)
Location: include/net/netprio_cgroup.h:28
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffff8187767d)
Location: include/net/netprio_cgroup.h:28
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818859c9)
Location: include/net/netprio_cgroup.h:28
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffff81897acd)
Location: include/net/netprio_cgroup.h:28
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818a60f9)
Location: include/net/netprio_cgroup.h:28
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffff818e1ff0)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818f1589)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffff819141c0)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819234d9)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffff819e85e1)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819f6acb)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/scm.c:__scm_install_fd
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
In net/core/sock.c (ffffffff819e8253)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff819ce391)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81a7dc56)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81bf2558)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81d9e6e8)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81e0cef8)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81ec9888)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffff800010bab190)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffff800010bbe5cc)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (c0cc9c5c)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c0cda108)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (c000000000c8198c)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c000000000c979b8)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffe00073eb84)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffe00074c540)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffff818b41c0)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818c34d9)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffff8186e110)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8187d419)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffff819051c0)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819144d9)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
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
In net/core/sock.c (ffffffff8192626c)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff81935603)
Location: include/net/netprio_cgroup.h:22
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
</details>
</li>
</ul>

## Differences
