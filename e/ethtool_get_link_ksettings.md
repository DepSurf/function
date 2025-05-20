# Function: <code>ethtool_get_link_ksettings</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8178a1f9)
Location: net/core/ethtool.c:646
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff817b7b6e)
Location: net/core/ethtool.c:657
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff817d657f)
Location: net/core/ethtool.c:660
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff81850c4e)
Location: net/core/ethtool.c:674
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff8189d6b8)
Location: net/core/ethtool.c:647
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
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
In net/core/ethtool.c (ffffffff818be16e)
Location: net/core/ethtool.c:610
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81908e90)
Location: net/core/ethtool.c:609
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81908e90-ffffffff81908fcc: ethtool_get_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8193b5d0)
Location: net/core/ethtool.c:610
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8193b5d0-ffffffff8193b70c: ethtool_get_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a80d20)
Location: net/ethtool/ioctl.c:506
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a80d20-ffffffff81a80e62: ethtool_get_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a8ad90)
Location: net/ethtool/ioctl.c:510
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a8ad90-ffffffff81a8aed2: ethtool_get_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a740c0)
Location: net/ethtool/ioctl.c:510
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a740c0-ffffffff81a7420b: ethtool_get_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:512
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81b2e2b0-ffffffff81b2e40a: ethtool_get_link_ksettings (STB_LOCAL)
ffffffff81d3961e-ffffffff81d39633: ethtool_get_link_ksettings.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:536
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81cb8c80-ffffffff81cb8e23: ethtool_get_link_ksettings (STB_LOCAL)
ffffffff81f05d86-ffffffff81f05d9b: ethtool_get_link_ksettings.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:516
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81e77090-ffffffff81e7723a: ethtool_get_link_ksettings (STB_LOCAL)
ffffffff820adaa1-ffffffff820adab6: ethtool_get_link_ksettings.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:517
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81ed2f80-ffffffff81ed3122: ethtool_get_link_ksettings (STB_LOCAL)
ffffffff8212ece7-ffffffff8212ecfc: ethtool_get_link_ksettings.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:520
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81f96890-ffffffff81f96a32: ethtool_get_link_ksettings (STB_LOCAL)
ffffffff82210a60-ffffffff82210a75: ethtool_get_link_ksettings.cold (STB_LOCAL)
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
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffff800010bda720)
Location: net/core/ethtool.c:610
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffff800010bda720-ffff800010bda8d4: ethtool_get_link_ksettings (STB_LOCAL)
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
In net/core/ethtool.c (c0cf7d68)
Location: net/core/ethtool.c:610
Inline: True
Inline callers:
  - net/core/ethtool.c:dev_ethtool
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c000000000cb9bf0)
Location: net/core/ethtool.c:610
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
c000000000cb9bf0-c000000000cb9dac: ethtool_get_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffe000762c8c)
Location: net/core/ethtool.c:610
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffe000762c8c-ffffffe000762dea: ethtool_get_link_ksettings (STB_LOCAL)
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
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818db5a0)
Location: net/core/ethtool.c:610
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff818db5a0-ffffffff818db6dc: ethtool_get_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818953e0)
Location: net/core/ethtool.c:610
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff818953e0-ffffffff8189551c: ethtool_get_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8192c5d0)
Location: net/core/ethtool.c:610
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8192c5d0-ffffffff8192c70c: ethtool_get_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ethtool_get_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8194dca0)
Location: net/core/ethtool.c:610
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8194dca0-ffffffff8194dddc: ethtool_get_link_ksettings (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
