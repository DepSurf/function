# Function: <code>__sk_mem_reduce_allocated</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817969f0)
Location: net/core/sock.c:2224
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff817969f0-ffffffff81796adb: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b4df0)
Location: net/core/sock.c:2383
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff817b4df0-ffffffff817b4ec3: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182d220)
Location: net/core/sock.c:2423
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff8182d220-ffffffff8182d2f6: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81877000)
Location: net/core/sock.c:2504
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff81877000-ffffffff818770db: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818977a0)
Location: net/core/sock.c:2448
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff818977a0-ffffffff8189787b: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e1cb0)
Location: net/core/sock.c:2591
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff818e1cb0-ffffffff818e1d8f: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81913e70)
Location: net/core/sock.c:2606
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff81913e70-ffffffff81913f55: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5ac0)
Location: net/core/sock.c:2714
Inline: False
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff819e5ac0-ffffffff819e5bac: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5590)
Location: net/core/sock.c:2706
Inline: False
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff819e5590-ffffffff819e567c: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819cb6a0)
Location: net/core/sock.c:2729
Inline: False
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff819cb6a0-ffffffff819cb78c: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7ad30)
Location: net/core/sock.c:2860
Inline: False
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff81a7ad30-ffffffff81a7ae13: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81beec40)
Location: net/core/sock.c:3023
Inline: False
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:__mptcp_mem_reclaim_partial
  - net/mptcp/protocol.c:mptcp_rfree
```
**Symbols:**

```
ffffffff81beec40-ffffffff81beed4a: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9e330)
Location: net/core/sock.c:3104
Inline: False
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_rfree
```
**Symbols:**

```
ffffffff81d9e330-ffffffff81d9e48f: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0cbb0)
Location: net/core/sock.c:3165
Inline: False
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_rfree
```
**Symbols:**

```
ffffffff81e0cbb0-ffffffff81e0cc95: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec9530)
Location: net/core/sock.c:3175
Inline: False
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
  - net/mptcp/protocol.c:__mptcp_update_rmem
  - net/mptcp/protocol.c:mptcp_rfree
```
**Symbols:**

```
ffffffff81ec9530-ffffffff81ec9615: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010babb40)
Location: net/core/sock.c:2606
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffff800010babb40-ffff800010babc44: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cca6bc)
Location: net/core/sock.c:2606
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
c0cca6bc-c0cca7ec: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c82090)
Location: net/core/sock.c:2606
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
c000000000c82090-c000000000c821fc: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073f192)
Location: net/core/sock.c:2606
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffe00073f192-ffffffe00073f25e: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b3e70)
Location: net/core/sock.c:2606
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff818b3e70-ffffffff818b3f55: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186ddc0)
Location: net/core/sock.c:2606
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff8186ddc0-ffffffff8186dea5: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81904e70)
Location: net/core/sock.c:2606
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff81904e70-ffffffff81904f55: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __sk_mem_reduce_allocated(struct sock *sk, int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81925f40)
Location: net/core/sock.c:2606
Inline: True
Direct callers:
  - net/core/sock.c:sock_rfree
  - net/core/sock.c:sk_clear_memalloc
  - net/ipv4/udp.c:udp_rmem_release
```
**Symbols:**

```
ffffffff81925f40-ffffffff81926025: __sk_mem_reduce_allocated (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
