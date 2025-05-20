# Function: <code>sk_msg_recvmsg</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sk_msg_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4d890)
Location: net/core/skmsg.c:426
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81a4d890-ffffffff81a4dc17: sk_msg_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sk_msg_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b06130)
Location: net/core/skmsg.c:403
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81b06130-ffffffff81b064e0: sk_msg_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sk_msg_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8bee0)
Location: net/core/skmsg.c:412
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81c8bee0-ffffffff81c8c2f4: sk_msg_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sk_msg_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e47060)
Location: net/core/skmsg.c:411
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81e47060-ffffffff81e474d9: sk_msg_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sk_msg_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea2af0)
Location: net/core/skmsg.c:412
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
**Symbols:**

```
ffffffff81ea2af0-ffffffff81ea2f13: sk_msg_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sk_msg_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f64e20)
Location: net/core/skmsg.c:412
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser
```
**Symbols:**

```
ffffffff81f64e20-ffffffff81f65240: sk_msg_recvmsg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
