# Function: <code>icmpv6_push_pending_frames</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff817e7620)
Location: net/ipv6/icmp.c:239
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff817e7620-ffffffff817e76f8: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81855a20)
Location: net/ipv6/icmp.c:239
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81855a20-ffffffff81855af8: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff818877e0)
Location: net/ipv6/icmp.c:240
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff818877e0-ffffffff818878b8: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff818addb0)
Location: net/ipv6/icmp.c:253
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff818addb0-ffffffff818adea6: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81930a30)
Location: net/ipv6/icmp.c:253
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81930a30-ffffffff81930b23: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81989660)
Location: net/ipv6/icmp.c:253
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81989660-ffffffff81989752: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff819bff90)
Location: net/ipv6/icmp.c:255
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff819bff90-ffffffff819c0082: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a2edd0)
Location: net/ipv6/icmp.c:250
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a2edd0-ffffffff81a2eed0: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a65920)
Location: net/ipv6/icmp.c:250
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a65920-ffffffff81a65a20: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81b5e270)
Location: net/ipv6/icmp.c:269
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81b5e270-ffffffff81b5e370: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81b6ca40)
Location: net/ipv6/icmp.c:275
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81b6ca40-ffffffff81b6cb40: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81b5ada0)
Location: net/ipv6/icmp.c:275
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81b5ada0-ffffffff81b5aea0: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81c224b0)
Location: net/ipv6/icmp.c:276
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81c224b0-ffffffff81c225b0: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81dbf1f0)
Location: net/ipv6/icmp.c:268
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81dbf1f0-ffffffff81dbf2fa: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81f8f910)
Location: net/ipv6/icmp.c:268
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81f8f910-ffffffff81f8fa33: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81ff0170)
Location: net/ipv6/icmp.c:272
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81ff0170-ffffffff81ff0261: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff820bdd40)
Location: net/ipv6/icmp.c:272
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff820bdd40-ffffffff820bde31: icmpv6_push_pending_frames (STB_GLOBAL)
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
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffff800010d2b9d8)
Location: net/ipv6/icmp.c:250
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffff800010d2b9d8-ffff800010d2baec: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (c0e2f850)
Location: net/ipv6/icmp.c:250
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
c0e2f850-c0e2f95c: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (c000000000e5cf80)
Location: net/ipv6/icmp.c:250
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
c000000000e5cf80-c000000000e5d10c: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffe00086bd08)
Location: net/ipv6/icmp.c:250
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffe00086bd08-ffffffe00086be1a: icmpv6_push_pending_frames (STB_GLOBAL)
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
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a04fb0)
Location: net/ipv6/icmp.c:250
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a04fb0-ffffffff81a050b0: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff819c1d70)
Location: net/ipv6/icmp.c:250
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff819c1d70-ffffffff819c1e70: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a6fa30)
Location: net/ipv6/icmp.c:250
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a6fa30-ffffffff81a6fb30: icmpv6_push_pending_frames (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void icmpv6_push_pending_frames(struct sock *sk, struct flowi6 *fl6, struct icmp6hdr *thdr, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/icmp.c (ffffffff81a7c060)
Location: net/ipv6/icmp.c:250
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a7c060-ffffffff81a7c160: icmpv6_push_pending_frames (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
