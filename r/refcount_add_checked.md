# Function: <code>refcount_add_checked</code>

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
void refcount_add_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff814e2110)
Location: lib/refcount.c:100
Inline: True
```
**Symbols:**

```
ffffffff814e2110-ffffffff814e213f: refcount_add_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8150dfb0)
Location: lib/refcount.c:103
Inline: True
```
**Symbols:**

```
ffffffff8150dfb0-ffffffff8150dfdf: refcount_add_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8152be00)
Location: lib/refcount.c:103
Inline: True
```
**Symbols:**

```
ffffffff8152be00-ffffffff8152be2f: refcount_add_checked (STB_GLOBAL)
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
void refcount_add_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffff800010637c68)
Location: lib/refcount.c:103
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - fs/io_uring.c:__arm64_sys_io_uring_register
  - net/core/sock.c:skb_set_owner_w
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
ffff800010637c68-ffff800010637cb0: refcount_add_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c07dd510)
Location: lib/refcount.c:103
Inline: True
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_clear_mc
  - fs/io_uring.c:__se_sys_io_uring_register
  - net/core/sock.c:skb_set_owner_w
  - net/core/datagram.c:__zerocopy_sg_from_iter
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/packet/af_packet.c:tpacket_snd
```
**Symbols:**

```
c07dd510-c07dd564: refcount_add_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c0000000007dd8c0)
Location: lib/refcount.c:103
Inline: True
```
**Symbols:**

```
c0000000007dd8c0-c0000000007dd924: refcount_add_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffe000464a82)
Location: lib/refcount.c:103
Inline: True
```
**Symbols:**

```
ffffffe000464a82-ffffffe000464ac4: refcount_add_checked (STB_GLOBAL)
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
void refcount_add_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815243e0)
Location: lib/refcount.c:103
Inline: True
```
**Symbols:**

```
ffffffff815243e0-ffffffff8152440f: refcount_add_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff815146c0)
Location: lib/refcount.c:103
Inline: True
```
**Symbols:**

```
ffffffff815146c0-ffffffff815146ef: refcount_add_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81520470)
Location: lib/refcount.c:103
Inline: True
```
**Symbols:**

```
ffffffff81520470-ffffffff8152049f: refcount_add_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void refcount_add_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81539df0)
Location: lib/refcount.c:103
Inline: True
```
**Symbols:**

```
ffffffff81539df0-ffffffff81539e1f: refcount_add_checked (STB_GLOBAL)
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
