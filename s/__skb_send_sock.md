# Function: <code>__skb_send_sock</code>

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
int __skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len, sendmsg_func sendmsg, sendpage_func sendpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d03e0)
Location: net/core/skbuff.c:2531
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff819d03e0-ffffffff819d0731: __skb_send_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len, sendmsg_func sendmsg, sendpage_func sendpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a80030)
Location: net/core/skbuff.c:2603
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff81a80030-ffffffff81a80381: __skb_send_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len, sendmsg_func sendmsg, sendpage_func sendpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf45a0)
Location: net/core/skbuff.c:2652
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff81bf45a0-ffffffff81bf4978: __skb_send_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len, sendmsg_func sendmsg, sendpage_func sendpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da2420)
Location: net/core/skbuff.c:2858
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff81da2420-ffffffff81da27f8: __skb_send_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len, sendmsg_func sendmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e10d10)
Location: net/core/skbuff.c:3022
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff81e10d10-ffffffff81e11223: __skb_send_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len, sendmsg_func sendmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecd840)
Location: net/core/skbuff.c:3110
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_send_sock
  - net/core/skbuff.c:skb_send_sock_locked
```
**Symbols:**

```
ffffffff81ecd840-ffffffff81ecdd53: __skb_send_sock (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>sendpage_func sendpage</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
