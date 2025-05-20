# Function: <code>__netdev_update_upper_level</code>

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
int __netdev_update_upper_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192db81)
Location: net/core/dev.c:6971
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff8192a0a0-ffffffff8192a10f: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a03e06)
Location: net/core/dev.c:7362
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a02670-ffffffff81a026e4: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, struct netdev_nested_priv *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0444b)
Location: net/core/dev.c:7524
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a02e70-ffffffff81a02ee4: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, struct netdev_nested_priv *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819eb8b3)
Location: net/core/dev.c:7783
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff819e9530-ffffffff819e959f: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, struct netdev_nested_priv *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9c82b)
Location: net/core/dev.c:7773
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a98bf0-ffffffff81a98c13: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, struct netdev_nested_priv *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c164eb)
Location: net/core/dev.c:7294
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81c10230-ffffffff81c10259: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, struct netdev_nested_priv *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc788b)
Location: net/core/dev.c:7280
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81dbfe90-ffffffff81dbfeb9: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, struct netdev_nested_priv *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3963b)
Location: net/core/dev.c:7285
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81e2f950-ffffffff81e2f979: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, struct netdev_nested_priv *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef792b)
Location: net/core/dev.c:7403
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81eee530-ffffffff81eee559: __netdev_update_upper_level (STB_LOCAL)
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
int __netdev_update_upper_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcdcf8)
Location: net/core/dev.c:6971
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffff800010bc6920-ffff800010bc69bc: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce71c0)
Location: net/core/dev.c:6971
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
c0ce1e14-c0ce1e9c: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca9180)
Location: net/core/dev.c:6971
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
c000000000ca1580-c000000000ca1610: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000756814)
Location: net/core/dev.c:6971
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffe000752f5e-ffffffe000752fd0: __netdev_update_upper_level (STB_LOCAL)
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
int __netdev_update_upper_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cdb81)
Location: net/core/dev.c:6971
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff818ca0a0-ffffffff818ca10f: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81887ca1)
Location: net/core/dev.c:6971
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81883fe0-ffffffff8188404f: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191eb81)
Location: net/core/dev.c:6971
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff8191b0a0-ffffffff8191b10f: __netdev_update_upper_level (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __netdev_update_upper_level(struct net_device *dev, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819408e1)
Location: net/core/dev.c:6971
Inline: True
Inline callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff8193c2a0-ffffffff8193c30f: __netdev_update_upper_level (STB_LOCAL)
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
<code>struct netdev_nested_priv *__unused</code>
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
