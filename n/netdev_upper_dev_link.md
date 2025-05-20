# Function: <code>netdev_upper_dev_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817177f0)
Location: net/core/dev.c:5484
Inline: False
```
**Symbols:**

```
ffffffff817177f0-ffffffff81717804: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177f7f0)
Location: net/core/dev.c:5879
Inline: False
```
**Symbols:**

```
ffffffff8177f7f0-ffffffff8177f807: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ad250)
Location: net/core/dev.c:6041
Inline: False
```
**Symbols:**

```
ffffffff817ad250-ffffffff817ad267: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cbe00)
Location: net/core/dev.c:6249
Inline: False
```
**Symbols:**

```
ffffffff817cbe00-ffffffff817cbe17: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81845690)
Location: net/core/dev.c:6395
Inline: False
```
**Symbols:**

```
ffffffff81845690-ffffffff818456aa: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188ec70)
Location: net/core/dev.c:6530
Inline: False
```
**Symbols:**

```
ffffffff8188ec70-ffffffff8188ec8a: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818afd10)
Location: net/core/dev.c:7105
Inline: False
```
**Symbols:**

```
ffffffff818afd10-ffffffff818afd2a: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fbb60)
Location: net/core/dev.c:7115
Inline: False
```
**Symbols:**

```
ffffffff818fbb60-ffffffff818fbb7a: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192e0e2)
Location: net/core/dev.c:7336
Inline: True
Inline callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff8192e090-ffffffff8192e0aa: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a03cc2)
Location: net/core/dev.c:7727
Inline: True
Inline callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff81a03c70-ffffffff81a03c8a: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04210)
Location: net/core/dev.c:7902
Inline: False
```
**Symbols:**

```
ffffffff81a04210-ffffffff81a0425f: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819eb670)
Location: net/core/dev.c:8161
Inline: False
```
**Symbols:**

```
ffffffff819eb670-ffffffff819eb6bf: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9c5f0)
Location: net/core/dev.c:8151
Inline: False
```
**Symbols:**

```
ffffffff81a9c5f0-ffffffff81a9c63f: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c16260)
Location: net/core/dev.c:7682
Inline: False
```
**Symbols:**

```
ffffffff81c16260-ffffffff81c162c5: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc75d0)
Location: net/core/dev.c:7668
Inline: False
```
**Symbols:**

```
ffffffff81dc75d0-ffffffff81dc7635: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e39380)
Location: net/core/dev.c:7673
Inline: False
```
**Symbols:**

```
ffffffff81e39380-ffffffff81e393e5: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef7670)
Location: net/core/dev.c:7791
Inline: False
```
**Symbols:**

```
ffffffff81ef7670-ffffffff81ef76d5: netdev_upper_dev_link (STB_GLOBAL)
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
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcf3b0)
Location: net/core/dev.c:7336
Inline: True
Inline callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffff800010bcf328-ffff800010bcf378: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce7798)
Location: net/core/dev.c:7336
Inline: True
Inline callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
c0ce771c-c0ce7750: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caa960)
Location: net/core/dev.c:7336
Inline: True
Inline callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
c000000000caa8d0-c000000000caa8f4: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000756c92)
Location: net/core/dev.c:7336
Inline: True
Inline callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffe000756c18-ffffffe000756c58: netdev_upper_dev_link (STB_GLOBAL)
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
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ce0e2)
Location: net/core/dev.c:7336
Inline: True
Inline callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff818ce090-ffffffff818ce0aa: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81888202)
Location: net/core/dev.c:7336
Inline: True
Inline callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
Direct callers:
  - drivers/net/vxlan.c:__vxlan_dev_create
```
**Symbols:**

```
ffffffff818881b0-ffffffff818881ca: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191f0e2)
Location: net/core/dev.c:7336
Inline: True
Inline callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff8191f090-ffffffff8191f0aa: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81940e42)
Location: net/core/dev.c:7336
Inline: True
Inline callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
```
**Symbols:**

```
ffffffff81940df0-ffffffff81940e0a: netdev_upper_dev_link (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
