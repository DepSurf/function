# Function: <code>__netdev_walk_all_upper_dev</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81929d00)
Location: net/core/dev.c:6602
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81929d00-ffffffff81929df1: __netdev_walk_all_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fdd40)
Location: net/core/dev.c:6993
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff819fdd40-ffffffff819fde31: __netdev_walk_all_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fd890)
Location: net/core/dev.c:7150
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff819fd890-ffffffff819fd981: __netdev_walk_all_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e4080)
Location: net/core/dev.c:7409
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff819e4080-ffffffff819e4171: __netdev_walk_all_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7399
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81a98600-ffffffff81a987ad: __netdev_walk_all_upper_dev (STB_LOCAL)
ffffffff81d35e7e-ffffffff81d35ea1: __netdev_walk_all_upper_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6920
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81c0fed0-ffffffff81c100b7: __netdev_walk_all_upper_dev (STB_LOCAL)
ffffffff81f0267b-ffffffff81f0269e: __netdev_walk_all_upper_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6906
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81dbfa00-ffffffff81dbfbe7: __netdev_walk_all_upper_dev (STB_LOCAL)
ffffffff820ab2ad-ffffffff820ab2d0: __netdev_walk_all_upper_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6911
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81e2f5c0-ffffffff81e2f7a7: __netdev_walk_all_upper_dev (STB_LOCAL)
ffffffff8212c8a1-ffffffff8212c8c4: __netdev_walk_all_upper_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, struct netdev_nested_priv *), struct netdev_nested_priv *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7029
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81eee1a0-ffffffff81eee387: __netdev_walk_all_upper_dev (STB_LOCAL)
ffffffff8220e63d-ffffffff8220e660: __netdev_walk_all_upper_dev.cold (STB_LOCAL)
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
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc6488)
Location: net/core/dev.c:6602
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffff800010bc6488-ffff800010bc6594: __netdev_walk_all_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce1a40)
Location: net/core/dev.c:6602
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
c0ce1a40-c0ce1b44: __netdev_walk_all_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca1030)
Location: net/core/dev.c:6602
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
c000000000ca1030-c000000000ca1190: __netdev_walk_all_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000752c1e)
Location: net/core/dev.c:6602
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffe000752c1e-ffffffe000752cd0: __netdev_walk_all_upper_dev (STB_LOCAL)
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
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818c9d00)
Location: net/core/dev.c:6602
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff818c9d00-ffffffff818c9df1: __netdev_walk_all_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81883c40)
Location: net/core/dev.c:6602
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff81883c40-ffffffff81883d31: __netdev_walk_all_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191ad00)
Location: net/core/dev.c:6602
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff8191ad00-ffffffff8191adf1: __netdev_walk_all_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __netdev_walk_all_upper_dev(struct net_device *dev, int (*fn)(struct net_device *, void *), void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193bf00)
Location: net/core/dev.c:6602
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_unlink
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_has_upper_dev
```
**Symbols:**

```
ffffffff8193bf00-ffffffff8193bff1: __netdev_walk_all_upper_dev (STB_LOCAL)
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
<li>
<b>Param type changed. </b>
<code>int (*fn)(struct net_device *, void *)</code> ➡️ <code>int (*fn)(struct net_device *, struct netdev_nested_priv *)</code>
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
