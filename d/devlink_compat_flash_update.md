# Function: <code>devlink_compat_flash_update</code>

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
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81951cf0)
Location: net/core/devlink.c:6896
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_flash_device
```
**Symbols:**

```
ffffffff81951cf0-ffffffff81951da9: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81988730)
Location: net/core/devlink.c:8060
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_flash_device
```
**Symbols:**

```
ffffffff81988730-ffffffff819887e9: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a60430)
Location: net/core/devlink.c:9291
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_flash_device
```
**Symbols:**

```
ffffffff81a60430-ffffffff81a604ec: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a68c20)
Location: net/core/devlink.c:10245
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_flash_device
```
**Symbols:**

```
ffffffff81a68c20-ffffffff81a68dc4: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4bfe0)
Location: net/core/devlink.c:10509
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_flash_device
```
**Symbols:**

```
ffffffff81a4bfe0-ffffffff81a4c184: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b04430)
Location: net/core/devlink.c:11451
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_flash_device
```
**Symbols:**

```
ffffffff81b04430-ffffffff81b04631: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct devlink *devlink, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c89d40)
Location: net/core/devlink.c:12047
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81c89d40-ffffffff81c89e91: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct devlink *devlink, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e44930)
Location: net/core/devlink.c:12928
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff81e44930-ffffffff81e44a81: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct devlink *devlink, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82045590)
Location: net/devlink/dev.c:1135
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff82045590-ffffffff82045704: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct devlink *devlink, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dev.c (ffffffff82104e90)
Location: net/devlink/dev.c:1236
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
**Symbols:**

```
ffffffff82104e90-ffffffff82105004: devlink_compat_flash_update (STB_GLOBAL)
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
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c30690)
Location: net/core/devlink.c:8060
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_flash_device
```
**Symbols:**

```
ffff800010c30690-ffff800010c30778: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d47688)
Location: net/core/devlink.c:8060
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_flash_device
```
**Symbols:**

```
c0d47688-c0d4776c: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d294d0)
Location: net/core/devlink.c:8060
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_flash_device
```
**Symbols:**

```
c000000000d294d0-c000000000d29628: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a6834)
Location: net/core/devlink.c:8060
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_flash_device
```
**Symbols:**

```
ffffffe0007a6834-ffffffe0007a6912: devlink_compat_flash_update (STB_GLOBAL)
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
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819285a0)
Location: net/core/devlink.c:8060
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_flash_device
```
**Symbols:**

```
ffffffff819285a0-ffffffff81928659: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e2350)
Location: net/core/devlink.c:8060
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_flash_device
```
**Symbols:**

```
ffffffff818e2350-ffffffff818e2409: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81979730)
Location: net/core/devlink.c:8060
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_flash_device
```
**Symbols:**

```
ffffffff81979730-ffffffff819797e9: devlink_compat_flash_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_compat_flash_update(struct net_device *dev, const char *file_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199bc20)
Location: net/core/devlink.c:8060
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_flash_device
```
**Symbols:**

```
ffffffff8199bc20-ffffffff8199bcd9: devlink_compat_flash_update (STB_GLOBAL)
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
