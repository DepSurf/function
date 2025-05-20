# Function: <code>sk_stream_wait_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8170e330)
Location: net/core/stream.c:117
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff8170e330-ffffffff8170e626: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81775a70)
Location: net/core/stream.c:117
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81775a70-ffffffff81775dbd: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817a2c30)
Location: net/core/stream.c:116
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff817a2c30-ffffffff817a2f7c: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817c0d90)
Location: net/core/stream.c:117
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:do_tcp_sendpages
```
**Symbols:**

```
ffffffff817c0d90-ffffffff817c10c9: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8183a7b0)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
**Symbols:**

```
ffffffff8183a7b0-ffffffff8183aaed: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81884ef0)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
```
**Symbols:**

```
ffffffff81884ef0-ffffffff81885226: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818a54f0)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff818a54f0-ffffffff818a5832: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818f0820)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff818f0820-ffffffff818f0b54: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81922770)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81922770-ffffffff81922aae: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819f6310)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff819f6310-ffffffff819f6650: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819f5e30)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff819f5e30-ffffffff819f6212: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819dbfc0)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff819dbfc0-ffffffff819dc3a9: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81a8c200)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81a8c200-ffffffff81a8c5e9: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81c01aa0)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81c01aa0-ffffffff81c01e57: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81db0e60)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81db0e60-ffffffff81db122a: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81e21350)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81e21350-ffffffff81e21733: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81edf100)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81edf100-ffffffff81edf50e: sk_stream_wait_memory (STB_GLOBAL)
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
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffff800010bbd4c8)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffff800010bbd4c8-ffff800010bbd840: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (c0cd94ec)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c0cd94ec-c0cd9834: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (c000000000c965e0)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c000000000c965e0-c000000000c96a2c: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffe00074b94e)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffe00074b94e-ffffffe00074bbb6: sk_stream_wait_memory (STB_GLOBAL)
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
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818c2770)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff818c2770-ffffffff818c2aae: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8187c6b0)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff8187c6b0-ffffffff8187c9ee: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81913770)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81913770-ffffffff81913aae: sk_stream_wait_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sk_stream_wait_memory(struct sock *sk, long int *timeo_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819348f0)
Location: net/core/stream.c:118
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff819348f0-ffffffff81934c31: sk_stream_wait_memory (STB_GLOBAL)
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
