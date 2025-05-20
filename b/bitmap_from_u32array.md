# Function: <code>bitmap_from_u32array</code>

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
unsigned int bitmap_from_u32array(long unsigned int *bitmap, unsigned int nbits, const u32 *buf, unsigned int nwords);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814401f0)
Location: lib/bitmap.c:1079
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/ethtool.c:load_link_ksettings_from_user
```
**Symbols:**

```
ffffffff814401f0-ffffffff814402a3: bitmap_from_u32array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int bitmap_from_u32array(long unsigned int *bitmap, unsigned int nbits, const u32 *buf, unsigned int nwords);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145d2f0)
Location: lib/bitmap.c:1121
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/ethtool.c:load_link_ksettings_from_user
```
**Symbols:**

```
ffffffff8145d2f0-ffffffff8145d3a3: bitmap_from_u32array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int bitmap_from_u32array(long unsigned int *bitmap, unsigned int nbits, const u32 *buf, unsigned int nwords);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814625d0)
Location: lib/bitmap.c:1127
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/ethtool.c:load_link_ksettings_from_user
```
**Symbols:**

```
ffffffff814625d0-ffffffff8146266d: bitmap_from_u32array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int bitmap_from_u32array(long unsigned int *bitmap, unsigned int nbits, const u32 *buf, unsigned int nwords);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148e4b0)
Location: lib/bitmap.c:1123
Inline: False
Direct callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/ethtool.c:load_link_ksettings_from_user
```
**Symbols:**

```
ffffffff8148e4b0-ffffffff8148e54d: bitmap_from_u32array (STB_GLOBAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
