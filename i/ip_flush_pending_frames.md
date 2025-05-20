# Function: <code>ip_flush_pending_frames</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8175f4a0)
Location: net/ipv4/ip_output.c:1482
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8175f4a0-ffffffff8175f4be: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817cbb91)
Location: net/ipv4/ip_output.c:1480
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff817cb740-ffffffff817cb75e: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817fb80c)
Location: net/ipv4/ip_output.c:1521
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff817fb3a0-ffffffff817fb3be: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8181bbd1)
Location: net/ipv4/ip_output.c:1534
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8181b790-ffffffff8181b7ae: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8189ab0a)
Location: net/ipv4/ip_output.c:1452
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8189a6c0-ffffffff8189a6de: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818eefd3)
Location: net/ipv4/ip_output.c:1476
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff818eeb90-ffffffff818eebae: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8191c7d7)
Location: net/ipv4/ip_output.c:1503
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8191c330-ffffffff8191c34e: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197eb0b)
Location: net/ipv4/ip_output.c:1592
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8197e660-ffffffff8197e67e: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b549d)
Location: net/ipv4/ip_output.c:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff819b5000-ffffffff819b501e: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9f6f1)
Location: net/ipv4/ip_output.c:1599
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81a9f280-ffffffff81a9f29e: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa9654)
Location: net/ipv4/ip_output.c:1606
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81aa91c0-ffffffff81aa91de: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a94827)
Location: net/ipv4/ip_output.c:1610
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81a94360-ffffffff81a9437e: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4fca7)
Location: net/ipv4/ip_output.c:1609
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81b4f7e0-ffffffff81b4f7fe: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cdd77d)
Location: net/ipv4/ip_output.c:1609
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81cdd1b0-ffffffff81cdd1d6: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e9e23f)
Location: net/ipv4/ip_output.c:1624
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81e9dc50-ffffffff81e9dc76: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81efca3e)
Location: net/ipv4/ip_output.c:1524
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81efc410-ffffffff81efc436: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fc0976)
Location: net/ipv4/ip_output.c:1530
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_destroy_sock
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81fc0350-ffffffff81fc0376: ip_flush_pending_frames (STB_GLOBAL)
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
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c65b90)
Location: net/ipv4/ip_output.c:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffff800010c65790-ffff800010c657c0: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d7580c)
Location: net/ipv4/ip_output.c:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
c0d7540c-c0d75430: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d6a380)
Location: net/ipv4/ip_output.c:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
c000000000d69e80-c000000000d69e9c: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007cd2d6)
Location: net/ipv4/ip_output.c:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffe0007ccf6e-ffffffe0007ccf9e: ip_flush_pending_frames (STB_GLOBAL)
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
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8195530d)
Location: net/ipv4/ip_output.c:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81954e70-ffffffff81954e8e: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190edfd)
Location: net/ipv4/ip_output.c:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8190e960-ffffffff8190e97e: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819bfadd)
Location: net/ipv4/ip_output.c:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff819bf640-ffffffff819bf65e: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ip_flush_pending_frames(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c9494)
Location: net/ipv4/ip_output.c:1600
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
Direct callers:
  - net/ipv4/raw.c:raw_destroy
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff819c8fc0-ffffffff819c8fde: ip_flush_pending_frames (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
