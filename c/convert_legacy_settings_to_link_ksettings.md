# Function: <code>convert_legacy_settings_to_link_ksettings</code>

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
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81787c00)
Location: net/core/ethtool.c:431
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_set_settings
```
**Symbols:**

```
ffffffff81787c00-ffffffff81787ca3: convert_legacy_settings_to_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817b51c0)
Location: net/core/ethtool.c:442
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_set_settings
```
**Symbols:**

```
ffffffff817b51c0-ffffffff817b5263: convert_legacy_settings_to_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff817d3d10)
Location: net/core/ethtool.c:445
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
```
**Symbols:**

```
ffffffff817d3d10-ffffffff817d3db3: convert_legacy_settings_to_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8184e220)
Location: net/core/ethtool.c:458
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
```
**Symbols:**

```
ffffffff8184e220-ffffffff8184e2bb: convert_legacy_settings_to_link_ksettings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff81899380)
Location: net/core/ethtool.c:437
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_set_settings
  - net/core/ethtool.c:__ethtool_get_link_ksettings
```
**Symbols:**

```
ffffffff81899380-ffffffff8189941c: convert_legacy_settings_to_link_ksettings (STB_LOCAL)
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
In net/core/ethtool.c (ffffffff818bc926)
Location: net/core/ethtool.c:439
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8190928b)
Location: net/core/ethtool.c:438
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8193b9cb)
Location: net/core/ethtool.c:439
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a85530)
Location: net/ethtool/common.c:263
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_settings
```
**Symbols:**

```
ffffffff81a85530-ffffffff81a85607: convert_legacy_settings_to_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a8eec0)
Location: net/ethtool/common.c:290
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_settings
```
**Symbols:**

```
ffffffff81a8eec0-ffffffff81a8ef97: convert_legacy_settings_to_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a785c0)
Location: net/ethtool/common.c:443
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_settings
```
**Symbols:**

```
ffffffff81a785c0-ffffffff81a78697: convert_legacy_settings_to_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81b326b0)
Location: net/ethtool/common.c:445
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_settings
```
**Symbols:**

```
ffffffff81b326b0-ffffffff81b32787: convert_legacy_settings_to_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81cbdc10)
Location: net/ethtool/common.c:449
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_settings
```
**Symbols:**

```
ffffffff81cbdc10-ffffffff81cbdcf3: convert_legacy_settings_to_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81e7c3f0)
Location: net/ethtool/common.c:464
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_settings
```
**Symbols:**

```
ffffffff81e7c3f0-ffffffff81e7c4d3: convert_legacy_settings_to_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81ed8790)
Location: net/ethtool/common.c:472
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_settings
```
**Symbols:**

```
ffffffff81ed8790-ffffffff81ed8873: convert_legacy_settings_to_link_ksettings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool convert_legacy_settings_to_link_ksettings(struct ethtool_link_ksettings *link_ksettings, const struct ethtool_cmd *legacy_settings);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81f9c5a0)
Location: net/ethtool/common.c:472
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_settings
```
**Symbols:**

```
ffffffff81f9c5a0-ffffffff81f9c683: convert_legacy_settings_to_link_ksettings (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffff800010bd9c10)
Location: net/core/ethtool.c:439
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
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
In net/core/ethtool.c (c0cf4c68)
Location: net/core/ethtool.c:439
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (c000000000cba0c8)
Location: net/core/ethtool.c:439
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffe0007619fa)
Location: net/core/ethtool.c:439
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818db99b)
Location: net/core/ethtool.c:439
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff818957db)
Location: net/core/ethtool.c:439
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8192c9cb)
Location: net/core/ethtool.c:439
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/ethtool.c (ffffffff8194e09b)
Location: net/core/ethtool.c:439
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_set_settings
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
