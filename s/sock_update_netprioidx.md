# Function: <code>sock_update_netprioidx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void sock_update_netprioidx(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817013f0)
Location: net/core/sock.c:1396
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
Direct callers:
  - net/core/scm.c:scm_detach_fds
```
**Symbols:**

```
ffffffff817020c0-ffffffff817020ff: sock_update_netprioidx (STB_GLOBAL)
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
In net/core/sock.c (ffffffff81767679)
Location: include/net/netprio_cgroup.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817763fa)
Location: include/net/netprio_cgroup.h:40
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
In net/core/sock.c (ffffffff81794681)
Location: include/net/netprio_cgroup.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817a367a)
Location: include/net/netprio_cgroup.h:40
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
In net/core/sock.c (ffffffff817b48bf)
Location: include/net/netprio_cgroup.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817c17ba)
Location: include/net/netprio_cgroup.h:40
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
In net/core/sock.c (ffffffff8182cb1f)
Location: include/net/netprio_cgroup.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8183b1ca)
Location: include/net/netprio_cgroup.h:40
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
In net/core/sock.c (ffffffff81877666)
Location: include/net/netprio_cgroup.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818859be)
Location: include/net/netprio_cgroup.h:40
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
In net/core/sock.c (ffffffff81897ab6)
Location: include/net/netprio_cgroup.h:40
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818a60e1)
Location: include/net/netprio_cgroup.h:40
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
In net/core/sock.c (ffffffff818e1fd9)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818f1587)
Location: include/net/netprio_cgroup.h:34
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
In net/core/sock.c (ffffffff819141a9)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819234d7)
Location: include/net/netprio_cgroup.h:34
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
In net/core/sock.c (ffffffff819e856b)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819f6ac0)
Location: include/net/netprio_cgroup.h:34
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
In net/core/sock.c (ffffffff819e81ef)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff819ce31f)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81a7dbff)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81bf24ef)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81d9e67f)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81e0ce8f)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffffffff81ec981f)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
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
In net/core/sock.c (ffff800010bab180)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffff800010bbe5c4)
Location: include/net/netprio_cgroup.h:34
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
In net/core/sock.c (c0cc9c40)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c0cda0fc)
Location: include/net/netprio_cgroup.h:34
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
In net/core/sock.c (c000000000c8197c)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c000000000c979b0)
Location: include/net/netprio_cgroup.h:34
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
In net/core/sock.c (ffffffe00073eb72)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffe00074c3c4)
Location: include/net/netprio_cgroup.h:34
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
In net/core/sock.c (ffffffff818b41a9)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818c34d7)
Location: include/net/netprio_cgroup.h:34
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
In net/core/sock.c (ffffffff8186e0f9)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8187d417)
Location: include/net/netprio_cgroup.h:34
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
In net/core/sock.c (ffffffff819051a9)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819144d7)
Location: include/net/netprio_cgroup.h:34
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
In net/core/sock.c (ffffffff81926250)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819355f1)
Location: include/net/netprio_cgroup.h:34
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
