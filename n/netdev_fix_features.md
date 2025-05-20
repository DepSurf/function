# Function: <code>netdev_fix_features</code>

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
In net/core/dev.c (ffffffff8171dfac)
Location: net/core/dev.c:6345
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
In net/core/dev.c (ffffffff81786863)
Location: net/core/dev.c:6829
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
In net/core/dev.c (ffffffff817b3e23)
Location: net/core/dev.c:6999
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
In net/core/dev.c (ffffffff817d2a23)
Location: net/core/dev.c:7197
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
In net/core/dev.c (ffffffff8184cdb6)
Location: net/core/dev.c:7369
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
In net/core/dev.c (ffffffff818970fd)
Location: net/core/dev.c:7563
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
In net/core/dev.c (ffffffff818b9559)
Location: net/core/dev.c:8190
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
In net/core/dev.c (ffffffff819056fd)
Location: net/core/dev.c:8293
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
In net/core/dev.c (ffffffff81937ded)
Location: net/core/dev.c:8604
Inline: True
Inline callers:
  - net/core/dev.c:__netdev_update_features
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
netdev_features_t netdev_fix_features(struct net_device *dev, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9062
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff81a00170-ffffffff81a003c5: netdev_fix_features (STB_LOCAL)
ffffffff81a0eca4-ffffffff81a0ecb9: netdev_fix_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
netdev_features_t netdev_fix_features(struct net_device *dev, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9676
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff81a00260-ffffffff81a0054d: netdev_fix_features (STB_LOCAL)
ffffffff81c30f98-ffffffff81c30fad: netdev_fix_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
netdev_features_t netdev_fix_features(struct net_device *dev, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9841
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff819e66e0-ffffffff819e69cd: netdev_fix_features (STB_LOCAL)
ffffffff81c2329e-ffffffff81c232b3: netdev_fix_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
netdev_features_t netdev_fix_features(struct net_device *dev, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9848
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff81a976e0-ffffffff81a979c4: netdev_fix_features (STB_LOCAL)
ffffffff81d35d63-ffffffff81d35d78: netdev_fix_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
netdev_features_t netdev_fix_features(struct net_device *dev, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9586
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff81c0eaf0-ffffffff81c0ee1e: netdev_fix_features (STB_LOCAL)
ffffffff81f024c3-ffffffff81f024d8: netdev_fix_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
netdev_features_t netdev_fix_features(struct net_device *dev, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc3eb0)
Location: net/core/dev.c:9573
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff81dc3eb0-ffffffff81dc4231: netdev_fix_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
netdev_features_t netdev_fix_features(struct net_device *dev, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e33350)
Location: net/core/dev.c:9585
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff81e33350-ffffffff81e33719: netdev_fix_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
netdev_features_t netdev_fix_features(struct net_device *dev, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef1480)
Location: net/core/dev.c:9722
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_update_features
```
**Symbols:**

```
ffffffff81ef1480-ffffffff81ef1843: netdev_fix_features (STB_LOCAL)
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
In net/core/dev.c (ffff800010bd6860)
Location: net/core/dev.c:8604
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
In net/core/dev.c (c0cf1430)
Location: net/core/dev.c:8604
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
In net/core/dev.c (c000000000cb63c4)
Location: net/core/dev.c:8604
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
In net/core/dev.c (ffffffe00075ff1c)
Location: net/core/dev.c:8604
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
In net/core/dev.c (ffffffff818d7dbd)
Location: net/core/dev.c:8604
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
In net/core/dev.c (ffffffff81891bfd)
Location: net/core/dev.c:8604
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
In net/core/dev.c (ffffffff81928ded)
Location: net/core/dev.c:8604
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
In net/core/dev.c (ffffffff8194a4bd)
Location: net/core/dev.c:8604
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
