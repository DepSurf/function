# Function: <code>udp_rmem_release</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81824bc0)
Location: net/ipv4/udp.c:1178
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffffffff81824bc0-ffffffff81824c3f: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81845910)
Location: net/ipv4/udp.c:1194
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffffffff81845910-ffffffff81845a55: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c5380)
Location: net/ipv4/udp.c:1202
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffffffff818c5380-ffffffff818c5495: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191d670)
Location: net/ipv4/udp.c:1272
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffffffff8191d670-ffffffff8191d78d: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194c5f0)
Location: net/ipv4/udp.c:1340
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffffffff8194c5f0-ffffffff8194c70d: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b0d90)
Location: net/ipv4/udp.c:1327
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffffffff819b0d90-ffffffff819b0eae: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e7860)
Location: net/ipv4/udp.c:1361
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffffffff819e7860-ffffffff819e79bd: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad3d90)
Location: net/ipv4/udp.c:1367
Inline: False
Direct callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff81ad3d90-ffffffff81ad3eed: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ae02d0)
Location: net/ipv4/udp.c:1417
Inline: False
Direct callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff81ae02d0-ffffffff81ae042d: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81acc2f0)
Location: net/ipv4/udp.c:1436
Inline: False
Direct callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff81acc2f0-ffffffff81acc44d: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b8ab80)
Location: net/ipv4/udp.c:1437
Inline: False
Direct callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff81b8ab80-ffffffff81b8acdd: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d1a0b0)
Location: net/ipv4/udp.c:1437
Inline: False
Direct callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
```
**Symbols:**

```
ffffffff81d1a0b0-ffffffff81d1a235: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee0d30)
Location: net/ipv4/udp.c:1448
Inline: False
Direct callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
```
**Symbols:**

```
ffffffff81ee0d30-ffffffff81ee0eb2: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f40660)
Location: net/ipv4/udp.c:1420
Inline: False
Direct callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
```
**Symbols:**

```
ffffffff81f40660-ffffffff81f407c9: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff820062b0)
Location: net/ipv4/udp.c:1395
Inline: False
Direct callers:
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:__skb_recv_udp
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_common
```
**Symbols:**

```
ffffffff820062b0-ffffffff8200641f: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9b738)
Location: net/ipv4/udp.c:1361
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffff800010c9b738-ffff800010c9b8c0: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da747c)
Location: net/ipv4/udp.c:1361
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
c0da747c-c0da75a4: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000daadb0)
Location: net/ipv4/udp.c:1361
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
c000000000daadb0-c000000000daafbc: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f9ab8)
Location: net/ipv4/udp.c:1361
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffffffe0007f9ab8-ffffffe0007f9bec: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819876d0)
Location: net/ipv4/udp.c:1361
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffffffff819876d0-ffffffff8198782d: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81941190)
Location: net/ipv4/udp.c:1361
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffffffff81941190-ffffffff819412ed: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f1ea0)
Location: net/ipv4/udp.c:1361
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffffffff819f1ea0-ffffffff819f1ffd: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void udp_rmem_release(struct sock *sk, int size, int partial, bool rx_queue_lock_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f9020)
Location: net/ipv4/udp.c:1361
Inline: False
Direct callers:
  - net/ipv4/udp.c:first_packet_length
  - net/ipv4/udp.c:udp_destruct_sock
  - net/ipv4/udp.c:udp_skb_dtor_locked
  - net/ipv4/udp.c:udp_skb_destructor
```
**Symbols:**

```
ffffffff819f9020-ffffffff819f917b: udp_rmem_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rx_queue_lock_held</code>
</li>
</ul>
</details>
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
