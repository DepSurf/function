# Function: <code>skb_send_sock_locked</code>

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
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81830770)
Location: net/core/skbuff.c:2264
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:smap_tx_work
  - net/core/skbuff.c:skb_send_sock
```
**Symbols:**

```
ffffffff81830770-ffffffff818309ee: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187ac30)
Location: net/core/skbuff.c:2280
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:smap_tx_work
  - net/core/skbuff.c:skb_send_sock
```
**Symbols:**

```
ffffffff8187ac30-ffffffff8187aeb1: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189b630)
Location: net/core/skbuff.c:2289
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff8189b630-ffffffff8189b8ab: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e5b90)
Location: net/core/skbuff.c:2448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff818e5b90-ffffffff818e5dfc: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917ce0)
Location: net/core/skbuff.c:2450
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81917ce0-ffffffff81917f5f: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea200)
Location: net/core/skbuff.c:2449
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/xfrm/espintcp.c:espintcp_push_msgs
```
**Symbols:**

```
ffffffff819ea200-ffffffff819ea46c: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819e9f30)
Location: net/core/skbuff.c:2466
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/xfrm/espintcp.c:espintcp_push_msgs
```
**Symbols:**

```
ffffffff819e9f30-ffffffff819ea19c: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d0740)
Location: net/core/skbuff.c:2622
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_push_msgs
```
**Symbols:**

```
ffffffff819d0740-ffffffff819d075e: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a80390)
Location: net/core/skbuff.c:2694
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_push_msgs
```
**Symbols:**

```
ffffffff81a80390-ffffffff81a803ae: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf4980)
Location: net/core/skbuff.c:2743
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_push_msgs
```
**Symbols:**

```
ffffffff81bf4980-ffffffff81bf49b0: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da2810)
Location: net/core/skbuff.c:2949
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_push_msgs
```
**Symbols:**

```
ffffffff81da2810-ffffffff81da2840: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e11240)
Location: net/core/skbuff.c:3121
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_push_msgs
```
**Symbols:**

```
ffffffff81e11240-ffffffff81e11266: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecdd70)
Location: net/core/skbuff.c:3209
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_push_msgs
```
**Symbols:**

```
ffffffff81ecdd70-ffffffff81ecdd96: skb_send_sock_locked (STB_GLOBAL)
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
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb1370)
Location: net/core/skbuff.c:2450
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffff800010bb1370-ffff800010bb15ac: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccee14)
Location: net/core/skbuff.c:2450
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
c0ccee14-c0ccf040: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c88810)
Location: net/core/skbuff.c:2450
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
c000000000c88810-c000000000c88b48: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000742d46)
Location: net/core/skbuff.c:2450
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffe000742d46-ffffffe000742f5c: skb_send_sock_locked (STB_GLOBAL)
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
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7ce0)
Location: net/core/skbuff.c:2450
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff818b7ce0-ffffffff818b7f5f: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81871c30)
Location: net/core/skbuff.c:2450
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81871c30-ffffffff81871eaf: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908ce0)
Location: net/core/skbuff.c:2450
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81908ce0-ffffffff81908f5f: skb_send_sock_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_send_sock_locked(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81929d90)
Location: net/core/skbuff.c:2450
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81929d90-ffffffff8192a00f: skb_send_sock_locked (STB_GLOBAL)
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
