# Function: <code>tcp_v4_do_rcv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8177d8e0)
Location: net/ipv4/tcp_ipv4.c:1376
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff8177d8e0-ffffffff8177dadf: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff817ea560)
Location: net/ipv4/tcp_ipv4.c:1384
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff817ea560-ffffffff817ea75f: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8181b090)
Location: net/ipv4/tcp_ipv4.c:1390
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff8181b090-ffffffff8181b28f: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8183b800)
Location: net/ipv4/tcp_ipv4.c:1445
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff8183b800-ffffffff8183b9d2: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818bb230)
Location: net/ipv4/tcp_ipv4.c:1453
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff818bb230-ffffffff818bb405: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819108f0)
Location: net/ipv4/tcp_ipv4.c:1515
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff819108f0-ffffffff81910aca: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193f1a0)
Location: net/ipv4/tcp_ipv4.c:1525
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff8193f1a0-ffffffff8193f38e: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a36a0)
Location: net/ipv4/tcp_ipv4.c:1526
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff819a36a0-ffffffff819a389b: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819da2c0)
Location: net/ipv4/tcp_ipv4.c:1548
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff819da2c0-ffffffff819da4bb: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac7560)
Location: net/ipv4/tcp_ipv4.c:1625
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81ac7560-ffffffff81ac775b: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad2ea0)
Location: net/ipv4/tcp_ipv4.c:1660
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81ad2ea0-ffffffff81ad309b: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abdad0)
Location: net/ipv4/tcp_ipv4.c:1677
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81abdad0-ffffffff81abdcdd: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b7afa0)
Location: net/ipv4/tcp_ipv4.c:1696
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81b7afa0-ffffffff81b7b1e6: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d0b930)
Location: net/ipv4/tcp_ipv4.c:1638
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_backlog_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81d0b930-ffffffff81d0bbc7: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ed1890)
Location: net/ipv4/tcp_ipv4.c:1700
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_backlog_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81ed1890-ffffffff81ed1b27: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f30000)
Location: net/ipv4/tcp_ipv4.c:1707
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_backlog_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81f30000-ffffffff81f3029b: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff5e90)
Location: net/ipv4/tcp_ipv4.c:1885
Inline: False
Direct callers:
  - net/core/sock.c:__release_sock
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_backlog_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81ff5e90-ffffffff81ff612b: tcp_v4_do_rcv (STB_GLOBAL)
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
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8d330)
Location: net/ipv4/tcp_ipv4.c:1548
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffff800010c8d330-ffff800010c8d57c: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d9c488)
Location: net/ipv4/tcp_ipv4.c:1548
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
c0d9c488-c0d9c698: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d9c3f0)
Location: net/ipv4/tcp_ipv4.c:1548
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
c000000000d9c3f0-c000000000d9c708: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007ed78e)
Location: net/ipv4/tcp_ipv4.c:1548
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffe0007ed78e-ffffffe0007ed980: tcp_v4_do_rcv (STB_GLOBAL)
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
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8197a130)
Location: net/ipv4/tcp_ipv4.c:1548
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff8197a130-ffffffff8197a32b: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81933bf0)
Location: net/ipv4/tcp_ipv4.c:1548
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff81933bf0-ffffffff81933deb: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e4900)
Location: net/ipv4/tcp_ipv4.c:1548
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff819e4900-ffffffff819e4afb: tcp_v4_do_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_v4_do_rcv(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819eea40)
Location: net/ipv4/tcp_ipv4.c:1548
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff819eea40-ffffffff819eec3b: tcp_v4_do_rcv (STB_GLOBAL)
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
