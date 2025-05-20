# Function: <code>refcount_sub_and_test_checked</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff814e21e0)
Location: lib/refcount.c:177
Inline: True
```
**Symbols:**

```
ffffffff814e21e0-ffffffff814e2240: refcount_sub_and_test_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8150e070)
Location: lib/refcount.c:180
Inline: True
```
**Symbols:**

```
ffffffff8150e070-ffffffff8150e0cf: refcount_sub_and_test_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8152bec0)
Location: lib/refcount.c:180
Inline: True
```
**Symbols:**

```
ffffffff8152bec0-ffffffff8152bf1f: refcount_sub_and_test_checked (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffff800010637868)
Location: lib/refcount.c:180
Inline: True
Direct callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
**Symbols:**

```
ffff800010637868-ffff800010637924: refcount_sub_and_test_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c07dd668)
Location: lib/refcount.c:180
Inline: True
Direct callers:
  - net/core/sock.c:__sock_wfree
  - net/core/sock.c:sock_wfree
  - net/core/sock.c:sock_wfree
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/inet_fragment.c:inet_frags_free_cb
```
**Symbols:**

```
c07dd668-c07dd720: refcount_sub_and_test_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c0000000007dda80)
Location: lib/refcount.c:180
Inline: True
```
**Symbols:**

```
c0000000007dda80-c0000000007ddb84: refcount_sub_and_test_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffe000464b78)
Location: lib/refcount.c:180
Inline: True
```
**Symbols:**

```
ffffffe000464b78-ffffffe000464c08: refcount_sub_and_test_checked (STB_GLOBAL)
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
bool refcount_sub_and_test_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815244a0)
Location: lib/refcount.c:180
Inline: True
```
**Symbols:**

```
ffffffff815244a0-ffffffff815244ff: refcount_sub_and_test_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81514780)
Location: lib/refcount.c:180
Inline: True
```
**Symbols:**

```
ffffffff81514780-ffffffff815147df: refcount_sub_and_test_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81520530)
Location: lib/refcount.c:180
Inline: True
```
**Symbols:**

```
ffffffff81520530-ffffffff8152058f: refcount_sub_and_test_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool refcount_sub_and_test_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81539eb0)
Location: lib/refcount.c:180
Inline: True
```
**Symbols:**

```
ffffffff81539eb0-ffffffff81539f0f: refcount_sub_and_test_checked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
