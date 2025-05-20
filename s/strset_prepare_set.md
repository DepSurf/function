# Function: <code>strset_prepare_set</code>

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
In net/ethtool/strset.c (ffffffff81a882f4)
Location: net/ethtool/strset.c:209
Inline: True
Inline callers:
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
In net/ethtool/strset.c (ffffffff81a91cae)
Location: net/ethtool/strset.c:210
Inline: True
Inline callers:
  - net/ethtool/strset.c:strset_prepare_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int strset_prepare_set(struct strset_info *info, struct net_device *dev, unsigned int id, bool counts_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81a7af30)
Location: net/ethtool/strset.c:235
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81a7af30-ffffffff81a7b08e: strset_prepare_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int strset_prepare_set(struct strset_info *info, struct net_device *dev, unsigned int id, bool counts_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81b354a0)
Location: net/ethtool/strset.c:235
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81b354a0-ffffffff81b355fe: strset_prepare_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int strset_prepare_set(struct strset_info *info, struct net_device *dev, unsigned int id, bool counts_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81cc0d10)
Location: net/ethtool/strset.c:235
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81cc0d10-ffffffff81cc0e62: strset_prepare_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int strset_prepare_set(struct strset_info *info, struct net_device *dev, unsigned int id, bool counts_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81e7fa20)
Location: net/ethtool/strset.c:235
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81e7fa20-ffffffff81e7fb72: strset_prepare_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int strset_prepare_set(struct strset_info *info, struct net_device *dev, unsigned int id, bool counts_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81edc0d0)
Location: net/ethtool/strset.c:235
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81edc0d0-ffffffff81edc230: strset_prepare_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int strset_prepare_set(struct strset_info *info, struct net_device *dev, unsigned int id, bool counts_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/strset.c (ffffffff81f9fea0)
Location: net/ethtool/strset.c:235
Inline: False
Direct callers:
  - net/ethtool/strset.c:strset_prepare_data
```
**Symbols:**

```
ffffffff81f9fea0-ffffffff81fa0000: strset_prepare_set (STB_LOCAL)
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
