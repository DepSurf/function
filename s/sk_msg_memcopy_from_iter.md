# Function: <code>sk_msg_memcopy_from_iter</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e6ff0)
Location: net/core/skmsg.c:338
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff818e6ff0-ffffffff818e7169: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81936990)
Location: net/core/skmsg.c:347
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81936990-ffffffff81936afe: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81968e40)
Location: net/core/skmsg.c:356
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81968e40-ffffffff81968fc9: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3c840)
Location: net/core/skmsg.c:357
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81a3c840-ffffffff81a3c9ba: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3ef10)
Location: net/core/skmsg.c:359
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81a3ef10-ffffffff81a3f08a: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4d320)
Location: net/core/skmsg.c:359
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81a4d320-ffffffff81a4d49a: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b055a0)
Location: net/core/skmsg.c:359
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81b055a0-ffffffff81b0576e: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8ab40)
Location: net/core/skmsg.c:368
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81c8ab40-ffffffff81c8ad33: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e45c20)
Location: net/core/skmsg.c:367
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81e45c20-ffffffff81e45e13: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea1230)
Location: net/core/skmsg.c:368
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81ea1230-ffffffff81ea1423: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f63a30)
Location: net/core/skmsg.c:368
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81f63a30-ffffffff81f63c23: sk_msg_memcopy_from_iter (STB_GLOBAL)
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
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffff800010c0f4f8)
Location: net/core/skmsg.c:356
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffff800010c0f4f8-ffff800010c0f6d0: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c0d26cec)
Location: net/core/skmsg.c:356
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c0d26cec-c0d26ed8: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c000000000cfae10)
Location: net/core/skmsg.c:356
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c000000000cfae10-c000000000cfb0b8: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffe00078bfe6)
Location: net/core/skmsg.c:356
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffe00078bfe6-ffffffe00078c16c: sk_msg_memcopy_from_iter (STB_GLOBAL)
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
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81908e10)
Location: net/core/skmsg.c:356
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81908e10-ffffffff81908f99: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818c2c20)
Location: net/core/skmsg.c:356
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff818c2c20-ffffffff818c2da9: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81959e40)
Location: net/core/skmsg.c:356
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81959e40-ffffffff81959fc9: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sk_msg_memcopy_from_iter(struct sock *sk, struct iov_iter *from, struct sk_msg *msg, u32 bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8197c060)
Location: net/core/skmsg.c:356
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff8197c060-ffffffff8197c1e9: sk_msg_memcopy_from_iter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
