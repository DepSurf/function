# Function: <code>devlink_compat_running_version</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81951b00)
Location: net/core/devlink.c:6875
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_drvinfo
```
**Symbols:**

```
ffffffff81951b00-ffffffff81951ce9: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81988540)
Location: net/core/devlink.c:8039
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_drvinfo
```
**Symbols:**

```
ffffffff81988540-ffffffff81988729: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a60380)
Location: net/core/devlink.c:9270
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
```
**Symbols:**

```
ffffffff81a60380-ffffffff81a60423: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a68b70)
Location: net/core/devlink.c:10224
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
```
**Symbols:**

```
ffffffff81a68b70-ffffffff81a68c13: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4be00)
Location: net/core/devlink.c:10488
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
```
**Symbols:**

```
ffffffff81a4be00-ffffffff81a4bfde: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b041f0)
Location: net/core/devlink.c:11430
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_drvinfo
```
**Symbols:**

```
ffffffff81b041f0-ffffffff81b0442c: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_compat_running_version(struct devlink *devlink, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c89b90)
Location: net/core/devlink.c:12036
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81c89b90-ffffffff81c89d3a: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_compat_running_version(struct devlink *devlink, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e44760)
Location: net/core/devlink.c:12917
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81e44760-ffffffff81e4491a: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_compat_running_version(struct devlink *devlink, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff820454e0)
Location: net/devlink/dev.c:1123
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff820454e0-ffffffff8204557d: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_compat_running_version(struct devlink *devlink, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82104de0)
Location: net/devlink/dev.c:1224
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff82104de0-ffffffff82104e7d: devlink_compat_running_version (STB_GLOBAL)
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
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c30460)
Location: net/core/devlink.c:8039
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_drvinfo
```
**Symbols:**

```
ffff800010c30460-ffff800010c3068c: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d47444)
Location: net/core/devlink.c:8039
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_drvinfo
```
**Symbols:**

```
c0d47444-c0d47688: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d291e0)
Location: net/core/devlink.c:8039
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_drvinfo
```
**Symbols:**

```
c000000000d291e0-c000000000d294d0: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a665c)
Location: net/core/devlink.c:8039
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_drvinfo
```
**Symbols:**

```
ffffffe0007a665c-ffffffe0007a6834: devlink_compat_running_version (STB_GLOBAL)
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
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819283b0)
Location: net/core/devlink.c:8039
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_drvinfo
```
**Symbols:**

```
ffffffff819283b0-ffffffff81928599: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e2160)
Location: net/core/devlink.c:8039
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_drvinfo
```
**Symbols:**

```
ffffffff818e2160-ffffffff818e2349: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81979540)
Location: net/core/devlink.c:8039
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_drvinfo
```
**Symbols:**

```
ffffffff81979540-ffffffff81979729: devlink_compat_running_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_compat_running_version(struct net_device *dev, char *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199ba30)
Location: net/core/devlink.c:8039
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_get_drvinfo
```
**Symbols:**

```
ffffffff8199ba30-ffffffff8199bc19: devlink_compat_running_version (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct devlink *devlink</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net_device *dev</code>
</li>
</ul>
</details>
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
