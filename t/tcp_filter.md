# Function: <code>tcp_filter</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818189e0)
Location: net/ipv4/tcp_ipv4.c:1574
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
```
**Symbols:**

```
ffffffff818189e0-ffffffff81818a24: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81839000)
Location: net/ipv4/tcp_ipv4.c:1626
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81839000-ffffffff81839044: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818b8880)
Location: net/ipv4/tcp_ipv4.c:1580
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff818b8880-ffffffff818b88c4: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8190deb0)
Location: net/ipv4/tcp_ipv4.c:1642
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8190deb0-ffffffff8190defb: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819408c4)
Location: net/ipv4/tcp_ipv4.c:1734
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8193c2a0-ffffffff8193c2c4: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a4e1c)
Location: net/ipv4/tcp_ipv4.c:1746
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff819a06e0-ffffffff819a0704: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819dbb1c)
Location: net/ipv4/tcp_ipv4.c:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff819d72a0-ffffffff819d72c4: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8c8d)
Location: net/ipv4/tcp_ipv4.c:1845
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81ac4230-ffffffff81ac4254: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4c2d)
Location: net/ipv4/tcp_ipv4.c:1881
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81acfd10-ffffffff81acfd34: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abfcc4)
Location: net/ipv4/tcp_ipv4.c:1899
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81abae40-ffffffff81abae64: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d866)
Location: net/ipv4/tcp_ipv4.c:1923
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81b78190-ffffffff81b781b4: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d839)
Location: net/ipv4/tcp_ipv4.c:1870
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81d07df0-ffffffff81d07e1e: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ed3264)
Location: net/ipv4/tcp_ipv4.c:1935
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81ecc880-ffffffff81ecc8ae: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f31f69)
Location: net/ipv4/tcp_ipv4.c:1942
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81f2b560-ffffffff81f2b58e: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7f6f)
Location: net/ipv4/tcp_ipv4.c:2121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81ff0240-ffffffff81ff026e: tcp_filter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8ee40)
Location: net/ipv4/tcp_ipv4.c:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffff800010c8a2e0-ffff800010c8a324: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d9dd80)
Location: net/ipv4/tcp_ipv4.c:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
c0d99a24-c0d99a50: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d9d9fc)
Location: net/ipv4/tcp_ipv4.c:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
c000000000d97cb0-c000000000d97cf0: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef0e0)
Location: net/ipv4/tcp_ipv4.c:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffe0007eb240-ffffffe0007eb27e: tcp_filter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8197b98c)
Location: net/ipv4/tcp_ipv4.c:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81977110-ffffffff81977134: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193544c)
Location: net/ipv4/tcp_ipv4.c:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81930bd0-ffffffff81930bf4: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e615c)
Location: net/ipv4/tcp_ipv4.c:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff819e18e0-ffffffff819e1904: tcp_filter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tcp_filter(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819efe1c)
Location: net/ipv4/tcp_ipv4.c:1768
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff819eb610-ffffffff819eb634: tcp_filter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
