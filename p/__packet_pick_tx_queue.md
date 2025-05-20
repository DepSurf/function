# Function: <code>__packet_pick_tx_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u16 __packet_pick_tx_queue(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81802a20)
Location: net/packet/af_packet.c:315
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_pick_tx_queue
```
**Symbols:**

```
ffffffff81802a20-ffffffff81802a3f: __packet_pick_tx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u16 __packet_pick_tx_queue(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818747ac)
Location: net/packet/af_packet.c:316
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_pick_tx_queue
```
**Symbols:**

```
ffffffff81873d00-ffffffff81873d1f: __packet_pick_tx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u16 __packet_pick_tx_queue(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818a8d9c)
Location: net/packet/af_packet.c:315
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_pick_tx_queue
```
**Symbols:**

```
ffffffff818a8380-ffffffff818a839f: __packet_pick_tx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u16 __packet_pick_tx_queue(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818cfa2b)
Location: net/packet/af_packet.c:315
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff818cebd0-ffffffff818cebef: __packet_pick_tx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u16 __packet_pick_tx_queue(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819549a4)
Location: net/packet/af_packet.c:310
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff81953a80-ffffffff81953a9f: __packet_pick_tx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u16 __packet_pick_tx_queue(struct net_device *dev, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819adb77)
Location: net/packet/af_packet.c:278
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff819ad4a0-ffffffff819ad4bf: __packet_pick_tx_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u16 __packet_pick_tx_queue(struct net_device *dev, struct sk_buff *skb, struct net_device *sb_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e450a)
Location: net/packet/af_packet.c:278
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_direct_xmit
```
**Symbols:**

```
ffffffff819e4490-ffffffff819e44a2: __packet_pick_tx_queue (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
<b>Param added. </b>
<code>struct net_device *sb_dev</code>
</li>
</ul>
</details>
</li>
</ul>
