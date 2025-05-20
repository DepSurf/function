# Function: <code>netif_set_xps_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81717ca0)
Location: net/core/dev.c:2030
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_set_affinity
  - net/core/net-sysfs.c:store_xps_map
```
**Symbols:**

```
ffffffff81717ca0-ffffffff817181ec: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177fea0)
Location: net/core/dev.c:2051
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_xps_map
```
**Symbols:**

```
ffffffff8177fea0-ffffffff8178037e: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ad570)
Location: net/core/dev.c:2110
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_xps_map
```
**Symbols:**

```
ffffffff817ad570-ffffffff817adc8c: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cc120)
Location: net/core/dev.c:2144
Inline: False
Direct callers:
  - net/core/net-sysfs.c:store_xps_map
```
**Symbols:**

```
ffffffff817cc120-ffffffff817cc7ee: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818457f0)
Location: net/core/dev.c:2164
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff818457f0-ffffffff81845e67: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188edd0)
Location: net/core/dev.c:2208
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff8188edd0-ffffffff8188f451: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b31c0)
Location: net/core/dev.c:2510
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff818b31c0-ffffffff818b31fb: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ffef0)
Location: net/core/dev.c:2520
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff818ffef0-ffffffff818fff2d: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81932210)
Location: net/core/dev.c:2438
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff81932210-ffffffff8193224d: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a06010)
Location: net/core/dev.c:2798
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff81a06010-ffffffff81a0604d: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a07810)
Location: net/core/dev.c:2823
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff81a07810-ffffffff81a0784d: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819eb0b0)
Location: net/core/dev.c:2891
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff819eb0b0-ffffffff819eb0ed: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9c070)
Location: net/core/dev.c:2766
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff81a9c070-ffffffff81a9c0ad: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c138a0)
Location: net/core/dev.c:2743
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff81c138a0-ffffffff81c138e7: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc5780)
Location: net/core/dev.c:2728
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff81dc5780-ffffffff81dc57c7: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e343b0)
Location: net/core/dev.c:2756
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff81e343b0-ffffffff81e343f7: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef2ee0)
Location: net/core/dev.c:2759
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff81ef2ee0-ffffffff81ef2f27: netif_set_xps_queue (STB_GLOBAL)
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
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcac30)
Location: net/core/dev.c:2438
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffff800010bcac30-ffff800010bcac88: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ceacc0)
Location: net/core/dev.c:2438
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
c0ceacc0-c0cead08: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cadc00)
Location: net/core/dev.c:2438
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
c000000000cadc00-c000000000cadc64: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075aa7e)
Location: net/core/dev.c:2438
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffe00075aa7e-ffffffe00075aaba: netif_set_xps_queue (STB_GLOBAL)
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
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d2210)
Location: net/core/dev.c:2438
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff818d2210-ffffffff818d224d: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188c0a0)
Location: net/core/dev.c:2438
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff8188c0a0-ffffffff8188c0dd: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81923210)
Location: net/core/dev.c:2438
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff81923210-ffffffff8192324d: netif_set_xps_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netif_set_xps_queue(struct net_device *dev, const struct cpumask *mask, u16 index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81944640)
Location: net/core/dev.c:2438
Inline: False
Direct callers:
  - net/core/net-sysfs.c:xps_cpus_store
```
**Symbols:**

```
ffffffff81944640-ffffffff8194467d: netif_set_xps_queue (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
