# Function: <code>__get_xps_queue_idx</code>

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
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ae3b0)
Location: net/core/dev.c:3624
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__netdev_pick_tx
```
**Symbols:**

```
ffffffff818ae3b0-ffffffff818ae458: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f9ce0)
Location: net/core/dev.c:3636
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff818f9ce0-ffffffff818f9d82: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192be40)
Location: net/core/dev.c:3536
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff8192be40-ffffffff8192bee2: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ff410)
Location: net/core/dev.c:3894
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff819ff410-ffffffff819ff4b2: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ff160)
Location: net/core/dev.c:3925
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff819ff160-ffffffff819ff202: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e5930)
Location: net/core/dev.c:4006
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff819e5930-ffffffff819e59d2: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a95de0)
Location: net/core/dev.c:3971
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff81a95de0-ffffffff81a95e82: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0c7b0)
Location: net/core/dev.c:4003
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff81c0c7b0-ffffffff81c0c86a: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbc5f0)
Location: net/core/dev.c:3990
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff81dbc5f0-ffffffff81dbc6aa: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2ce00)
Location: net/core/dev.c:3950
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff81e2ce00-ffffffff81e2ceba: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eeb140)
Location: net/core/dev.c:4100
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff81eeb140-ffffffff81eeb1f7: __get_xps_queue_idx (STB_LOCAL)
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
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc8518)
Location: net/core/dev.c:3536
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffff800010bc8518-ffff800010bc85dc: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce3dec)
Location: net/core/dev.c:3536
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
c0ce3dec-c0ce3e84: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca4520)
Location: net/core/dev.c:3536
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
c000000000ca4520-c000000000ca4624: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000754a0e)
Location: net/core/dev.c:3536
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffe000754a0e-ffffffe000754ac4: __get_xps_queue_idx (STB_LOCAL)
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
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cbe40)
Location: net/core/dev.c:3536
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff818cbe40-ffffffff818cbee2: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81885d80)
Location: net/core/dev.c:3536
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff81885d80-ffffffff81885e22: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191ce40)
Location: net/core/dev.c:3536
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff8191ce40-ffffffff8191cee2: __get_xps_queue_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __get_xps_queue_idx(struct net_device *dev, struct sk_buff *skb, struct xps_dev_maps *dev_maps, unsigned int tci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193e310)
Location: net/core/dev.c:3536
Inline: False
Direct callers:
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:netdev_pick_tx
```
**Symbols:**

```
ffffffff8193e310-ffffffff8193e3b2: __get_xps_queue_idx (STB_LOCAL)
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
