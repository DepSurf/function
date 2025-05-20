# Function: <code>ipv6_list_rcv</code>

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
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff819998c0)
Location: net/ipv6/ip6_input.c:286
Inline: False
```
**Symbols:**

```
ffffffff819998c0-ffffffff819999f7: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a057f0)
Location: net/ipv6/ip6_input.c:286
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81a057f0-ffffffff81a05925: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a3c370)
Location: net/ipv6/ip6_input.c:298
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81a3c370-ffffffff81a3c4a5: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81b31a30)
Location: net/ipv6/ip6_input.c:321
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81b31a30-ffffffff81b31b4e: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81b40630)
Location: net/ipv6/ip6_input.c:311
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81b40630-ffffffff81b4074e: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81b2ea70)
Location: net/ipv6/ip6_input.c:311
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81b2ea70-ffffffff81b2eb8e: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81bf4da0)
Location: net/ipv6/ip6_input.c:311
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81bf4da0-ffffffff81bf4ebe: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81d8dbd0)
Location: net/ipv6/ip6_input.c:323
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81d8dbd0-ffffffff81d8dd06: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81f5bd20)
Location: net/ipv6/ip6_input.c:323
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81f5bd20-ffffffff81f5be56: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81fbbad0)
Location: net/ipv6/ip6_input.c:323
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81fbbad0-ffffffff81fbbc06: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff82088f00)
Location: net/ipv6/ip6_input.c:324
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff82088f00-ffffffff82089036: ipv6_list_rcv (STB_GLOBAL)
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
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffff800010cfd640)
Location: net/ipv6/ip6_input.c:298
Inline: False
```
**Symbols:**

```
ffff800010cfd640-ffff800010cfd780: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (c0e04e54)
Location: net/ipv6/ip6_input.c:298
Inline: False
```
**Symbols:**

```
c0e04e54-c0e04f84: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (c000000000e25680)
Location: net/ipv6/ip6_input.c:298
Inline: False
```
**Symbols:**

```
c000000000e25680-c000000000e25838: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffe000847bf8)
Location: net/ipv6/ip6_input.c:298
Inline: False
```
**Symbols:**

```
ffffffe000847bf8-ffffffe000847cd6: ipv6_list_rcv (STB_GLOBAL)
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
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff819dba00)
Location: net/ipv6/ip6_input.c:298
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff819dba00-ffffffff819dbb35: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff819987c0)
Location: net/ipv6/ip6_input.c:298
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff819987c0-ffffffff819988f5: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a46480)
Location: net/ipv6/ip6_input.c:298
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81a46480-ffffffff81a465b5: ipv6_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff81a521b0)
Location: net/ipv6/ip6_input.c:298
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81a521b0-ffffffff81a522e5: ipv6_list_rcv (STB_GLOBAL)
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
