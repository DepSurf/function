# Function: <code>tcp_add_backlog</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8181b290)
Location: net/ipv4/tcp_ipv4.c:1546
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8181b290-ffffffff8181b3be: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8183ba40)
Location: net/ipv4/tcp_ipv4.c:1599
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8183ba40-ffffffff8183bb58: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818bb470)
Location: net/ipv4/tcp_ipv4.c:1553
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff818bb470-ffffffff818bb588: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81910f20)
Location: net/ipv4/tcp_ipv4.c:1615
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81910f20-ffffffff81911021: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193f4c0)
Location: net/ipv4/tcp_ipv4.c:1625
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8193f4c0-ffffffff8193f930: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a38a0)
Location: net/ipv4/tcp_ipv4.c:1626
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff819a38a0-ffffffff819a3d2d: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819da5a0)
Location: net/ipv4/tcp_ipv4.c:1648
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff819da5a0-ffffffff819daa2f: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac7760)
Location: net/ipv4/tcp_ipv4.c:1725
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81ac7760-ffffffff81ac7be9: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad3180)
Location: net/ipv4/tcp_ipv4.c:1760
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81ad3180-ffffffff81ad3605: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abe210)
Location: net/ipv4/tcp_ipv4.c:1778
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81abe210-ffffffff81abe697: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1801
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81d3b82a-ffffffff81d3b83e: tcp_add_backlog.cold (STB_LOCAL)
ffffffff81b7bcd0-ffffffff81b7c1c1: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb, enum skb_drop_reason *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1746
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81f0809e-ffffffff81f080b3: tcp_add_backlog.cold (STB_LOCAL)
ffffffff81d0bbd0-ffffffff81d0c100: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb, enum skb_drop_reason *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1809
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff820afad5-ffffffff820afaea: tcp_add_backlog.cold (STB_LOCAL)
ffffffff81ed0af0-ffffffff81ed1022: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb, enum skb_drop_reason *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1816
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff82130ea7-ffffffff82130ebc: tcp_add_backlog.cold (STB_LOCAL)
ffffffff81f302b0-ffffffff81f307f4: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb, enum skb_drop_reason *reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_ipv4.c (0)
Location: net/ipv4/tcp_ipv4.c:1994
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff82212811-ffffffff82212826: tcp_add_backlog.cold (STB_LOCAL)
ffffffff81ff6140-ffffffff81ff6709: tcp_add_backlog (STB_GLOBAL)
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
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8d978)
Location: net/ipv4/tcp_ipv4.c:1648
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffff800010c8d978-ffff800010c8de28: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d9c698)
Location: net/ipv4/tcp_ipv4.c:1648
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
c0d9c698-c0d9cb10: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d9b160)
Location: net/ipv4/tcp_ipv4.c:1648
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
c000000000d9b160-c000000000d9b744: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007edece)
Location: net/ipv4/tcp_ipv4.c:1648
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffe0007edece-ffffffe0007ee2fe: tcp_add_backlog (STB_GLOBAL)
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
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8197a410)
Location: net/ipv4/tcp_ipv4.c:1648
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff8197a410-ffffffff8197a89f: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81933ed0)
Location: net/ipv4/tcp_ipv4.c:1648
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff81933ed0-ffffffff8193435f: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e4be0)
Location: net/ipv4/tcp_ipv4.c:1648
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff819e4be0-ffffffff819e506f: tcp_add_backlog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tcp_add_backlog(struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819edf40)
Location: net/ipv4/tcp_ipv4.c:1648
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
```
**Symbols:**

```
ffffffff819edf40-ffffffff819ee3cb: tcp_add_backlog (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum skb_drop_reason *reason</code>
</li>
</ul>
</details>
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
