# Function: <code>__scm_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff8170e690)
Location: net/core/scm.c:133
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff8170e690-ffffffff8170ea90: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81775e30)
Location: net/core/scm.c:133
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff81775e30-ffffffff81776236: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff817a30b0)
Location: net/core/scm.c:133
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff817a30b0-ffffffff817a34b6: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff817c1200)
Location: net/core/scm.c:134
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff817c1200-ffffffff817c15f2: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff8183ac20)
Location: net/core/scm.c:134
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff8183ac20-ffffffff8183b005: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81885360)
Location: net/core/scm.c:134
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff81885360-ffffffff81885736: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff818a5a90)
Location: net/core/scm.c:134
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff818a5a90-ffffffff818a5e6c: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff818f0de0)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff818f0de0-ffffffff818f11da: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81922d20)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff81922d20-ffffffff8192311a: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff819f6d60)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff819f6d60-ffffffff819f71a3: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff819f67d0)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff819f67d0-ffffffff819f6c13: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff819dc940)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff819dc940-ffffffff819dcd81: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81a8cb80)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff81a8cb80-ffffffff81a8cfc1: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81c02460)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff81c02460-ffffffff81c028bf: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81db18f0)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff81db18f0-ffffffff81db1d4f: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81e21e40)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81e21e40-ffffffff81e222d2: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81edfd60)
Location: net/core/scm.c:137
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff81edfd60-ffffffff81ee0216: __scm_send (STB_GLOBAL)
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
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffff800010bbda28)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffff800010bbda28-ffff800010bbde20: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (c0cd9ad8)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
c0cd9ad8-c0cd9f14: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (c000000000c96dd0)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
c000000000c96dd0-c000000000c97318: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffe00074bdbc)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffe00074bdbc-ffffffe00074c14c: __scm_send (STB_GLOBAL)
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
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff818c2d20)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff818c2d20-ffffffff818c311a: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff8187cc60)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff8187cc60-ffffffff8187d05a: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81913d20)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff81913d20-ffffffff8191411a: __scm_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __scm_send(struct socket *sock, struct msghdr *msg, struct scm_cookie *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81934eb0)
Location: net/core/scm.c:131
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff81934eb0-ffffffff819352aa: __scm_send (STB_GLOBAL)
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
