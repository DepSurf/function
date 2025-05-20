# Function: <code>netdev_sync_lower_features</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171e1bb)
Location: net/core/dev.c:6323
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81786a94)
Location: net/core/dev.c:6807
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b4054)
Location: net/core/dev.c:6977
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
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
In net/core/dev.c (ffffffff817d2c32)
Location: net/core/dev.c:7175
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
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
In net/core/dev.c (ffffffff8184cf94)
Location: net/core/dev.c:7347
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
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
In net/core/dev.c (ffffffff81897326)
Location: net/core/dev.c:7541
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
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
In net/core/dev.c (ffffffff818b9780)
Location: net/core/dev.c:8168
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
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
In net/core/dev.c (ffffffff8190592b)
Location: net/core/dev.c:8271
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193801b)
Location: net/core/dev.c:8582
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netdev_sync_lower_features(struct net_device *upper, struct net_device *lower, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0ce50)
Location: net/core/dev.c:9038
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff81a0ce50-ffffffff81a0d009: netdev_sync_lower_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netdev_sync_lower_features(struct net_device *upper, struct net_device *lower, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0e600)
Location: net/core/dev.c:9652
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff81a0e600-ffffffff81a0e7b9: netdev_sync_lower_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f4fdb)
Location: net/core/dev.c:9817
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa6936)
Location: net/core/dev.c:9824
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1e6e9)
Location: net/core/dev.c:9562
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcfb40)
Location: net/core/dev.c:9549
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e4074b)
Location: net/core/dev.c:9561
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eff0e0)
Location: net/core/dev.c:9698
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd69e8)
Location: net/core/dev.c:8582
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf17c4)
Location: net/core/dev.c:8582
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb6614)
Location: net/core/dev.c:8582
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007600c2)
Location: net/core/dev.c:8582
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d7feb)
Location: net/core/dev.c:8582
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81891e2b)
Location: net/core/dev.c:8582
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192901b)
Location: net/core/dev.c:8582
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194a6eb)
Location: net/core/dev.c:8582
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
