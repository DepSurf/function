# Function: <code>__ethtool_get_ts_info</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ethtool_get_ts_info(struct net_device *dev, struct ethtool_ts_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a85760)
Location: net/ethtool/common.c:357
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
**Symbols:**

```
ffffffff81a85760-ffffffff81a857f1: __ethtool_get_ts_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ethtool_get_ts_info(struct net_device *dev, struct ethtool_ts_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a8f0f0)
Location: net/ethtool/common.c:384
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
**Symbols:**

```
ffffffff81a8f0f0-ffffffff81a8f181: __ethtool_get_ts_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ethtool_get_ts_info(struct net_device *dev, struct ethtool_ts_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a787f0)
Location: net/ethtool/common.c:537
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
**Symbols:**

```
ffffffff81a787f0-ffffffff81a78881: __ethtool_get_ts_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ethtool_get_ts_info(struct net_device *dev, struct ethtool_ts_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81b328e0)
Location: net/ethtool/common.c:539
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/common.c:ethtool_get_phc_vclocks
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
**Symbols:**

```
ffffffff81b328e0-ffffffff81b32971: __ethtool_get_ts_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ethtool_get_ts_info(struct net_device *dev, struct ethtool_ts_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81cbde60)
Location: net/ethtool/common.c:543
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/common.c:ethtool_get_phc_vclocks
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
**Symbols:**

```
ffffffff81cbde60-ffffffff81cbdf12: __ethtool_get_ts_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ethtool_get_ts_info(struct net_device *dev, struct ethtool_ts_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81e7c8a0)
Location: net/ethtool/common.c:624
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/common.c:ethtool_get_phc_vclocks
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
**Symbols:**

```
ffffffff81e7c8a0-ffffffff81e7c952: __ethtool_get_ts_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ethtool_get_ts_info(struct net_device *dev, struct ethtool_ts_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81ed8c60)
Location: net/ethtool/common.c:632
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/common.c:ethtool_get_phc_vclocks
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
**Symbols:**

```
ffffffff81ed8c60-ffffffff81ed8d12: __ethtool_get_ts_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ethtool_get_ts_info(struct net_device *dev, struct ethtool_ts_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81f9cad0)
Location: net/ethtool/common.c:632
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/common.c:ethtool_get_ts_info_by_layer
  - net/ethtool/common.c:ethtool_get_phc_vclocks
  - net/ethtool/tsinfo.c:tsinfo_prepare_data
```
**Symbols:**

```
ffffffff81f9cad0-ffffffff81f9cb82: __ethtool_get_ts_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
