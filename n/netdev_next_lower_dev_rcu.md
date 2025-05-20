# Function: <code>netdev_next_lower_dev_rcu</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a8e69)
Location: net/core/dev.c:5716
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
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
In net/core/dev.c (ffffffff817c7509)
Location: net/core/dev.c:5922
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
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
In net/core/dev.c (ffffffff818410e9)
Location: net/core/dev.c:6063
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
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
In net/core/dev.c (ffffffff8188b734)
Location: net/core/dev.c:6193
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
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
In net/core/dev.c (ffffffff818ac8b4)
Location: net/core/dev.c:6768
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
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
In net/core/dev.c (ffffffff818f80f4)
Location: net/core/dev.c:6778
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a207)
Location: net/core/dev.c:6916
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff8192a070-ffffffff8192a098: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fe0b0)
Location: net/core/dev.c:7307
Inline: True
```
**Symbols:**

```
ffffffff819fe0b0-ffffffff819fe0d8: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fdc40)
Location: net/core/dev.c:7469
Inline: True
```
**Symbols:**

```
ffffffff819fdc40-ffffffff819fdc68: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e44e7)
Location: net/core/dev.c:7728
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff819e4430-ffffffff819e4458: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a94eb9)
Location: net/core/dev.c:7718
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff81a94e20-ffffffff81a94e48: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0b45a)
Location: net/core/dev.c:7239
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff81c0b390-ffffffff81c0b3c8: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbb46a)
Location: net/core/dev.c:7225
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff81dbb390-ffffffff81dbb3c8: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2bbfa)
Location: net/core/dev.c:7230
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff81e2bb20-ffffffff81e2bb58: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ee9c5a)
Location: net/core/dev.c:7348
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff81ee9b80-ffffffff81ee9bb8: netdev_next_lower_dev_rcu (STB_GLOBAL)
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
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc6ab4)
Location: net/core/dev.c:6916
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffff800010bc68d0-ffff800010bc691c: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce1fac)
Location: net/core/dev.c:6916
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
c0ce1de0-c0ce1e14: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca16fc)
Location: net/core/dev.c:6916
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
c000000000ca1540-c000000000ca1578: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075306a)
Location: net/core/dev.c:6916
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffe000752f1e-ffffffe000752f5e: netdev_next_lower_dev_rcu (STB_GLOBAL)
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
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ca207)
Location: net/core/dev.c:6916
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff818ca070-ffffffff818ca098: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81884147)
Location: net/core/dev.c:6916
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff81883fb0-ffffffff81883fd8: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191b207)
Location: net/core/dev.c:6916
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff8191b070-ffffffff8191b098: netdev_next_lower_dev_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct net_device *netdev_next_lower_dev_rcu(struct net_device *dev, struct list_head **iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193c407)
Location: net/core/dev.c:6916
Inline: True
Inline callers:
  - net/core/dev.c:netdev_walk_all_lower_dev_rcu
```
**Symbols:**

```
ffffffff8193c270-ffffffff8193c298: netdev_next_lower_dev_rcu (STB_GLOBAL)
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
