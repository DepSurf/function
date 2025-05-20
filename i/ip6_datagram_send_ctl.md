# Function: <code>ip6_datagram_send_ctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipv6_txoptions *opt, int *hlimit, int *tclass, int *dontfrag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff817f45b0)
Location: net/ipv6/datagram.c:685
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff817f45b0-ffffffff817f49e6: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6, struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81862fa0)
Location: net/ipv6/datagram.c:728
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81862fa0-ffffffff81863434: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6, struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff818955b0)
Location: net/ipv6/datagram.c:740
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff818955b0-ffffffff81895a44: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6, struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff818bbb10)
Location: net/ipv6/datagram.c:738
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff818bbb10-ffffffff818bbfb4: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6, struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff8193ebe0)
Location: net/ipv6/datagram.c:745
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff8193ebe0-ffffffff8193f08a: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6, struct sockcm_cookie *sockc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81997ab0)
Location: net/ipv6/datagram.c:740
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81997ab0-ffffffff81997f75: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff819ce390)
Location: net/ipv6/datagram.c:739
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff819ce390-ffffffff819ce90e: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a3cfd0)
Location: net/ipv6/datagram.c:737
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81a3cfd0-ffffffff81a3d5b2: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a73c30)
Location: net/ipv6/datagram.c:737
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81a73c30-ffffffff81a74212: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81b6df40)
Location: net/ipv6/datagram.c:737
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81b6df40-ffffffff81b6e512: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81b7c9c0)
Location: net/ipv6/datagram.c:753
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81b7c9c0-ffffffff81b7cfc4: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81b6b4a0)
Location: net/ipv6/datagram.c:753
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81b6b4a0-ffffffff81b6baa3: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81c33300)
Location: net/ipv6/datagram.c:753
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81c33300-ffffffff81c33903: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81dd0b00)
Location: net/ipv6/datagram.c:753
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81dd0b00-ffffffff81dd116a: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81fa1ee0)
Location: net/ipv6/datagram.c:759
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81fa1ee0-ffffffff81fa2544: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff82002760)
Location: net/ipv6/datagram.c:759
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff82002760-ffffffff82002ddb: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff820d1720)
Location: net/ipv6/datagram.c:759
Inline: False
Direct callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ping.c:ping_v6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff820d1720-ffffffff820d1db2: ip6_datagram_send_ctl (STB_GLOBAL)
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
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffff800010d3c618)
Location: net/ipv6/datagram.c:737
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffff800010d3c618-ffff800010d3cc60: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (c0e3f870)
Location: net/ipv6/datagram.c:737
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
c0e3f870-c0e3fec0: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (c000000000e703b0)
Location: net/ipv6/datagram.c:737
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
c000000000e703b0-c000000000e70bf0: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffe000878ffc)
Location: net/ipv6/datagram.c:737
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffe000878ffc-ffffffe0008794f6: ip6_datagram_send_ctl (STB_GLOBAL)
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
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a132c0)
Location: net/ipv6/datagram.c:737
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81a132c0-ffffffff81a138a2: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff819d0080)
Location: net/ipv6/datagram.c:737
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff819d0080-ffffffff819d0662: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a7dd40)
Location: net/ipv6/datagram.c:737
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81a7dd40-ffffffff81a7e322: ip6_datagram_send_ctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6_datagram_send_ctl(struct net *net, struct sock *sk, struct msghdr *msg, struct flowi6 *fl6, struct ipcm6_cookie *ipc6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/datagram.c (ffffffff81a8a590)
Location: net/ipv6/datagram.c:737
Inline: False
Direct callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/ip6_flowlabel.c:fl_create
```
**Symbols:**

```
ffffffff81a8a590-ffffffff81a8abbb: ip6_datagram_send_ctl (STB_GLOBAL)
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
<code>struct sockcm_cookie *sockc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ipv6_txoptions *opt</code>
</li>
<li>
<b>Param removed. </b>
<code>int *hlimit</code>
</li>
<li>
<b>Param removed. </b>
<code>int *tclass</code>
</li>
<li>
<b>Param removed. </b>
<code>int *dontfrag</code>
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
<code>struct sockcm_cookie *sockc</code>
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
