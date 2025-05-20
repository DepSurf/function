# Function: <code>__netdev_update_features</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171df30)
Location: net/core/dev.c:6412
Inline: False
Direct callers:
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:register_netdevice
  - net/core/ethtool.c:__ethtool_set_flags
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8171df30-ffffffff8171e685: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817867f0)
Location: net/core/dev.c:6908
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffff817867f0-ffffffff81786f0b: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b3db0)
Location: net/core/dev.c:7078
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffff817b3db0-ffffffff817b44cb: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d29b0)
Location: net/core/dev.c:7269
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffff817d29b0-ffffffff817d307c: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184cd40)
Location: net/core/dev.c:7423
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffff8184cd40-ffffffff8184d46e: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81897080)
Location: net/core/dev.c:7642
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffff81897080-ffffffff81897a3a: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b94e0)
Location: net/core/dev.c:8269
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffff818b94e0-ffffffff818b9e6d: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8372
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffff8190765b-ffffffff81907699: __netdev_update_features.cold (STB_LOCAL)
ffffffff81905680-ffffffff81906005: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8683
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffff81939c42-ffffffff81939c80: __netdev_update_features.cold (STB_LOCAL)
ffffffff81937d70-ffffffff819386f5: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9141
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:netdev_sync_lower_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:__ethtool_set_flags
  - net/ethtool/ioctl.c:ethtool_set_features
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81a0f1e0-ffffffff81a0f205: __netdev_update_features.cold (STB_LOCAL)
ffffffff81a0c940-ffffffff81a0ce50: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9771
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:netdev_sync_lower_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:__ethtool_set_flags
  - net/ethtool/ioctl.c:ethtool_set_features
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81c3152b-ffffffff81c31550: __netdev_update_features.cold (STB_LOCAL)
ffffffff81a0e0f0-ffffffff81a0e600: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9936
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:__ethtool_set_flags
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81c23810-ffffffff81c23835: __netdev_update_features.cold (STB_LOCAL)
ffffffff819f4e10-ffffffff819f558e: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9943
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:__ethtool_set_flags
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81d36758-ffffffff81d36864: __netdev_update_features.cold (STB_LOCAL)
ffffffff81aa6750-ffffffff81aa6f60: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9686
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__ethtool_set_flags
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81f02f81-ffffffff81f030d2: __netdev_update_features.cold (STB_LOCAL)
ffffffff81c1e4e0-ffffffff81c1ee16: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9673
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__ethtool_set_flags
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff820ab82d-ffffffff820ab95d: __netdev_update_features.cold (STB_LOCAL)
ffffffff81dcf940-ffffffff81dd0278: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9685
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__ethtool_set_flags
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff8212cf67-ffffffff8212d09a: __netdev_update_features.cold (STB_LOCAL)
ffffffff81e40540-ffffffff81e40e79: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9822
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/dev.c:__netdev_update_features
  - net/core/dev.c:generic_xdp_install
  - net/core/dev.c:dev_disable_lro
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/ioctl.c:__ethtool_set_flags
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff8220ecb7-ffffffff8220edb2: __netdev_update_features.cold (STB_LOCAL)
ffffffff81efef40-ffffffff81eff798: __netdev_update_features (STB_GLOBAL)
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
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd67f0)
Location: net/core/dev.c:8683
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffff800010bd67f0-ffff800010bd7084: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf139c)
Location: net/core/dev.c:8683
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
c0cf139c-c0cf1f70: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb6320)
Location: net/core/dev.c:8683
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
c000000000cb6320-c000000000cb6e40: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075feb8)
Location: net/core/dev.c:8683
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffe00075feb8-ffffffe000760740: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8683
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffff818d9c12-ffffffff818d9c50: __netdev_update_features.cold (STB_LOCAL)
ffffffff818d7d40-ffffffff818d86c5: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8683
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffff81893a52-ffffffff81893a90: __netdev_update_features.cold (STB_LOCAL)
ffffffff81891b80-ffffffff81892505: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8683
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffff8192ac42-ffffffff8192ac80: __netdev_update_features.cold (STB_LOCAL)
ffffffff81928d70-ffffffff819296f5: __netdev_update_features (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __netdev_update_features(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8683
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:netdev_change_features
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:__ethtool_set_flags
```
**Symbols:**

```
ffffffff8194c312-ffffffff8194c350: __netdev_update_features.cold (STB_LOCAL)
ffffffff8194a440-ffffffff8194adc5: __netdev_update_features (STB_GLOBAL)
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
