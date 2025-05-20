# Function: <code>ip_cmsg_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip_cmsg_send(struct net *net, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817605a0)
Location: net/ipv4/ip_sockglue.c:222
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff817605a0-ffffffff81760752: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817cc890)
Location: net/ipv4/ip_sockglue.c:223
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff817cc890-ffffffff817cca7d: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817fc590)
Location: net/ipv4/ip_sockglue.c:238
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff817fc590-ffffffff817fc791: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8181c930)
Location: net/ipv4/ip_sockglue.c:238
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8181c930-ffffffff8181cb44: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8189b870)
Location: net/ipv4/ip_sockglue.c:240
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8189b870-ffffffff8189ba96: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff818efdc0)
Location: net/ipv4/ip_sockglue.c:245
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff818efdc0-ffffffff818effe9: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8191d6b0)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8191d6b0-ffffffff8191d8d9: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8197fa20)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8197fa20-ffffffff8197fc4e: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819b63c0)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff819b63c0-ffffffff819b65ee: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa0c30)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81aa0c30-ffffffff81aa0e56: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aab1f0)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81aab1f0-ffffffff81aab42a: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a96410)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81a96410-ffffffff81a9664c: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b51880)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81b51880-ffffffff81b51ac3: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81cdf440)
Location: net/ipv4/ip_sockglue.c:244
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81cdf440-ffffffff81cdf668: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81e9f910)
Location: net/ipv4/ip_sockglue.c:244
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81e9f910-ffffffff81e9fb35: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81efe0f0)
Location: net/ipv4/ip_sockglue.c:244
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81efe0f0-ffffffff81efe387: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc22d0)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81fc22d0-ffffffff81fc2567: ip_cmsg_send (STB_GLOBAL)
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
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffff800010c67860)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffff800010c67860-ffff800010c67b20: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c0d767d0)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
c0d767d0-c0d769f4: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c000000000d6b990)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
c000000000d6b990-c000000000d6bd08: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffe0007cddb8)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffe0007cddb8-ffffffe0007cdfc4: ip_cmsg_send (STB_GLOBAL)
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
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81956230)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff81956230-ffffffff8195645e: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8190fd20)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff8190fd20-ffffffff8190ff4e: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819c0a00)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff819c0a00-ffffffff819c0c2e: ip_cmsg_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip_cmsg_send(struct sock *sk, struct msghdr *msg, struct ipcm_cookie *ipc, bool allow_ipv6);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819ca3e0)
Location: net/ipv4/ip_sockglue.c:242
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/ping.c:ping_v4_sendmsg
```
**Symbols:**

```
ffffffff819ca3e0-ffffffff819ca60e: ip_cmsg_send (STB_GLOBAL)
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
<code>struct sock *sk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net *net</code>
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
