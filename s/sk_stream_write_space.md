# Function: <code>sk_stream_write_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8170e280)
Location: net/core/stream.c:28
Inline: False
```
**Symbols:**

```
ffffffff8170e280-ffffffff8170e32f: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817759b0)
Location: net/core/stream.c:28
Inline: False
```
**Symbols:**

```
ffffffff817759b0-ffffffff81775a67: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817a2f80)
Location: net/core/stream.c:28
Inline: False
```
**Symbols:**

```
ffffffff817a2f80-ffffffff817a3037: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff817c10d0)
Location: net/core/stream.c:29
Inline: False
```
**Symbols:**

```
ffffffff817c10d0-ffffffff817c1183: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8183aaf0)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
ffffffff8183aaf0-ffffffff8183aba9: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81885230)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
ffffffff81885230-ffffffff818852e8: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818a5960)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
ffffffff818a5960-ffffffff818a5a1d: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818f0c70)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
ffffffff818f0c70-ffffffff818f0d2d: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81922bd0)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
ffffffff81922bd0-ffffffff81922ca3: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819f6650)
Location: net/core/stream.c:30
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_clean_una
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:subflow_write_space
```
**Symbols:**

```
ffffffff819f6650-ffffffff819f6721: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819f6220)
Location: net/core/stream.c:30
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_clean_una
```
**Symbols:**

```
ffffffff819f6220-ffffffff819f6311: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff819dc3b0)
Location: net/core/stream.c:30
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/subflow.c:subflow_write_space
```
**Symbols:**

```
ffffffff819dc3b0-ffffffff819dc49c: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81a8c5f0)
Location: net/core/stream.c:30
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/subflow.c:subflow_write_space
```
**Symbols:**

```
ffffffff81a8c5f0-ffffffff81a8c6dc: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81c01e60)
Location: net/core/stream.c:30
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/subflow.c:subflow_write_space
```
**Symbols:**

```
ffffffff81c01e60-ffffffff81c01f6d: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81db1240)
Location: net/core/stream.c:30
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/subflow.c:subflow_write_space
```
**Symbols:**

```
ffffffff81db1240-ffffffff81db134d: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81e21750)
Location: net/core/stream.c:30
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/subflow.c:subflow_write_space
```
**Symbols:**

```
ffffffff81e21750-ffffffff81e2185d: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81edf670)
Location: net/core/stream.c:30
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_subflow_process_delegated
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_sk_clone_init
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_close_ssk
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
  - net/mptcp/protocol.c:mptcp_enter_memory_pressure
  - net/mptcp/subflow.c:subflow_write_space
  - net/mptcp/subflow.c:__mptcp_sync_state
```
**Symbols:**

```
ffffffff81edf670-ffffffff81edf77d: sk_stream_write_space (STB_GLOBAL)
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
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffff800010bbd840)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
ffff800010bbd840-ffff800010bbd92c: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (c0cd9998)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
c0cd9998-c0cd9a74: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (c000000000c96bc0)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
c000000000c96bc0-c000000000c96d08: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffe00074bc98)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
ffffffe00074bc98-ffffffe00074bd48: sk_stream_write_space (STB_GLOBAL)
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
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff818c2bd0)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
ffffffff818c2bd0-ffffffff818c2ca3: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff8187cb10)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
ffffffff8187cb10-ffffffff8187cbe3: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81913bd0)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
ffffffff81913bd0-ffffffff81913ca3: sk_stream_write_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sk_stream_write_space(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81934d60)
Location: net/core/stream.c:30
Inline: False
```
**Symbols:**

```
ffffffff81934d60-ffffffff81934e3f: sk_stream_write_space (STB_GLOBAL)
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
