# Function: <code>__netif_set_xps_queue</code>

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
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b28f0)
Location: net/core/dev.c:2312
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff818b28f0-ffffffff818b31bb: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ff5f0)
Location: net/core/dev.c:2322
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff818ff5f0-ffffffff818ffeec: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81931910)
Location: net/core/dev.c:2240
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff81931910-ffffffff81932205: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a056d0)
Location: net/core/dev.c:2600
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff81a056d0-ffffffff81a0600f: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a06ed0)
Location: net/core/dev.c:2625
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff81a06ed0-ffffffff81a0780f: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, enum xps_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ea930)
Location: net/core/dev.c:2689
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff819ea930-ffffffff819eb0a2: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, enum xps_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9b7e0)
Location: net/core/dev.c:2564
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff81a9b7e0-ffffffff81a9c062: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, enum xps_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c12e00)
Location: net/core/dev.c:2541
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff81c12e00-ffffffff81c13899: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, enum xps_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc4cc0)
Location: net/core/dev.c:2526
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff81dc4cc0-ffffffff81dc576f: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, enum xps_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e33890)
Location: net/core/dev.c:2552
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff81e33890-ffffffff81e3439b: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, enum xps_map_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef23e0)
Location: net/core/dev.c:2555
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff81ef23e0-ffffffff81ef2ec4: __netif_set_xps_queue (STB_GLOBAL)
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
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bca348)
Location: net/core/dev.c:2240
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffff800010bca348-ffff800010bcac30: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cea348)
Location: net/core/dev.c:2240
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
c0cea348-c0ceacc0: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cacff0)
Location: net/core/dev.c:2240
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
c000000000cacff0-c000000000cadbf4: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075a2a0)
Location: net/core/dev.c:2240
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffe00075a2a0-ffffffe00075aa7e: __netif_set_xps_queue (STB_GLOBAL)
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
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d1910)
Location: net/core/dev.c:2240
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff818d1910-ffffffff818d2205: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b7a0)
Location: net/core/dev.c:2240
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff8188b7a0-ffffffff8188c095: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81922910)
Location: net/core/dev.c:2240
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff81922910-ffffffff81923205: __netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __netif_set_xps_queue(struct net_device *dev, const long unsigned int *mask, u16 index, bool is_rxqs_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81943d40)
Location: net/core/dev.c:2240
Inline: False
Direct callers:
  - net/core/dev.c:netif_set_xps_queue
  - net/core/net-sysfs.c:xps_rxqs_store
```
**Symbols:**

```
ffffffff81943d40-ffffffff81944635: __netif_set_xps_queue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum xps_map_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>bool is_rxqs_map</code>
</li>
</ul>
</details>
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
