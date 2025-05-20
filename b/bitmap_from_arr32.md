# Function: <code>bitmap_from_arr32</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c34d0)
Location: lib/bitmap.c:1135
Inline: True
Direct callers:
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/ethtool.c:load_link_ksettings_from_user
```
**Symbols:**

```
ffffffff814c34d0-ffffffff814c353a: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d77e0)
Location: lib/bitmap.c:1149
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
ffffffff814d77e0-ffffffff814d7846: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815036c0)
Location: lib/bitmap.c:1177
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
ffffffff815036c0-ffffffff81503726: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81521660)
Location: lib/bitmap.c:1197
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
ffffffff81521660-ffffffff815216c6: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815846c0)
Location: lib/bitmap.c:1272
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff815846c0-ffffffff81584720: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a17d0)
Location: lib/bitmap.c:1272
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff815a17d0-ffffffff815a1830: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8680)
Location: lib/bitmap.c:1315
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff815a8680-ffffffff815a86e0: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611640)
Location: lib/bitmap.c:1446
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff81611640-ffffffff816116a0: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816dd790)
Location: lib/bitmap.c:1476
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff816dd790-ffffffff816dd80a: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cd6c0)
Location: lib/bitmap.c:1457
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff817cd6c0-ffffffff817cd73a: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180bad0)
Location: lib/bitmap.c:1457
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff8180bad0-ffffffff8180bb4a: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff818522b0)
Location: lib/bitmap.c:781
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/ioctl.c:load_link_ksettings_from_user
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff818522b0-ffffffff8185232a: bitmap_from_arr32 (STB_GLOBAL)
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
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062ad90)
Location: lib/bitmap.c:1197
Inline: False
Direct callers:
  - arch/arm64/kernel/perf_event.c:__armv8pmu_probe_pmu
  - arch/arm64/kernel/perf_event.c:__armv8pmu_probe_pmu
  - net/core/ethtool.c:ethtool_set_per_queue_coalesce
  - net/core/ethtool.c:ethtool_get_per_queue_coalesce
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/ethtool.c:load_link_ksettings_from_user
  - net/core/ethtool.c:load_link_ksettings_from_user
```
**Symbols:**

```
ffff80001062ad90-ffff80001062ae14: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cd090)
Location: lib/bitmap.c:1197
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
c0000000007cd090-c0000000007cd140: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045b67a)
Location: lib/bitmap.c:1197
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
ffffffe00045b67a-ffffffe00045b6fa: bitmap_from_arr32 (STB_GLOBAL)
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
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81519c40)
Location: lib/bitmap.c:1197
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
ffffffff81519c40-ffffffff81519ca6: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81509f30)
Location: lib/bitmap.c:1197
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
ffffffff81509f30-ffffffff81509f96: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81515cd0)
Location: lib/bitmap.c:1197
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
ffffffff81515cd0-ffffffff81515d36: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bitmap_from_arr32(long unsigned int *bitmap, const u32 *buf, unsigned int nbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f460)
Location: lib/bitmap.c:1197
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
ffffffff8152f460-ffffffff8152f4c6: bitmap_from_arr32 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
