# Function: <code>netdev_is_rx_handler_busy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177c2b0)
Location: net/core/dev.c:3986
Inline: False
```
**Symbols:**

```
ffffffff8177c2b0-ffffffff8177c2fd: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a9a40)
Location: net/core/dev.c:3981
Inline: False
```
**Symbols:**

```
ffffffff817a9a40-ffffffff817a9a8d: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c7f30)
Location: net/core/dev.c:4070
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff817c7f30-ffffffff817c7f7a: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81841ad0)
Location: net/core/dev.c:4271
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff81841ad0-ffffffff81841b1a: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188bf40)
Location: net/core/dev.c:4397
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff8188bf40-ffffffff8188bf97: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ad250)
Location: net/core/dev.c:4716
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff818ad250-ffffffff818ad2a7: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f8b50)
Location: net/core/dev.c:4711
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff818f8b50-ffffffff818f8ba7: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192acf0)
Location: net/core/dev.c:4613
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff8192acf0-ffffffff8192ad47: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a02c85)
Location: net/core/dev.c:4976
Inline: True
Inline callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff819fe9d0-ffffffff819fea2a: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a03527)
Location: net/core/dev.c:5025
Inline: True
Inline callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff819fe630-ffffffff819fe68a: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e9fd7)
Location: net/core/dev.c:5150
Inline: True
Inline callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff819e4ea0-ffffffff819e4efa: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a9ac99)
Location: net/core/dev.c:5140
Inline: True
Inline callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff81d357e3-ffffffff81d357f8: netdev_is_rx_handler_busy.cold (STB_LOCAL)
ffffffff81a96d60-ffffffff81a96dca: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81c13d69)
Location: net/core/dev.c:5175
Inline: True
Inline callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff81f01dcf-ffffffff81f01de4: netdev_is_rx_handler_busy.cold (STB_LOCAL)
ffffffff81c0db90-ffffffff81c0dc04: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81dc3429)
Location: net/core/dev.c:5166
Inline: True
Inline callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff820ab151-ffffffff820ab166: netdev_is_rx_handler_busy.cold (STB_LOCAL)
ffffffff81dbd9f0-ffffffff81dbda64: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81e32519)
Location: net/core/dev.c:5142
Inline: True
Inline callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff8212c7fa-ffffffff8212c80f: netdev_is_rx_handler_busy.cold (STB_LOCAL)
ffffffff81e2e240-ffffffff81e2e2b4: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81ef09d9)
Location: net/core/dev.c:5224
Inline: True
Inline callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff8220e524-ffffffff8220e539: netdev_is_rx_handler_busy.cold (STB_LOCAL)
ffffffff81eec620-ffffffff81eec694: netdev_is_rx_handler_busy (STB_GLOBAL)
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
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc75c8)
Location: net/core/dev.c:4613
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffff800010bc75c8-ffff800010bc7640: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce2aa4)
Location: net/core/dev.c:4613
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
c0ce2aa4-c0ce2b2c: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca2aa0)
Location: net/core/dev.c:4613
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
c000000000ca2aa0-c000000000ca2b40: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000753b28)
Location: net/core/dev.c:4613
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffe000753b28-ffffffe000753b94: netdev_is_rx_handler_busy (STB_GLOBAL)
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
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cacf0)
Location: net/core/dev.c:4613
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff818cacf0-ffffffff818cad47: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81884c30)
Location: net/core/dev.c:4613
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff81884c30-ffffffff81884c87: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191bcf0)
Location: net/core/dev.c:4613
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff8191bcf0-ffffffff8191bd47: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool netdev_is_rx_handler_busy(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193d1d0)
Location: net/core/dev.c:4613
Inline: False
Direct callers:
  - net/core/dev.c:netdev_rx_handler_register
```
**Symbols:**

```
ffffffff8193d1d0-ffffffff8193d227: netdev_is_rx_handler_busy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
