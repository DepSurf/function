# Function: <code>ip6_append_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, int hlimit, int tclass, struct ipv6_txoptions *opt, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, int dontfrag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff817c6710)
Location: net/ipv6/ip6_output.c:1564
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff817c6710-ffffffff817c6862: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81833810)
Location: net/ipv6/ip6_output.c:1567
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81833810-ffffffff81833962: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81865290)
Location: net/ipv6/ip6_output.c:1594
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81865290-ffffffff818653e2: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81889a90)
Location: net/ipv6/ip6_output.c:1597
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81889a90-ffffffff81889bbe: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff8190ac60)
Location: net/ipv6/ip6_output.c:1546
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff8190ac60-ffffffff8190ad8e: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags, const struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81962140)
Location: net/ipv6/ip6_output.c:1558
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81962140-ffffffff81962272: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81996b80)
Location: net/ipv6/ip6_output.c:1588
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81996b80-ffffffff81996ca9: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a03100)
Location: net/ipv6/ip6_output.c:1652
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a03100-ffffffff81a03221: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a39cd0)
Location: net/ipv6/ip6_output.c:1656
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a39cd0-ffffffff81a39dfa: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2f500)
Location: net/ipv6/ip6_output.c:1726
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81b2f500-ffffffff81b2f625: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3df50)
Location: net/ipv6/ip6_output.c:1765
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81b3df50-ffffffff81b3e075: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2b400)
Location: net/ipv6/ip6_output.c:1797
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81b2b400-ffffffff81b2b525: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1779
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81d3f447-ffffffff81d3f467: ip6_append_data.cold (STB_LOCAL)
ffffffff81bf1520-ffffffff81bf1658: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, size_t length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1800
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81f0bdf0-ffffffff81f0be18: ip6_append_data.cold (STB_LOCAL)
ffffffff81d89d90-ffffffff81d89fa6: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, size_t length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1838
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff820b35fa-ffffffff820b364d: ip6_append_data.cold (STB_LOCAL)
ffffffff81f57d30-ffffffff81f57f1c: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, size_t length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1857
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff8213476e-ffffffff821347ba: ip6_append_data.cold (STB_LOCAL)
ffffffff81fb78e0-ffffffff81fb7afe: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, size_t length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: net/ipv6/ip6_output.c:1806
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff822162f4-ffffffff82216340: ip6_append_data.cold (STB_LOCAL)
ffffffff82084f10-ffffffff82085123: ip6_append_data (STB_GLOBAL)
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
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffff800010cf9bb8)
Location: net/ipv6/ip6_output.c:1656
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffff800010cf9bb8-ffff800010cf9cfc: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c0e0141c)
Location: net/ipv6/ip6_output.c:1656
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
c0e0141c-c0e01548: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (c000000000e21e00)
Location: net/ipv6/ip6_output.c:1656
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
c000000000e21e00-c000000000e21fb4: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffe000845840)
Location: net/ipv6/ip6_output.c:1656
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffe000845840-ffffffe00084594c: ip6_append_data (STB_GLOBAL)
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
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff819d9360)
Location: net/ipv6/ip6_output.c:1656
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff819d9360-ffffffff819d948a: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81996120)
Location: net/ipv6/ip6_output.c:1656
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81996120-ffffffff8199624a: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a43de0)
Location: net/ipv6/ip6_output.c:1656
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a43de0-ffffffff81a43f0a: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_append_data(struct sock *sk, int (*getfrag)(void *, char *, int, int, int, struct sk_buff *), void *from, int length, int transhdrlen, struct ipcm6_cookie *ipc6, struct flowi6 *fl6, struct rt6_info *rt, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81a4fa80)
Location: net/ipv6/ip6_output.c:1656
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/icmp.c:icmpv6_echo_reply
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ping.c:ping_v6_sendmsg
```
**Symbols:**

```
ffffffff81a4fa80-ffffffff81a4fbaa: ip6_append_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ipcm6_cookie *ipc6</code>
</li>
<li>
<b>Param added. </b>
<code>const struct sockcm_cookie *sockc</code>
</li>
<li>
<b>Param removed. </b>
<code>int hlimit</code>
</li>
<li>
<b>Param removed. </b>
<code>int tclass</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ipv6_txoptions *opt</code>
</li>
<li>
<b>Param removed. </b>
<code>int dontfrag</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, getfrag, from, length, transhdrlen, hlimit, tclass, opt, fl6, rt, flags, dontfrag</code> ➡️ <code>sk, getfrag, from, length, transhdrlen, ipc6, fl6, rt, flags, sockc</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct sockcm_cookie *sockc</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int length</code> ➡️ <code>size_t length</code>
</li>
</ul>
</details>
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
