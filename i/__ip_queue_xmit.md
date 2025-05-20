# Function: <code>__ip_queue_xmit</code>

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
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8191b2c0)
Location: net/ipv4/ip_output.c:426
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:ip_queue_xmit
  - net/ipv6/tcp_ipv6.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff8191b2c0-ffffffff8191b6ed: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197d560)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:ip_queue_xmit
  - net/ipv6/tcp_ipv6.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff8197d560-ffffffff8197d9a4: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819b3f00)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:ip_queue_xmit
  - net/ipv6/tcp_ipv6.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff819b3f00-ffffffff819b4344: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9e030)
Location: net/ipv4/ip_output.c:452
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:ip_queue_xmit
  - net/ipv6/tcp_ipv6.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff81a9e030-ffffffff81a9e44a: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81aa7f10)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff81aa7f10-ffffffff81aa833e: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a92f20)
Location: net/ipv4/ip_output.c:454
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff81a92f20-ffffffff81a93323: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81b4e320)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff81b4e320-ffffffff81b4e754: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81cdbbe0)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff81cdbbe0-ffffffff81cdc03f: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81e9c5e0)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff81e9c5e0-ffffffff81e9ca3f: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81efb1d0)
Location: net/ipv4/ip_output.c:455
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff81efb1d0-ffffffff81efb66d: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81fbf0e0)
Location: net/ipv4/ip_output.c:456
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff81fbf0e0-ffffffff81fbf5b7: __ip_queue_xmit (STB_GLOBAL)
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
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffff800010c646e8)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:ip_queue_xmit
  - net/ipv6/tcp_ipv6.c:ip_queue_xmit
```
**Symbols:**

```
ffff800010c646e8-ffff800010c64a68: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c0d74218)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:ip_queue_xmit
  - net/ipv6/tcp_ipv6.c:ip_queue_xmit
```
**Symbols:**

```
c0d74218-c0d74644: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (c000000000d687e0)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:ip_queue_xmit
  - net/ipv6/tcp_ipv6.c:ip_queue_xmit
```
**Symbols:**

```
c000000000d687e0-c000000000d68ca4: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffe0007cc042)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:ip_queue_xmit
  - net/ipv6/tcp_ipv6.c:ip_queue_xmit
```
**Symbols:**

```
ffffffe0007cc042-ffffffe0007cc3f0: __ip_queue_xmit (STB_GLOBAL)
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
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81953d70)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:ip_queue_xmit
  - net/ipv6/tcp_ipv6.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff81953d70-ffffffff819541b4: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8190d860)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:ip_queue_xmit
  - net/ipv6/tcp_ipv6.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff8190d860-ffffffff8190dca4: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819be540)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:ip_queue_xmit
  - net/ipv6/tcp_ipv6.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff819be540-ffffffff819be984: __ip_queue_xmit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ip_queue_xmit(struct sock *sk, struct sk_buff *skb, struct flowi *fl, __u8 tos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff819c7e70)
Location: net/ipv4/ip_output.c:453
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:ip_queue_xmit
  - net/ipv6/tcp_ipv6.c:ip_queue_xmit
```
**Symbols:**

```
ffffffff819c7e70-ffffffff819c82b0: __ip_queue_xmit (STB_GLOBAL)
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
