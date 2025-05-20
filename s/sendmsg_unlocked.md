# Function: <code>sendmsg_unlocked</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sendmsg_unlocked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d06b0)
Location: net/core/skbuff.c:2507
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff819d0380-ffffffff819d03a2: sendmsg_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sendmsg_unlocked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a80300)
Location: net/core/skbuff.c:2579
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81a7ffd0-ffffffff81a7fff2: sendmsg_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sendmsg_unlocked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf4861)
Location: net/core/skbuff.c:2628
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81bf4520-ffffffff81bf4560: sendmsg_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sendmsg_unlocked(struct sock *sk, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da26e1)
Location: net/core/skbuff.c:2834
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81da2380-ffffffff81da23c0: sendmsg_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sendmsg_unlocked(struct sock *sk, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1106f)
Location: net/core/skbuff.c:3012
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81e10cc0-ffffffff81e10cf2: sendmsg_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sendmsg_unlocked(struct sock *sk, struct msghdr *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecdb9f)
Location: net/core/skbuff.c:3100
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81ecd7f0-ffffffff81ecd822: sendmsg_unlocked (STB_LOCAL)
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
<code>struct kvec *vec</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t num</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
