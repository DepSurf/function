# Function: <code>ethtool_set_link_ksettings</code>

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
In net/core/ethtool.c (ffffffff8178a0ff)
Location: net/core/ethtool.c:710
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
In net/core/ethtool.c (ffffffff817b7adf)
Location: net/core/ethtool.c:721
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
In net/core/ethtool.c (ffffffff817d64fc)
Location: net/core/ethtool.c:724
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
In net/core/ethtool.c (ffffffff81850bc5)
Location: net/core/ethtool.c:738
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
In net/core/ethtool.c (ffffffff8189c0eb)
Location: net/core/ethtool.c:711
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
In net/core/ethtool.c (ffffffff818bff1a)
Location: net/core/ethtool.c:664
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
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81908460)
Location: net/core/ethtool.c:663
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81908460-ffffffff81908560: ethtool_set_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8193aba0)
Location: net/core/ethtool.c:664
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8193aba0-ffffffff8193aca0: ethtool_set_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a80970)
Location: net/ethtool/ioctl.c:562
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a80970-ffffffff81a80ab2: ethtool_set_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a8a9e0)
Location: net/ethtool/ioctl.c:566
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a8a9e0-ffffffff81a8ab22: ethtool_set_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81a73e60)
Location: net/ethtool/ioctl.c:566
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a73e60-ffffffff81a73fb2: ethtool_set_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:568
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81b2dde0-ffffffff81b2df49: ethtool_set_link_ksettings (STB_LOCAL)
ffffffff81d3960a-ffffffff81d3961e: ethtool_set_link_ksettings.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:592
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81cb8780-ffffffff81cb8906: ethtool_set_link_ksettings (STB_LOCAL)
ffffffff81f05d71-ffffffff81f05d86: ethtool_set_link_ksettings.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:573
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81e76950-ffffffff81e76ad6: ethtool_set_link_ksettings (STB_LOCAL)
ffffffff820ada8c-ffffffff820adaa1: ethtool_set_link_ksettings.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:574
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81ed2cd0-ffffffff81ed2e56: ethtool_set_link_ksettings (STB_LOCAL)
ffffffff8212ecd2-ffffffff8212ece7: ethtool_set_link_ksettings.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/ioctl.c (0)
Location: net/ethtool/ioctl.c:577
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
**Symbols:**

```
ffffffff81f965e0-ffffffff81f96766: ethtool_set_link_ksettings (STB_LOCAL)
ffffffff82210a4b-ffffffff82210a60: ethtool_set_link_ksettings.cold (STB_LOCAL)
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
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffff800010bd9e70)
Location: net/core/ethtool.c:664
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffff800010bd9e70-ffff800010bd9f7c: ethtool_set_link_ksettings (STB_LOCAL)
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
In net/core/ethtool.c (c0cf8168)
Location: net/core/ethtool.c:664
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
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c000000000cb96e0)
Location: net/core/ethtool.c:664
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
c000000000cb96e0-c000000000cb9848: ethtool_set_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffe0007622ac)
Location: net/core/ethtool.c:664
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffe0007622ac-ffffffe000762372: ethtool_set_link_ksettings (STB_LOCAL)
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
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818dab70)
Location: net/core/ethtool.c:664
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff818dab70-ffffffff818dac70: ethtool_set_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818949b0)
Location: net/core/ethtool.c:664
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff818949b0-ffffffff81894ab0: ethtool_set_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8192bba0)
Location: net/core/ethtool.c:664
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8192bba0-ffffffff8192bca0: ethtool_set_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ethtool_set_link_ksettings(struct net_device *dev, void *useraddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8194d270)
Location: net/core/ethtool.c:664
Inline: False
Direct callers:
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8194d270-ffffffff8194d370: ethtool_set_link_ksettings (STB_LOCAL)
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
