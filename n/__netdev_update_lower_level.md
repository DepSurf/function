# Function: <code>__netdev_update_lower_level</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192dbe5)
Location: net/core/dev.c:6977
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff8192a110-ffffffff8192a17f: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a03e63)
Location: net/core/dev.c:7368
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a026f0-ffffffff81a02764: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a044a8)
Location: net/core/dev.c:7531
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a02ef0-ffffffff81a02f64: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819eb910)
Location: net/core/dev.c:7790
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff819e95a0-ffffffff819e960f: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9c845)
Location: net/core/dev.c:7780
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a98e90-ffffffff81a98eb3: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c16506)
Location: net/core/dev.c:7311
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81c10510-ffffffff81c10539: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc78a6)
Location: net/core/dev.c:7297
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81dbfd90-ffffffff81dbfdb9: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e39656)
Location: net/core/dev.c:7302
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81e2fc40-ffffffff81e2fc69: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef7946)
Location: net/core/dev.c:7420
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81eee820-ffffffff81eee849: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcdd5c)
Location: net/core/dev.c:6977
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffff800010bc69c0-ffff800010bc6a5c: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce722c)
Location: net/core/dev.c:6977
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
c0ce1e9c-c0ce1f24: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca9200)
Location: net/core/dev.c:6977
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
c000000000ca1610-c000000000ca16a0: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075685e)
Location: net/core/dev.c:6977
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffe000752fd0-ffffffe000753042: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cdbe5)
Location: net/core/dev.c:6977
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff818ca110-ffffffff818ca17f: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81887d05)
Location: net/core/dev.c:6977
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81884050-ffffffff818840bf: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191ebe5)
Location: net/core/dev.c:6977
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff8191b110-ffffffff8191b17f: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_lower_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81940945)
Location: net/core/dev.c:6977
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff8193c310-ffffffff8193c37f: __netdev_update_lower_level (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netdev_nested_priv *priv</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
</ul>
</details>
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
