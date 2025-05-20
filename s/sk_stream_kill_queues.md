# Function: <code>sk_stream_kill_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8170e130)
Location: net/core/stream.c:190
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff8170e130-ffffffff8170e280: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81775850)
Location: net/core/stream.c:190
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff81775850-ffffffff817759ac: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817a2ad0)
Location: net/core/stream.c:189
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff817a2ad0-ffffffff817a2c2c: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817c0c70)
Location: net/core/stream.c:190
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff817c0c70-ffffffff817c0d85: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8183a690)
Location: net/core/stream.c:191
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff8183a690-ffffffff8183a7a5: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81884dd0)
Location: net/core/stream.c:191
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff81884dd0-ffffffff81884ee5: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818a5840)
Location: net/core/stream.c:191
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff818a5840-ffffffff818a5955: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/stream.c (0)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff818f0d2d-ffffffff818f0d66: sk_stream_kill_queues.cold (STB_LOCAL)
ffffffff818f0b60-ffffffff818f0c68: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81922ab0)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff81922ab0-ffffffff81922bc5: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819f61e0)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff819f61e0-ffffffff819f6303: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819f5a20)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/mptcp/protocol.c:__mptcp_destroy_sock
```
**Symbols:**

```
ffffffff819f5a20-ffffffff819f5b43: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819dbbc0)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/mptcp/protocol.c:__mptcp_destroy_sock
```
**Symbols:**

```
ffffffff819dbbc0-ffffffff819dbceb: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81a8bda0)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/mptcp/protocol.c:__mptcp_destroy_sock
```
**Symbols:**

```
ffffffff81a8bda0-ffffffff81a8be71: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81c01680)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/mptcp/protocol.c:__mptcp_destroy_sock
```
**Symbols:**

```
ffffffff81c01680-ffffffff81c01778: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81db0a10)
Location: net/core/stream.c:194
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/mptcp/protocol.c:__mptcp_destroy_sock
```
**Symbols:**

```
ffffffff81db0a10-ffffffff81db0b04: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81e20ed0)
Location: net/core/stream.c:194
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/mptcp/protocol.c:__mptcp_destroy_sock
```
**Symbols:**

```
ffffffff81e20ed0-ffffffff81e20fc4: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81ededa0)
Location: net/core/stream.c:196
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/mptcp/protocol.c:__mptcp_destroy_sock
```
**Symbols:**

```
ffffffff81ededa0-ffffffff81edee99: sk_stream_kill_queues (STB_GLOBAL)
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
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffff800010bbd3a8)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffff800010bbd3a8-ffff800010bbd4c8: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/stream.c (c0cd9834)
Location: net/core/stream.c:193
Inline: True
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
c0cd9834-c0cd9998: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (c000000000c96a30)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
c000000000c96a30-c000000000c96bb4: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffe00074bbb6)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffe00074bbb6-ffffffe00074bc98: sk_stream_kill_queues (STB_GLOBAL)
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
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818c2ab0)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff818c2ab0-ffffffff818c2bc5: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8187c9f0)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff8187c9f0-ffffffff8187cb05: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81913ab0)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff81913ab0-ffffffff81913bc5: sk_stream_kill_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sk_stream_kill_queues(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81934c40)
Location: net/core/stream.c:193
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
**Symbols:**

```
ffffffff81934c40-ffffffff81934d55: sk_stream_kill_queues (STB_GLOBAL)
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
