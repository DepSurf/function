# Function: <code>__netdev_has_upper_dev</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int __netdev_has_upper_dev(struct net_device *upper_dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a8c60)
Location: net/core/dev.c:5415
Inline: False
```
**Symbols:**

```
ffffffff817a8c60-ffffffff817a8c73: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __netdev_has_upper_dev(struct net_device *upper_dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c7300)
Location: net/core/dev.c:5620
Inline: False
```
**Symbols:**

```
ffffffff817c7300-ffffffff817c7313: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __netdev_has_upper_dev(struct net_device *upper_dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81840ee0)
Location: net/core/dev.c:5761
Inline: False
```
**Symbols:**

```
ffffffff81840ee0-ffffffff81840ef3: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __netdev_has_upper_dev(struct net_device *upper_dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b530)
Location: net/core/dev.c:5891
Inline: False
```
**Symbols:**

```
ffffffff8188b530-ffffffff8188b543: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __netdev_has_upper_dev(struct net_device *upper_dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ac6b0)
Location: net/core/dev.c:6466
Inline: False
```
**Symbols:**

```
ffffffff818ac6b0-ffffffff818ac6c3: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __netdev_has_upper_dev(struct net_device *upper_dev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f7ef0)
Location: net/core/dev.c:6476
Inline: False
```
**Symbols:**

```
ffffffff818f7ef0-ffffffff818f7f03: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192aee0)
Location: net/core/dev.c:6698
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff8192aee0-ffffffff8192af45: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819feb80)
Location: net/core/dev.c:7089
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff819feb80-ffffffff819febe5: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fe810)
Location: net/core/dev.c:7246
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff819fe810-ffffffff819fe8a0: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e5080)
Location: net/core/dev.c:7505
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff819e5080-ffffffff819e5110: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7495
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a987b0-ffffffff81a98850: __netdev_has_upper_dev (STB_LOCAL)
ffffffff81d35ea1-ffffffff81d35eb5: __netdev_has_upper_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7016
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81c100c0-ffffffff81c10171: __netdev_has_upper_dev (STB_LOCAL)
ffffffff81f0269e-ffffffff81f026b3: __netdev_has_upper_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7002
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81dbfc00-ffffffff81dbfcb1: __netdev_has_upper_dev (STB_LOCAL)
ffffffff820ab2d0-ffffffff820ab2e5: __netdev_has_upper_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7007
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81e2f7c0-ffffffff81e2f871: __netdev_has_upper_dev (STB_LOCAL)
ffffffff8212c8c4-ffffffff8212c8d9: __netdev_has_upper_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7125
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81eee3a0-ffffffff81eee451: __netdev_has_upper_dev (STB_LOCAL)
ffffffff8220e660-ffffffff8220e675: __netdev_has_upper_dev.cold (STB_LOCAL)
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
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc7848)
Location: net/core/dev.c:6698
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffff800010bc7848-ffff800010bc78cc: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce2d2c)
Location: net/core/dev.c:6698
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
c0ce2d2c-c0ce2dbc: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca2e10)
Location: net/core/dev.c:6698
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
c000000000ca2e10-c000000000ca2ed0: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000753d5e)
Location: net/core/dev.c:6698
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffe000753d5e-ffffffe000753ddc: __netdev_has_upper_dev (STB_LOCAL)
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
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818caee0)
Location: net/core/dev.c:6698
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff818caee0-ffffffff818caf45: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81884e20)
Location: net/core/dev.c:6698
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81884e20-ffffffff81884e85: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191bee0)
Location: net/core/dev.c:6698
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff8191bee0-ffffffff8191bf45: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __netdev_has_upper_dev(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193d3c0)
Location: net/core/dev.c:6698
Inline: False
Direct callers:
  - net/core/dev.c:__netdev_upper_dev_link
  - net/core/dev.c:__netdev_upper_dev_link
```
**Symbols:**

```
ffffffff8193d3c0-ffffffff8193d425: __netdev_has_upper_dev (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
<li>
<b>Param reordered. </b>
<code>upper_dev, data</code> ➡️ <code>dev, upper_dev</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
