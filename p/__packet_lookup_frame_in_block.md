# Function: <code>__packet_lookup_frame_in_block</code>

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
In net/packet/af_packet.c (ffffffff81806bab)
Location: net/packet/af_packet.c:1041
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff81877656)
Location: net/packet/af_packet.c:1041
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff818aae66)
Location: net/packet/af_packet.c:1040
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff818d414e)
Location: net/packet/af_packet.c:1047
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff81958b9e)
Location: net/packet/af_packet.c:1035
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff819b2bc3)
Location: net/packet/af_packet.c:1011
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff819e9b27)
Location: net/packet/af_packet.c:1012
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff81a57f67)
Location: net/packet/af_packet.c:1004
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff81a90553)
Location: net/packet/af_packet.c:1005
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__packet_lookup_frame_in_block(struct packet_sock *po, struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b86880)
Location: net/packet/af_packet.c:1008
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81b86880-ffffffff81b869a0: __packet_lookup_frame_in_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__packet_lookup_frame_in_block(struct packet_sock *po, struct sk_buff *skb, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b961b0)
Location: net/packet/af_packet.c:1012
Inline: False
Direct callers:
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81b961b0-ffffffff81b962d0: __packet_lookup_frame_in_block (STB_LOCAL)
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
In net/packet/af_packet.c (ffffffff81b85108)
Location: net/packet/af_packet.c:1013
Inline: True
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
In net/packet/af_packet.c (ffffffff81c56ce4)
Location: net/packet/af_packet.c:1014
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff81df60cd)
Location: net/packet/af_packet.c:1050
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff81fca61d)
Location: net/packet/af_packet.c:1050
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff8202afa4)
Location: net/packet/af_packet.c:1052
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff820faaab)
Location: net/packet/af_packet.c:1052
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffff800010d5dd40)
Location: net/packet/af_packet.c:1005
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (c0e5c888)
Location: net/packet/af_packet.c:1005
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (c000000000e96a50)
Location: net/packet/af_packet.c:1005
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffe000893adc)
Location: net/packet/af_packet.c:1005
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff81a2fbe3)
Location: net/packet/af_packet.c:1005
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff819ecdd3)
Location: net/packet/af_packet.c:1005
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff81a9b793)
Location: net/packet/af_packet.c:1005
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
In net/packet/af_packet.c (ffffffff81aa5f85)
Location: net/packet/af_packet.c:1005
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
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
