# Function: <code>strset_cleanup_data</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void strset_cleanup_data(struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81a88516)
Location: net/ethtool/strset.c:196
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81a87b50-ffffffff81a87b9a: strset_cleanup_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void strset_cleanup_data(struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81a91e86)
Location: net/ethtool/strset.c:197
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81a914e0-ffffffff81a9152a: strset_cleanup_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void strset_cleanup_data(struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81a7b304)
Location: net/ethtool/strset.c:222
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81a7ad00-ffffffff81a7ad4a: strset_cleanup_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void strset_cleanup_data(struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/strset.c (0)
Location: net/ethtool/strset.c:222
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81b35120-ffffffff81b3517d: strset_cleanup_data (STB_LOCAL)
ffffffff81d3986e-ffffffff81d39883: strset_cleanup_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void strset_cleanup_data(struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/strset.c (0)
Location: net/ethtool/strset.c:222
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81cc0950-ffffffff81cc09b5: strset_cleanup_data (STB_LOCAL)
ffffffff81f05fdb-ffffffff81f05ff0: strset_cleanup_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void strset_cleanup_data(struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/strset.c (0)
Location: net/ethtool/strset.c:222
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81e7f5f0-ffffffff81e7f655: strset_cleanup_data (STB_LOCAL)
ffffffff820adcc6-ffffffff820adcdb: strset_cleanup_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void strset_cleanup_data(struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/strset.c (0)
Location: net/ethtool/strset.c:222
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81edbbe0-ffffffff81edbcaf: strset_cleanup_data (STB_LOCAL)
ffffffff8212ef14-ffffffff8212ef29: strset_cleanup_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void strset_cleanup_data(struct ethnl_reply_data *reply_base);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/strset.c (0)
Location: net/ethtool/strset.c:222
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81f9f9a0-ffffffff81f9fa6f: strset_cleanup_data (STB_LOCAL)
ffffffff82210ca5-ffffffff82210cba: strset_cleanup_data.cold (STB_LOCAL)
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
