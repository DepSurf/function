# Function: <code>kernel_sendmsg_locked</code>

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
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81826040)
Location: net/socket.c:660
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff81826040-ffffffff818260a7: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186f920)
Location: net/socket.c:664
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff8186f920-ffffffff8186f987: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890500)
Location: net/socket.c:644
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff81890500-ffffffff81890567: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818da380)
Location: net/socket.c:694
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff818da380-ffffffff818da3e8: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190c4d0)
Location: net/socket.c:694
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff8190c4d0-ffffffff8190c538: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de5c0)
Location: net/socket.c:709
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff819de5c0-ffffffff819de628: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de000)
Location: net/socket.c:709
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff819de000-ffffffff819de068: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c4010)
Location: net/socket.c:711
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff819c4010-ffffffff819c4078: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a732b0)
Location: net/socket.c:761
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81a732b0-ffffffff81a73318: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be5cb0)
Location: net/socket.c:771
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81be5cb0-ffffffff81be5d35: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d91ea0)
Location: net/socket.c:773
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81d91ea0-ffffffff81d91f25: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e00250)
Location: net/socket.c:788
Inline: False
```
**Symbols:**

```
ffffffff81e00250-ffffffff81e002d1: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebc7b0)
Location: net/socket.c:809
Inline: False
```
**Symbols:**

```
ffffffff81ebc7b0-ffffffff81ebc831: kernel_sendmsg_locked (STB_GLOBAL)
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
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba13b8)
Location: net/socket.c:694
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffff800010ba13b8-ffff800010ba1460: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc36cc)
Location: net/socket.c:694
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
c0cc36cc-c0cc3744: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c758c0)
Location: net/socket.c:694
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
c000000000c758c0-c000000000c75980: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073957c)
Location: net/socket.c:694
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffe00073957c-ffffffe0007395f6: kernel_sendmsg_locked (STB_GLOBAL)
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
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ac4d0)
Location: net/socket.c:694
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff818ac4d0-ffffffff818ac538: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81866420)
Location: net/socket.c:694
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff81866420-ffffffff81866488: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fd4d0)
Location: net/socket.c:694
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff818fd4d0-ffffffff818fd538: kernel_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_sendmsg_locked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191e540)
Location: net/socket.c:694
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage_locked
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff8191e540-ffffffff8191e5a8: kernel_sendmsg_locked (STB_GLOBAL)
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
