# Function: <code>tcp6_gro_receive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff **tcp6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff818012e0)
Location: net/ipv6/tcpv6_offload.c:18
Inline: False
```
**Symbols:**

```
ffffffff818012e0-ffffffff818014a3: tcp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff **tcp6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff81872b20)
Location: net/ipv6/tcpv6_offload.c:18
Inline: False
```
**Symbols:**

```
ffffffff81872b20-ffffffff81872cda: tcp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff **tcp6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff818a7140)
Location: net/ipv6/tcpv6_offload.c:18
Inline: False
```
**Symbols:**

```
ffffffff818a7140-ffffffff818a72fa: tcp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff **tcp6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff818cdbb0)
Location: net/ipv6/tcpv6_offload.c:18
Inline: False
```
**Symbols:**

```
ffffffff818cdbb0-ffffffff818cdd46: tcp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff **tcp6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff819529b0)
Location: net/ipv6/tcpv6_offload.c:18
Inline: False
```
**Symbols:**

```
ffffffff819529b0-ffffffff81952b46: tcp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff **tcp6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff819abf60)
Location: net/ipv6/tcpv6_offload.c:18
Inline: False
```
**Symbols:**

```
ffffffff819abf60-ffffffff819ac0ec: tcp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff819e2b40)
Location: net/ipv6/tcpv6_offload.c:20
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff819e2b40-ffffffff819e2ccd: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff81a51880)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81a51880-ffffffff81a51a39: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff81a88480)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81a88480-ffffffff81a88639: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff81b83a20)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81b83a20-ffffffff81b83bda: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff81b930e0)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81b930e0-ffffffff81b93288: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff81b82170)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81b82170-ffffffff81b82327: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff81c4e220)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81c4e220-ffffffff81c4e3d7: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff81deeae0)
Location: net/ipv6/tcpv6_offload.c:17
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81deeae0-ffffffff81deec81: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff81fc2b30)
Location: net/ipv6/tcpv6_offload.c:17
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81fc2b30-ffffffff81fc2cd1: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff82023ac0)
Location: net/ipv6/tcpv6_offload.c:17
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff82023ac0-ffffffff82023c5f: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff820f2c20)
Location: net/ipv6/tcpv6_offload.c:17
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff820f2c20-ffffffff820f2dbf: tcp6_gro_receive (STB_GLOBAL)
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
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffff800010d55028)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
```
**Symbols:**

```
ffff800010d55028-ffff800010d551e0: tcp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (c0e555d4)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
```
**Symbols:**

```
c0e555d4-c0e55774: tcp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (c000000000e8dd40)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
```
**Symbols:**

```
c000000000e8dd40-c000000000e8df60: tcp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffe00088c896)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
```
**Symbols:**

```
ffffffe00088c896-ffffffe00088ca0a: tcp6_gro_receive (STB_LOCAL)
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
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff81a27b10)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81a27b10-ffffffff81a27cc9: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff819e48d0)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff819e48d0-ffffffff819e4a89: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff81a936c0)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81a936c0-ffffffff81a93879: tcp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *tcp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcpv6_offload.c (ffffffff81a9f810)
Location: net/ipv6/tcpv6_offload.c:16
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81a9f810-ffffffff81a9f9c9: tcp6_gro_receive (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sk_buff **head</code> ➡️ <code>struct list_head *head</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct sk_buff **</code> ➡️ <code>struct sk_buff *</code>
</li>
</ul>
</details>
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
