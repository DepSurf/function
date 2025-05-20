# Function: <code>netpoll_send_skb</code>

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
In net/core/netpoll.c (ffffffff81739588)
Location: include/linux/netpoll.h:67
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffff817a583c)
Location: include/linux/netpoll.h:67
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffff817d42ac)
Location: include/linux/netpoll.h:67
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffff817f35ee)
Location: include/linux/netpoll.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffff8186e9de)
Location: include/linux/netpoll.h:69
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffff818bfb65)
Location: include/linux/netpoll.h:69
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffff818e8985)
Location: include/linux/netpoll.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffff81938197)
Location: include/linux/netpoll.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffff8196b057)
Location: include/linux/netpoll.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
netdev_tx_t netpoll_send_skb(struct netpoll *np, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81a3e8f0)
Location: net/core/netpoll.c:365
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_send_udp
```
**Symbols:**

```
ffffffff81a3e8f0-ffffffff81a3e94a: netpoll_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
netdev_tx_t netpoll_send_skb(struct netpoll *np, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81a41690)
Location: net/core/netpoll.c:366
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_send_udp
```
**Symbols:**

```
ffffffff81a41690-ffffffff81a416ea: netpoll_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
netdev_tx_t netpoll_send_skb(struct netpoll *np, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81a26628)
Location: net/core/netpoll.c:365
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
**Symbols:**

```
ffffffff81a26300-ffffffff81a26365: netpoll_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
netdev_tx_t netpoll_send_skb(struct netpoll *np, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81adb3a3)
Location: net/core/netpoll.c:366
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
**Symbols:**

```
ffffffff81adb070-ffffffff81adb0d5: netpoll_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
netdev_tx_t netpoll_send_skb(struct netpoll *np, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81c5c540)
Location: net/core/netpoll.c:366
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_send_udp
```
**Symbols:**

```
ffffffff81c5c540-ffffffff81c5c5a9: netpoll_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
netdev_tx_t netpoll_send_skb(struct netpoll *np, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81e12c00)
Location: net/core/netpoll.c:366
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_send_udp
```
**Symbols:**

```
ffffffff81e12c00-ffffffff81e12c86: netpoll_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
netdev_tx_t netpoll_send_skb(struct netpoll *np, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81e86520)
Location: net/core/netpoll.c:383
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_send_udp
```
**Symbols:**

```
ffffffff81e86520-ffffffff81e865a6: netpoll_send_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
netdev_tx_t netpoll_send_skb(struct netpoll *np, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81f48530)
Location: net/core/netpoll.c:383
Inline: False
Direct callers:
  - net/core/netpoll.c:netpoll_send_udp
```
**Symbols:**

```
ffffffff81f48530-ffffffff81f485b6: netpoll_send_skb (STB_GLOBAL)
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
In net/core/netpoll.c (ffff800010c11634)
Location: include/linux/netpoll.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (c0d29584)
Location: include/linux/netpoll.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (c000000000cfe34c)
Location: include/linux/netpoll.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffe00078d84e)
Location: include/linux/netpoll.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffff8190b027)
Location: include/linux/netpoll.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffff818c4dc2)
Location: include/linux/netpoll.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffff8195c057)
Location: include/linux/netpoll.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In net/core/netpoll.c (ffffffff8197e437)
Location: include/linux/netpoll.h:68
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
