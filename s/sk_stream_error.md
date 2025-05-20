# Function: <code>sk_stream_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8170e0d0)
Location: net/core/stream.c:180
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff8170e0d0-ffffffff8170e127: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817757f0)
Location: net/core/stream.c:180
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff817757f0-ffffffff81775847: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817a2a70)
Location: net/core/stream.c:179
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff817a2a70-ffffffff817a2ac7: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817c0b00)
Location: net/core/stream.c:180
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
```
**Symbols:**

```
ffffffff817c0b00-ffffffff817c0b57: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8183a520)
Location: net/core/stream.c:181
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
**Symbols:**

```
ffffffff8183a520-ffffffff8183a577: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81884c60)
Location: net/core/stream.c:181
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
**Symbols:**

```
ffffffff81884c60-ffffffff81884cb7: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818a5380)
Location: net/core/stream.c:181
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff818a5380-ffffffff818a53d7: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818f06c0)
Location: net/core/stream.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff818f06c0-ffffffff818f071e: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81922610)
Location: net/core/stream.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81922610-ffffffff8192266e: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819f5eb0)
Location: net/core/stream.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff819f5eb0-ffffffff819f5f12: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819f59b0)
Location: net/core/stream.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff819f59b0-ffffffff819f5a12: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819dbb50)
Location: net/core/stream.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff819dbb50-ffffffff819dbbb2: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81a8be80)
Location: net/core/stream.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81a8be80-ffffffff81a8bee2: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81c01600)
Location: net/core/stream.c:183
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81c01600-ffffffff81c01671: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81db0980)
Location: net/core/stream.c:184
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81db0980-ffffffff81db09f1: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81e20e40)
Location: net/core/stream.c:184
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81e20e40-ffffffff81e20eb1: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81eded10)
Location: net/core/stream.c:186
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81eded10-ffffffff81eded81: sk_stream_error (STB_GLOBAL)
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
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffff800010bbd308)
Location: net/core/stream.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffff800010bbd308-ffff800010bbd3a4: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (c0cd9278)
Location: net/core/stream.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c0cd9278-c0cd9308: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (c000000000c96150)
Location: net/core/stream.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c000000000c96150-c000000000c96218: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffe00074b7f6)
Location: net/core/stream.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffe00074b7f6-ffffffe00074b870: sk_stream_error (STB_GLOBAL)
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
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818c2610)
Location: net/core/stream.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff818c2610-ffffffff818c266e: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8187c550)
Location: net/core/stream.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff8187c550-ffffffff8187c5ae: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81913610)
Location: net/core/stream.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81913610-ffffffff8191366e: sk_stream_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sk_stream_error(struct sock *sk, int flags, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81934790)
Location: net/core/stream.c:183
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81934790-ffffffff819347ee: sk_stream_error (STB_GLOBAL)
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
