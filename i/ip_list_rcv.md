# Function: <code>ip_list_rcv</code>

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
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81915a90)
Location: net/ipv4/ip_input.c:585
Inline: False
```
**Symbols:**

```
ffffffff81915a90-ffffffff81915bc4: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81978020)
Location: net/ipv4/ip_input.c:584
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81978020-ffffffff8197814e: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819ae990)
Location: net/ipv4/ip_input.c:584
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff819ae990-ffffffff819aeabe: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a98820)
Location: net/ipv4/ip_input.c:612
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81a98820-ffffffff81a98938: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81aa27b0)
Location: net/ipv4/ip_input.c:612
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81aa27b0-ffffffff81aa28c8: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a8d890)
Location: net/ipv4/ip_input.c:613
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81a8d890-ffffffff81a8d9a8: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81b48a60)
Location: net/ipv4/ip_input.c:613
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81b48a60-ffffffff81b48b78: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81cd5e70)
Location: net/ipv4/ip_input.c:637
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81cd5e70-ffffffff81cd5fa3: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81e96330)
Location: net/ipv4/ip_input.c:642
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81e96330-ffffffff81e96463: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81ef4b60)
Location: net/ipv4/ip_input.c:642
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81ef4b60-ffffffff81ef4c93: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81fb8b00)
Location: net/ipv4/ip_input.c:643
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff81fb8b00-ffffffff81fb8c33: ip_list_rcv (STB_GLOBAL)
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
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffff800010c5ef08)
Location: net/ipv4/ip_input.c:584
Inline: False
```
**Symbols:**

```
ffff800010c5ef08-ffff800010c5f044: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (c0d6e620)
Location: net/ipv4/ip_input.c:584
Inline: False
```
**Symbols:**

```
c0d6e620-c0d6e748: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (c000000000d61a50)
Location: net/ipv4/ip_input.c:584
Inline: False
```
**Symbols:**

```
c000000000d61a50-c000000000d61bf8: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffe0007c7458)
Location: net/ipv4/ip_input.c:584
Inline: False
```
**Symbols:**

```
ffffffe0007c7458-ffffffe0007c7534: ip_list_rcv (STB_GLOBAL)
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
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff8194e800)
Location: net/ipv4/ip_input.c:584
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff8194e800-ffffffff8194e92e: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819082f0)
Location: net/ipv4/ip_input.c:584
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff819082f0-ffffffff8190841e: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819b8fd0)
Location: net/ipv4/ip_input.c:584
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff819b8fd0-ffffffff819b90fe: ip_list_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip_list_rcv(struct list_head *head, struct packet_type *pt, struct net_device *orig_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff819c28c0)
Location: net/ipv4/ip_input.c:584
Inline: False
Direct callers:
  - net/core/dev.c:__netif_receive_skb_list_core
  - net/core/dev.c:__netif_receive_skb_list_core
```
**Symbols:**

```
ffffffff819c28c0-ffffffff819c29ee: ip_list_rcv (STB_GLOBAL)
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
