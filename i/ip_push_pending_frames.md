# Function: <code>ip_push_pending_frames</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8175f460)
Location: net/ipv4/ip_output.c:1455
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8175f460-ffffffff8175f496: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817cb700)
Location: net/ipv4/ip_output.c:1453
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff817cb700-ffffffff817cb736: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff817fb360)
Location: net/ipv4/ip_output.c:1494
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff817fb360-ffffffff817fb396: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8181b750)
Location: net/ipv4/ip_output.c:1507
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8181b750-ffffffff8181b786: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8189a680)
Location: net/ipv4/ip_output.c:1425
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8189a680-ffffffff8189a6b6: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff818eeb50)
Location: net/ipv4/ip_output.c:1449
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff818eeb50-ffffffff818eeb86: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8191c2f0)
Location: net/ipv4/ip_output.c:1476
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8191c2f0-ffffffff8191c326: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197e620)
Location: net/ipv4/ip_output.c:1565
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8197e620-ffffffff8197e656: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b4fc0)
Location: net/ipv4/ip_output.c:1573
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff819b4fc0-ffffffff819b4ff6: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9f1f0)
Location: net/ipv4/ip_output.c:1572
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81a9f1f0-ffffffff81a9f27e: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa9130)
Location: net/ipv4/ip_output.c:1579
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81aa9130-ffffffff81aa91be: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a942b0)
Location: net/ipv4/ip_output.c:1583
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81a942b0-ffffffff81a9435c: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4f730)
Location: net/ipv4/ip_output.c:1582
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81b4f730-ffffffff81b4f7dc: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cdd0e0)
Location: net/ipv4/ip_output.c:1582
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81cdd0e0-ffffffff81cdd1a4: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e9db70)
Location: net/ipv4/ip_output.c:1597
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81e9db70-ffffffff81e9dc34: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81efc330)
Location: net/ipv4/ip_output.c:1497
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81efc330-ffffffff81efc3f4: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fc0270)
Location: net/ipv4/ip_output.c:1503
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81fc0270-ffffffff81fc0334: ip_push_pending_frames (STB_GLOBAL)
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
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c65740)
Location: net/ipv4/ip_output.c:1573
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffff800010c65740-ffff800010c65790: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d753cc)
Location: net/ipv4/ip_output.c:1573
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
c0d753cc-c0d7540c: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d69e10)
Location: net/ipv4/ip_output.c:1573
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
c000000000d69e10-c000000000d69e74: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007ccf24)
Location: net/ipv4/ip_output.c:1573
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffe0007ccf24-ffffffe0007ccf6e: ip_push_pending_frames (STB_GLOBAL)
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
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81954e30)
Location: net/ipv4/ip_output.c:1573
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81954e30-ffffffff81954e66: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190e920)
Location: net/ipv4/ip_output.c:1573
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8190e920-ffffffff8190e956: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819bf600)
Location: net/ipv4/ip_output.c:1573
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff819bf600-ffffffff819bf636: ip_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip_push_pending_frames(struct sock *sk, struct flowi4 *fl4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c8f80)
Location: net/ipv4/ip_output.c:1573
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_send_unicast_reply
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/icmp.c:icmp_push_reply
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff819c8f80-ffffffff819c8fb6: ip_push_pending_frames (STB_GLOBAL)
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
