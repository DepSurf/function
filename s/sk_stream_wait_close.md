# Function: <code>sk_stream_wait_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8170dfd0)
Location: net/core/stream.c:95
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff8170dfd0-ffffffff8170e0c7: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817756f0)
Location: net/core/stream.c:95
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff817756f0-ffffffff817757e7: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817a2960)
Location: net/core/stream.c:94
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff817a2960-ffffffff817a2a61: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817c0b60)
Location: net/core/stream.c:95
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff817c0b60-ffffffff817c0c61: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8183a580)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff8183a580-ffffffff8183a686: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81884cc0)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81884cc0-ffffffff81884dc6: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818a53e0)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff818a53e0-ffffffff818a54e6: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818f0720)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff818f0720-ffffffff818f081d: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81922670)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81922670-ffffffff8192276d: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/stream.c (ffffffff819f60d0)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819f60d0-ffffffff819f61bf: sk_stream_wait_close.part.0 (STB_LOCAL)
ffffffff819f61c0-ffffffff819f61d6: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/stream.c (ffffffff819f5b50)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff819f5b50-ffffffff819f5c49: sk_stream_wait_close.part.0 (STB_LOCAL)
ffffffff819f5c50-ffffffff819f5c66: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819dbcf0)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff819dbcf0-ffffffff819dbdf7: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/stream.c (ffffffff81a8bf42)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff81d3545d-ffffffff81d3549d: sk_stream_wait_close.cold (STB_LOCAL)
ffffffff81a8bef0-ffffffff81a8c009: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/stream.c (ffffffff81c017e0)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/mptcp/protocol.c:mptcp_close
```
**Symbols:**

```
ffffffff81f01979-ffffffff81f019b9: sk_stream_wait_close.cold (STB_LOCAL)
ffffffff81c01780-ffffffff81c018a7: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/stream.c (ffffffff81db0b80)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/mptcp/protocol.c:__mptcp_close
```
**Symbols:**

```
ffffffff820aadb9-ffffffff820aadf9: sk_stream_wait_close.cold (STB_LOCAL)
ffffffff81db0b20-ffffffff81db0c47: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/stream.c (ffffffff81e21043)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/mptcp/protocol.c:__mptcp_close
```
**Symbols:**

```
ffffffff8212c41f-ffffffff8212c451: sk_stream_wait_close.cold (STB_LOCAL)
ffffffff81e20fe0-ffffffff81e21127: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/stream.c (ffffffff81edf587)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:__tcp_close
  - net/mptcp/protocol.c:__mptcp_close
```
**Symbols:**

```
ffffffff8220e198-ffffffff8220e1ca: sk_stream_wait_close.cold (STB_LOCAL)
ffffffff81edf520-ffffffff81edf657: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffff800010bbd048)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffff800010bbd048-ffff800010bbd15c: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (c0cd9140)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
c0cd9140-c0cd9278: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (c000000000c96220)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
c000000000c96220-c000000000c96384: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffe00074b870)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffe00074b870-ffffffe00074b94e: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818c2670)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff818c2670-ffffffff818c276d: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8187c5b0)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff8187c5b0-ffffffff8187c6ad: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81913670)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff81913670-ffffffff8191376d: sk_stream_wait_close (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_wait_close(struct sock *sk, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819347f0)
Location: net/core/stream.c:96
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_close
  - net/ipv4/tcp.c:tcp_close
```
**Symbols:**

```
ffffffff819347f0-ffffffff819348ed: sk_stream_wait_close (STB_GLOBAL)
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
