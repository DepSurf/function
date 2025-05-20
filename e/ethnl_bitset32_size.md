# Function: <code>ethnl_bitset32_size</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ethnl_bitset32_size(const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:171
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_bitset_size
  - net/ethtool/debug.c:debug_reply_size
  - net/ethtool/wol.c:wol_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/privflags.c:privflags_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
```
**Symbols:**

```
ffffffff81a87b38-ffffffff81a87b44: ethnl_bitset32_size.cold (STB_LOCAL)
ffffffff81a871b0-ffffffff81a8733d: ethnl_bitset32_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ethnl_bitset32_size(const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:171
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_bitset_size
  - net/ethtool/debug.c:debug_reply_size
  - net/ethtool/wol.c:wol_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/privflags.c:privflags_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tunnels.c:ethnl_tunnel_info_reply_size
  - net/ethtool/tunnels.c:ethnl_tunnel_info_reply_size
```
**Symbols:**

```
ffffffff81c3233f-ffffffff81c3234b: ethnl_bitset32_size.cold (STB_LOCAL)
ffffffff81a90b40-ffffffff81a90ccd: ethnl_bitset32_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ethnl_bitset32_size(const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:171
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_bitset_size
  - net/ethtool/debug.c:debug_reply_size
  - net/ethtool/wol.c:wol_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/privflags.c:privflags_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81c24628-ffffffff81c24634: ethnl_bitset32_size.cold (STB_LOCAL)
ffffffff81a7a340-ffffffff81a7a4c7: ethnl_bitset32_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethnl_bitset32_size(const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:171
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_bitset_size
  - net/ethtool/debug.c:debug_reply_size
  - net/ethtool/wol.c:wol_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/privflags.c:privflags_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81d3981f-ffffffff81d3982b: ethnl_bitset32_size.cold (STB_LOCAL)
ffffffff81b34750-ffffffff81b348d7: ethnl_bitset32_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethnl_bitset32_size(const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:171
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_bitset_size
  - net/ethtool/debug.c:debug_reply_size
  - net/ethtool/wol.c:wol_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/privflags.c:privflags_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81f05fa2-ffffffff81f05fae: ethnl_bitset32_size.cold (STB_LOCAL)
ffffffff81cbfd00-ffffffff81cbfe89: ethnl_bitset32_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethnl_bitset32_size(const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81e7e8f0)
Location: net/ethtool/bitset.c:171
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_bitset_size
  - net/ethtool/debug.c:debug_reply_size
  - net/ethtool/wol.c:wol_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/privflags.c:privflags_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81e7e8f0-ffffffff81e7ea85: ethnl_bitset32_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethnl_bitset32_size(const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81edaeb0)
Location: net/ethtool/bitset.c:171
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_bitset_size
  - net/ethtool/debug.c:debug_reply_size
  - net/ethtool/wol.c:wol_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/privflags.c:privflags_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81edaeb0-ffffffff81edb078: ethnl_bitset32_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethnl_bitset32_size(const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81f9ec70)
Location: net/ethtool/bitset.c:171
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_bitset_size
  - net/ethtool/debug.c:debug_reply_size
  - net/ethtool/wol.c:wol_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/features.c:features_reply_size
  - net/ethtool/privflags.c:privflags_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/eee.c:eee_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tsinfo.c:tsinfo_reply_size
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_doit
```
**Symbols:**

```
ffffffff81f9ec70-ffffffff81f9ee38: ethnl_bitset32_size (STB_GLOBAL)
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
