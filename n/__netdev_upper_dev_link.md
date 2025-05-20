# Function: <code>__netdev_upper_dev_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81717310)
Location: net/core/dev.c:5361
Inline: False
Direct callers:
  - net/core/dev.c:netdev_upper_dev_link
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_master_upper_dev_link_private
```
**Symbols:**

```
ffffffff81717310-ffffffff817177e7: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177f2c0)
Location: net/core/dev.c:5751
Inline: False
Direct callers:
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff8177f2c0-ffffffff8177f7e4: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ad0a0)
Location: net/core/dev.c:5979
Inline: False
Direct callers:
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff817ad0a0-ffffffff817ad249: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cbc50)
Location: net/core/dev.c:6187
Inline: False
Direct callers:
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff817cbc50-ffffffff817cbdf2: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818454d0)
Location: net/core/dev.c:6328
Inline: False
Direct callers:
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff818454d0-ffffffff81845681: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188eab0)
Location: net/core/dev.c:6458
Inline: False
Direct callers:
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff8188eab0-ffffffff8188ec64: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818afb50)
Location: net/core/dev.c:7033
Inline: False
Direct callers:
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff818afb50-ffffffff818afd04: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fb9b0)
Location: net/core/dev.c:7043
Inline: False
Direct callers:
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff818fb9b0-ffffffff818fbb59: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192dd50)
Location: net/core/dev.c:7254
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
```
**Symbols:**

```
ffffffff8192dd50-ffffffff8192e084: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a03920)
Location: net/core/dev.c:7645
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
```
**Symbols:**

```
ffffffff81a03920-ffffffff81a03c63: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netdev_nested_priv *priv, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a03ec0)
Location: net/core/dev.c:7819
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a03ec0-ffffffff81a0420f: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netdev_nested_priv *priv, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819eb310)
Location: net/core/dev.c:8078
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff819eb310-ffffffff819eb66e: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netdev_nested_priv *priv, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8068
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81a9c2e0-ffffffff81a9c5e8: __netdev_upper_dev_link (STB_LOCAL)
ffffffff81d360d1-ffffffff81d36135: __netdev_upper_dev_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netdev_nested_priv *priv, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7599
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81c15f40-ffffffff81c1625b: __netdev_upper_dev_link (STB_LOCAL)
ffffffff81f02954-ffffffff81f029d8: __netdev_upper_dev_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netdev_nested_priv *priv, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7585
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81dc72a0-ffffffff81dc75bb: __netdev_upper_dev_link (STB_LOCAL)
ffffffff820ab514-ffffffff820ab598: __netdev_upper_dev_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netdev_nested_priv *priv, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7590
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81e39030-ffffffff81e39363: __netdev_upper_dev_link (STB_LOCAL)
ffffffff8212cc76-ffffffff8212ccda: __netdev_upper_dev_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netdev_nested_priv *priv, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7708
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
  - net/core/dev.c:netdev_upper_dev_link
```
**Symbols:**

```
ffffffff81ef7320-ffffffff81ef7653: __netdev_upper_dev_link (STB_LOCAL)
ffffffff8220e9b5-ffffffff8220ea19: __netdev_upper_dev_link.cold (STB_LOCAL)
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
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bceff0)
Location: net/core/dev.c:7254
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
```
**Symbols:**

```
ffff800010bceff0-ffff800010bcf324: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce73c8)
Location: net/core/dev.c:7254
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
```
**Symbols:**

```
c0ce73c8-c0ce771c: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caa4f0)
Location: net/core/dev.c:7254
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
```
**Symbols:**

```
c000000000caa4f0-c000000000caa8c4: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075699a)
Location: net/core/dev.c:7254
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
```
**Symbols:**

```
ffffffe00075699a-ffffffe000756c18: __netdev_upper_dev_link (STB_LOCAL)
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
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cdd50)
Location: net/core/dev.c:7254
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
```
**Symbols:**

```
ffffffff818cdd50-ffffffff818ce084: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81887e70)
Location: net/core/dev.c:7254
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
```
**Symbols:**

```
ffffffff81887e70-ffffffff818881a4: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191ed50)
Location: net/core/dev.c:7254
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
```
**Symbols:**

```
ffffffff8191ed50-ffffffff8191f084: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __netdev_upper_dev_link(struct net_device *dev, struct net_device *upper_dev, bool master, void *upper_priv, void *upper_info, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81940ab0)
Location: net/core/dev.c:7254
Inline: False
Direct callers:
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_adjacent_change_prepare
  - net/core/dev.c:netdev_master_upper_dev_link
```
**Symbols:**

```
ffffffff81940ab0-ffffffff81940de4: __netdev_upper_dev_link (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *upper_priv</code>
</li>
<li>
<b>Param added. </b>
<code>void *upper_info</code>
</li>
<li>
<b>Param removed. </b>
<code>void *private</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netdev_nested_priv *priv</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, upper_dev, master, upper_priv, upper_info, extack</code> ➡️ <code>dev, upper_dev, master, upper_priv, upper_info, priv, extack</code>
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
