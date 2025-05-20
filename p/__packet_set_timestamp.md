# Function: <code>__packet_set_timestamp</code>

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
In net/packet/af_packet.c (ffffffff81804b70)
Location: net/packet/af_packet.c:458
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffff818755a0)
Location: net/packet/af_packet.c:459
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffff818a9a70)
Location: net/packet/af_packet.c:458
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffff818d0910)
Location: net/packet/af_packet.c:463
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffff81955840)
Location: net/packet/af_packet.c:458
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffff819add34)
Location: net/packet/af_packet.c:434
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffff819e46d0)
Location: net/packet/af_packet.c:435
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffff81a53896)
Location: net/packet/af_packet.c:427
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffff81a8a486)
Location: net/packet/af_packet.c:427
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__u32 __packet_set_timestamp(struct packet_sock *po, void *frame, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b869a0)
Location: net/packet/af_packet.c:427
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff81b869a0-ffffffff81b86a81: __packet_set_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__u32 __packet_set_timestamp(struct packet_sock *po, void *frame, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b963e0)
Location: net/packet/af_packet.c:431
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
```
**Symbols:**

```
ffffffff81b963e0-ffffffff81b964c1: __packet_set_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b8558a)
Location: net/packet/af_packet.c:432
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c5189a)
Location: net/packet/af_packet.c:433
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81df313a)
Location: net/packet/af_packet.c:469
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc7f46)
Location: net/packet/af_packet.c:469
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff82027996)
Location: net/packet/af_packet.c:471
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f71f6)
Location: net/packet/af_packet.c:471
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffff800010d57854)
Location: net/packet/af_packet.c:427
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (c0e5a6e8)
Location: net/packet/af_packet.c:427
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (c000000000e925e0)
Location: net/packet/af_packet.c:427
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffe00088efd2)
Location: net/packet/af_packet.c:427
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffff81a29b16)
Location: net/packet/af_packet.c:427
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffff819e6d06)
Location: net/packet/af_packet.c:427
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffff81a956c6)
Location: net/packet/af_packet.c:427
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
In net/packet/af_packet.c (ffffffff81aa2306)
Location: net/packet/af_packet.c:427
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_destruct_skb
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
</ul>
