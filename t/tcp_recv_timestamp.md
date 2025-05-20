# Function: <code>tcp_recv_timestamp</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping *tss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a5480)
Location: net/ipv4/tcp.c:1734
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff818a5480-ffffffff818a55f7: tcp_recv_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f73e0)
Location: net/ipv4/tcp.c:1855
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81925a55)
Location: net/ipv4/tcp.c:1864
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819866b0)
Location: net/ipv4/tcp.c:1854
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff819866b0-ffffffff8198687d: tcp_recv_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819bce20)
Location: net/ipv4/tcp.c:1855
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff819bce20-ffffffff819bcfed: tcp_recv_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa8860)
Location: net/ipv4/tcp.c:1921
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81aa8860-ffffffff81aa8a19: tcp_recv_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab2de0)
Location: net/ipv4/tcp.c:2160
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81ab2de0-ffffffff81ab2f99: tcp_recv_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9e030)
Location: net/ipv4/tcp.c:2203
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81a9e030-ffffffff81a9e1f4: tcp_recv_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5e4e0)
Location: net/ipv4/tcp.c:2203
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81b5e4e0-ffffffff81b5e6a4: tcp_recv_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81cece90)
Location: net/ipv4/tcp.c:2230
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81cece90-ffffffff81ced07b: tcp_recv_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eb0da0)
Location: net/ipv4/tcp.c:2330
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81eb0da0-ffffffff81eb0f9b: tcp_recv_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f0f420)
Location: net/ipv4/tcp.c:2216
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81f0f420-ffffffff81f0f622: tcp_recv_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd3610)
Location: net/ipv4/tcp.c:2223
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81fd3610-ffffffff81fd381b: tcp_recv_timestamp (STB_GLOBAL)
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
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c6f0c8)
Location: net/ipv4/tcp.c:1855
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffff800010c6f0c8-ffff800010c6f228: tcp_recv_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d7dc80)
Location: net/ipv4/tcp.c:1855
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
c0d7dc80-c0d7de4c: tcp_recv_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d75410)
Location: net/ipv4/tcp.c:1855
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
c000000000d75410-c000000000d75604: tcp_recv_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d3e40)
Location: net/ipv4/tcp.c:1855
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffe0007d3e40-ffffffe0007d3f5a: tcp_recv_timestamp (STB_LOCAL)
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
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8195cc90)
Location: net/ipv4/tcp.c:1855
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff8195cc90-ffffffff8195ce5d: tcp_recv_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81916780)
Location: net/ipv4/tcp.c:1855
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81916780-ffffffff8191694d: tcp_recv_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c7460)
Location: net/ipv4/tcp.c:1855
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff819c7460-ffffffff819c762d: tcp_recv_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr *msg, const struct sock *sk, struct scm_timestamping_internal *tss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d0fb0)
Location: net/ipv4/tcp.c:1855
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff819d0fb0-ffffffff819d117d: tcp_recv_timestamp (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
