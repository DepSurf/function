# Function: <code>kernel_sendpage_locked</code>

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
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81827270)
Location: net/socket.c:3381
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff81827270-ffffffff8182729e: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81870610)
Location: net/socket.c:3345
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff81870610-ffffffff8187063e: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818911e0)
Location: net/socket.c:3411
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff818911e0-ffffffff8189120e: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818daed0)
Location: net/socket.c:3700
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff818daed0-ffffffff818daefe: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190d020)
Location: net/socket.c:3781
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff8190d020-ffffffff8190d04e: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819ded60)
Location: net/socket.c:3660
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff819ded60-ffffffff819ded8e: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de5f0)
Location: net/socket.c:3654
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff819de5f0-ffffffff819de61e: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c4600)
Location: net/socket.c:3640
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_send_sock
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff819c4600-ffffffff819c462e: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a73750)
Location: net/socket.c:3525
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_send_sock
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81a73750-ffffffff81a7377e: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be6390)
Location: net/socket.c:3585
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_send_sock
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81be6390-ffffffff81be63dc: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d92670)
Location: net/socket.c:3573
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_send_sock
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81d92670-ffffffff81d926bc: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba1ee0)
Location: net/socket.c:3781
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffff800010ba1ee0-ffff800010ba1f64: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc3f4c)
Location: net/socket.c:3781
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
c0cc3f4c-c0cc3f98: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c76be0)
Location: net/socket.c:3781
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
c000000000c76be0-c000000000c76c4c: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073a01a)
Location: net/socket.c:3781
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffe00073a01a-ffffffe00073a074: kernel_sendpage_locked (STB_GLOBAL)
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
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ad020)
Location: net/socket.c:3781
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff818ad020-ffffffff818ad04e: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81866f70)
Location: net/socket.c:3781
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff81866f70-ffffffff81866f9e: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fe020)
Location: net/socket.c:3781
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff818fe020-ffffffff818fe04e: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_sendpage_locked(struct sock *sk, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191f0b0)
Location: net/socket.c:3781
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock_locked
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
**Symbols:**

```
ffffffff8191f0b0-ffffffff8191f0de: kernel_sendpage_locked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
