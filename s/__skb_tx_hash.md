# Function: <code>__skb_tx_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u16 __skb_tx_hash(const struct net_device *dev, struct sk_buff *skb, unsigned int num_tx_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817154d0)
Location: net/core/dev.c:2378
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_pick_tx
```
**Symbols:**

```
ffffffff817154d0-ffffffff8171556d: __skb_tx_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u16 __skb_tx_hash(const struct net_device *dev, struct sk_buff *skb, unsigned int num_tx_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177d500)
Location: net/core/dev.c:2400
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_pick_tx
```
**Symbols:**

```
ffffffff8177d500-ffffffff8177d59e: __skb_tx_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u16 __skb_tx_hash(const struct net_device *dev, struct sk_buff *skb, unsigned int num_tx_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aaa30)
Location: net/core/dev.c:2532
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_pick_tx
```
**Symbols:**

```
ffffffff817aaa30-ffffffff817aaace: __skb_tx_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u16 __skb_tx_hash(const struct net_device *dev, struct sk_buff *skb, unsigned int num_tx_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c9080)
Location: net/core/dev.c:2547
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_pick_tx
```
**Symbols:**

```
ffffffff817c9080-ffffffff817c9120: __skb_tx_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u16 __skb_tx_hash(const struct net_device *dev, struct sk_buff *skb, unsigned int num_tx_queues);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81842d20)
Location: net/core/dev.c:2574
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_pick_tx
```
**Symbols:**

```
ffffffff81842d20-ffffffff81842dc0: __skb_tx_hash (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
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
</ul>
