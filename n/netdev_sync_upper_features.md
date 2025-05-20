# Function: <code>netdev_sync_upper_features</code>

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
In net/core/dev.c (ffffffff8171e0b7)
Location: net/core/dev.c:6303
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
In net/core/dev.c (ffffffff817869a1)
Location: net/core/dev.c:6787
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
In net/core/dev.c (ffffffff817b3f61)
Location: net/core/dev.c:6957
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
In net/core/dev.c (ffffffff817d2b3d)
Location: net/core/dev.c:7155
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
In net/core/dev.c (ffffffff8184ce9f)
Location: net/core/dev.c:7327
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
In net/core/dev.c (ffffffff8189721f)
Location: net/core/dev.c:7521
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
In net/core/dev.c (ffffffff818b968c)
Location: net/core/dev.c:8148
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
In net/core/dev.c (ffffffff81905833)
Location: net/core/dev.c:8251
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
In net/core/dev.c (ffffffff81937f23)
Location: net/core/dev.c:8562
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
netdev_features_t netdev_sync_upper_features(struct net_device *lower, struct net_device *upper, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ffea0)
Location: net/core/dev.c:9018
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff819ffea0-ffffffff819fff79: netdev_sync_upper_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
netdev_features_t netdev_sync_upper_features(struct net_device *lower, struct net_device *upper, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ffee0)
Location: net/core/dev.c:9632
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff819ffee0-ffffffff819fffb9: netdev_sync_upper_features (STB_LOCAL)
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
In net/core/dev.c (ffffffff819f4eda)
Location: net/core/dev.c:9797
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
In net/core/dev.c (ffffffff81aa6823)
Location: net/core/dev.c:9804
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
In net/core/dev.c (ffffffff81c1e5c3)
Location: net/core/dev.c:9542
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
In net/core/dev.c (ffffffff81dcfa24)
Location: net/core/dev.c:9529
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
In net/core/dev.c (ffffffff81e40620)
Location: net/core/dev.c:9541
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
In net/core/dev.c (ffffffff81efeff7)
Location: net/core/dev.c:9678
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
In net/core/dev.c (ffff800010bd6938)
Location: net/core/dev.c:8562
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
In net/core/dev.c (c0cf169c)
Location: net/core/dev.c:8562
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
In net/core/dev.c (c000000000cb64e0)
Location: net/core/dev.c:8562
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
In net/core/dev.c (ffffffe000760024)
Location: net/core/dev.c:8562
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
In net/core/dev.c (ffffffff818d7ef3)
Location: net/core/dev.c:8562
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
In net/core/dev.c (ffffffff81891d33)
Location: net/core/dev.c:8562
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
In net/core/dev.c (ffffffff81928f23)
Location: net/core/dev.c:8562
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
In net/core/dev.c (ffffffff8194a5f3)
Location: net/core/dev.c:8562
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
