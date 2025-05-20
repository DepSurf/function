# Function: <code>strset_include</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81a88030)
Location: net/ethtool/strset.c:117
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/strset.c:strset_prepare_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81a919e0)
Location: net/ethtool/strset.c:119
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/strset.c:strset_prepare_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81a7b416)
Location: net/ethtool/strset.c:144
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_prepare_data
  - net/ethtool/strset.c:strset_prepare_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool strset_include(const struct strset_req_info *info, const struct strset_reply_data *data, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/strset.c (ffffffff81b351d3)
Location: net/ethtool/strset.c:144
Inline: True
Direct callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81b35180-ffffffff81b351e0: strset_include (STB_LOCAL)
ffffffff81d39883-ffffffff81d398a6: strset_include.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool strset_include(const struct strset_req_info *info, const struct strset_reply_data *data, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/strset.c (ffffffff81cc0a15)
Location: net/ethtool/strset.c:144
Inline: True
Direct callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81cc09c0-ffffffff81cc0a39: strset_include (STB_LOCAL)
ffffffff81f05ff0-ffffffff81f06013: strset_include.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool strset_include(const struct strset_req_info *info, const struct strset_reply_data *data, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/strset.c (ffffffff81e7f6c5)
Location: net/ethtool/strset.c:144
Inline: True
Direct callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81e7f670-ffffffff81e7f6e9: strset_include (STB_LOCAL)
ffffffff820adcdb-ffffffff820adcfe: strset_include.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool strset_include(const struct strset_req_info *info, const struct strset_reply_data *data, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/strset.c (ffffffff81edbd26)
Location: net/ethtool/strset.c:144
Inline: True
Direct callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81edbcc0-ffffffff81edbd76: strset_include (STB_LOCAL)
ffffffff8212ef29-ffffffff8212ef44: strset_include.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool strset_include(const struct strset_req_info *info, const struct strset_reply_data *data, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/strset.c (ffffffff81f9fae6)
Location: net/ethtool/strset.c:144
Inline: True
Direct callers:
  - net/ethtool/strset.c:strset_fill_reply
  - net/ethtool/strset.c:strset_reply_size
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81f9fa80-ffffffff81f9fb36: strset_include (STB_LOCAL)
ffffffff82210cba-ffffffff82210cd5: strset_include.cold (STB_LOCAL)
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
