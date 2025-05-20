# Function: <code>netif_set_tso_max_size</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void netif_set_tso_max_size(struct net_device *dev, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0ad2b)
Location: net/core/dev.c:3006
Inline: True
Inline callers:
  - net/core/dev.c:netif_inherit_tso_max
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
**Symbols:**

```
ffffffff81c0acb0-ffffffff81c0ace5: netif_set_tso_max_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void netif_set_tso_max_size(struct net_device *dev, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbac4b)
Location: net/core/dev.c:2991
Inline: True
Inline callers:
  - net/core/dev.c:netif_inherit_tso_max
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
**Symbols:**

```
ffffffff81dbabb0-ffffffff81dbabe5: netif_set_tso_max_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void netif_set_tso_max_size(struct net_device *dev, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e307bb)
Location: net/core/dev.c:3019
Inline: True
Inline callers:
  - net/core/dev.c:netif_inherit_tso_max
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
```
**Symbols:**

```
ffffffff81e2b390-ffffffff81e2b3e5: netif_set_tso_max_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void netif_set_tso_max_size(struct net_device *dev, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eef15b)
Location: net/core/dev.c:3022
Inline: True
Inline callers:
  - net/core/dev.c:netif_inherit_tso_max
Direct callers:
  - drivers/net/loopback.c:blackhole_netdev_setup
  - drivers/net/loopback.c:loopback_setup
  - drivers/net/netkit.c:netkit_setup
```
**Symbols:**

```
ffffffff81ee9400-ffffffff81ee9446: netif_set_tso_max_size (STB_GLOBAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
