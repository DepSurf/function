# Function: <code>sock_cgroup_set_classid</code>

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
In net/core/sock.c (ffffffff81767651)
Location: include/linux/cgroup-defs.h:644
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff81776400)
Location: include/linux/cgroup-defs.h:644
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffff817aa7d7)
Location: include/linux/cgroup-defs.h:644
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff81794659)
Location: include/linux/cgroup-defs.h:648
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817a3680)
Location: include/linux/cgroup-defs.h:648
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffff817d92f7)
Location: include/linux/cgroup-defs.h:648
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff817b48ac)
Location: include/linux/cgroup-defs.h:671
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817c18a3)
Location: include/linux/cgroup-defs.h:671
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffff817f85c7)
Location: include/linux/cgroup-defs.h:671
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
In net/core/sock.c (ffffffff8182cb0c)
Location: include/linux/cgroup-defs.h:791
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8183b2b0)
Location: include/linux/cgroup-defs.h:791
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffff81875e97)
Location: include/linux/cgroup-defs.h:791
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
In net/core/sock.c (ffffffff8187763c)
Location: include/linux/cgroup-defs.h:803
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818858fd)
Location: include/linux/cgroup-defs.h:803
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffff818c7467)
Location: include/linux/cgroup-defs.h:803
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff81897a8c)
Location: include/linux/cgroup-defs.h:812
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818a602d)
Location: include/linux/cgroup-defs.h:812
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffff818f05a7)
Location: include/linux/cgroup-defs.h:812
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff818e1fad)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818f14c2)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffff81941f17)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff8191417d)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff81923412)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffff81976e0b)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff819e8599)
Location: include/linux/cgroup-defs.h:852
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819f6b3e)
Location: include/linux/cgroup-defs.h:852
Inline: True
Inline callers:
  - net/core/scm.c:__scm_install_fd
```
```
In net/core/netclassid_cgroup.c (ffffffff81a4bbbb)
Location: include/linux/cgroup-defs.h:852
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff819e8218)
Location: include/linux/cgroup-defs.h:837
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netclassid_cgroup.c (ffffffff81a517f6)
Location: include/linux/cgroup-defs.h:837
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff819ce348)
Location: include/linux/cgroup-defs.h:837
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netclassid_cgroup.c (ffffffff81a3706b)
Location: include/linux/cgroup-defs.h:837
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff81a7dc26)
Location: include/linux/cgroup-defs.h:797
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netclassid_cgroup.c (ffffffff81aecd25)
Location: include/linux/cgroup-defs.h:797
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff81bf2516)
Location: include/linux/cgroup-defs.h:798
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netclassid_cgroup.c (ffffffff81c6f8d5)
Location: include/linux/cgroup-defs.h:798
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff81d9e6a6)
Location: include/linux/cgroup-defs.h:826
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netclassid_cgroup.c (ffffffff81e27785)
Location: include/linux/cgroup-defs.h:826
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff81e0ceb6)
Location: include/linux/cgroup-defs.h:826
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netclassid_cgroup.c (ffffffff81e9cd95)
Location: include/linux/cgroup-defs.h:826
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff81ec9846)
Location: include/linux/cgroup-defs.h:862
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/netclassid_cgroup.c (ffffffff81f5f4e5)
Location: include/linux/cgroup-defs.h:862
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffff800010bab160)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffff800010bbe618)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffff800010c1d6d4)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (c0cc9c10)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c0cda000)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (c0d3551c)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (c000000000c81958)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c000000000c97a08)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (c000000000d0e8d8)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffe00073eb54)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffe00074c3ce)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffe000797250)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff818b417d)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818c3412)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffff81916c7b)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff8186e0cd)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8187d352)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffff818d0a2b)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff8190517d)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff81914412)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffff81967e0b)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/sock.c (ffffffff8192623c)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8193567e)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/netclassid_cgroup.c (ffffffff8198a1cb)
Location: include/linux/cgroup-defs.h:855
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
</ul>

## Differences
