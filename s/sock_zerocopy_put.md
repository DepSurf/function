# Function: <code>sock_zerocopy_put</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81833ed0)
Location: net/core/skbuff.c:1080
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81833ed0-ffffffff81833f0d: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187e360)
Location: net/core/skbuff.c:1081
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8187e360-ffffffff8187e39c: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189ef20)
Location: net/core/skbuff.c:1083
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff8189ef20-ffffffff8189ef5c: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e9750)
Location: net/core/skbuff.c:1245
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff818e9750-ffffffff818e978c: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191b8c0)
Location: net/core/skbuff.c:1245
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff8191b8c0-ffffffff8191b8fc: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed7d0)
Location: net/core/skbuff.c:1244
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
**Symbols:**

```
ffffffff819ed7d0-ffffffff819ed828: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed490)
Location: net/core/skbuff.c:1255
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
```
**Symbols:**

```
ffffffff819ed490-ffffffff819ed4e8: sock_zerocopy_put (STB_GLOBAL)
```
</details>
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
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb5e30)
Location: net/core/skbuff.c:1245
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffff800010bb5e30-ffff800010bb5e8c: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd2dec)
Location: net/core/skbuff.c:1245
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
c0cd2dec-c0cd2e44: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8d330)
Location: net/core/skbuff.c:1245
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
c000000000c8d330-c000000000c8d3b8: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffe00074738c)
Location: net/core/skbuff.c:1245
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffe000745cae-ffffffe000745cf2: sock_zerocopy_put.part.0 (STB_LOCAL)
ffffffe000745cf2-ffffffe000745d3a: sock_zerocopy_put (STB_GLOBAL)
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
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bb8c0)
Location: net/core/skbuff.c:1245
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff818bb8c0-ffffffff818bb8fc: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81875800)
Location: net/core/skbuff.c:1245
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff81875800-ffffffff8187583c: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190c8c0)
Location: net/core/skbuff.c:1245
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff8190c8c0-ffffffff8190c8fc: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sock_zerocopy_put(struct ubuf_info *uarg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192da00)
Location: net/core/skbuff.c:1245
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_put_abort
  - net/core/skbuff.c:skb_release_data
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
**Symbols:**

```
ffffffff8192da00-ffffffff8192da3c: sock_zerocopy_put (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
