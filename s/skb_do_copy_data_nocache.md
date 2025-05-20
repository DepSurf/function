# Function: <code>skb_do_copy_data_nocache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817698e8)
Location: include/net/sock.h:1801
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d629a)
Location: include/net/sock.h:1771
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81806292)
Location: include/net/sock.h:1833
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81826e0d)
Location: include/net/sock.h:1858
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a468f)
Location: include/net/sock.h:1872
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818fa876)
Location: include/net/sock.h:1874
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81928737)
Location: include/net/sock.h:1959
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8198b6ae)
Location: include/net/sock.h:1971
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c1ef4)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int skb_do_copy_data_nocache(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, char *to, int copy, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aac540)
Location: include/net/sock.h:2030
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81aac540-ffffffff81aac651: skb_do_copy_data_nocache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int skb_do_copy_data_nocache(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, char *to, int copy, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab3e90)
Location: include/net/sock.h:2049
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81ab3e90-ffffffff81ab3fa1: skb_do_copy_data_nocache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int skb_do_copy_data_nocache(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, char *to, int copy, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9f000)
Location: include/net/sock.h:2066
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81a9f000-ffffffff81a9f111: skb_do_copy_data_nocache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int skb_do_copy_data_nocache(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, char *to, int copy, int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5a130)
Location: include/net/sock.h:2106
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81b5a130-ffffffff81b5a27c: skb_do_copy_data_nocache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_do_copy_data_nocache(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, char *to, int copy, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ce8470)
Location: include/net/sock.h:2224
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81ce8470-ffffffff81ce85bc: skb_do_copy_data_nocache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_do_copy_data_nocache(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, char *to, int copy, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eabdc0)
Location: include/net/sock.h:2261
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81eabdc0-ffffffff81eabf0c: skb_do_copy_data_nocache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_do_copy_data_nocache(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, char *to, int copy, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f0a580)
Location: include/net/sock.h:2249
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81f0a580-ffffffff81f0a6cc: skb_do_copy_data_nocache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_do_copy_data_nocache(struct sock *sk, struct sk_buff *skb, struct iov_iter *from, char *to, int copy, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fce580)
Location: include/net/sock.h:2239
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
**Symbols:**

```
ffffffff81fce580-ffffffff81fce6cb: skb_do_copy_data_nocache (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c74c4c)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d833c4)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7c1e4)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d8096)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81961d64)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8191b854)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819cc534)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d60c4)
Location: include/net/sock.h:1981
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
  - net/ipv4/tcp.c:tcp_sendmsg_locked
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
