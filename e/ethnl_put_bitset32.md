# Function: <code>ethnl_put_bitset32</code>

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
int ethnl_put_bitset32(struct sk_buff *skb, int attrtype, const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:232
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_put_bitset
  - net/ethtool/debug.c:debug_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/privflags.c:privflags_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
```
**Symbols:**

```
ffffffff81a87b44-ffffffff81a87b50: ethnl_put_bitset32.cold (STB_LOCAL)
ffffffff81a87340-ffffffff81a8771b: ethnl_put_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ethnl_put_bitset32(struct sk_buff *skb, int attrtype, const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:232
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_put_bitset
  - net/ethtool/debug.c:debug_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/privflags.c:privflags_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
**Symbols:**

```
ffffffff81c3234b-ffffffff81c32357: ethnl_put_bitset32.cold (STB_LOCAL)
ffffffff81a90cd0-ffffffff81a91099: ethnl_put_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ethnl_put_bitset32(struct sk_buff *skb, int attrtype, const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:232
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_put_bitset
  - net/ethtool/debug.c:debug_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/privflags.c:privflags_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
**Symbols:**

```
ffffffff81c24634-ffffffff81c24640: ethnl_put_bitset32.cold (STB_LOCAL)
ffffffff81a7a4d0-ffffffff81a7a895: ethnl_put_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethnl_put_bitset32(struct sk_buff *skb, int attrtype, const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:232
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_put_bitset
  - net/ethtool/debug.c:debug_fill_reply
  - net/ethtool/wol.c:wol_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/privflags.c:privflags_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
**Symbols:**

```
ffffffff81d3982b-ffffffff81d39837: ethnl_put_bitset32.cold (STB_LOCAL)
ffffffff81b348e0-ffffffff81b34cb0: ethnl_put_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethnl_put_bitset32(struct sk_buff *skb, int attrtype, const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:232
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_put_bitset
  - net/ethtool/debug.c:debug_fill_reply
  - net/ethtool/wol.c:wol_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/privflags.c:privflags_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
**Symbols:**

```
ffffffff81f05fae-ffffffff81f05fba: ethnl_put_bitset32.cold (STB_LOCAL)
ffffffff81cbfe90-ffffffff81cc026b: ethnl_put_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethnl_put_bitset32(struct sk_buff *skb, int attrtype, const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81e7eaa0)
Location: net/ethtool/bitset.c:232
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_put_bitset
  - net/ethtool/debug.c:debug_fill_reply
  - net/ethtool/wol.c:wol_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/privflags.c:privflags_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
**Symbols:**

```
ffffffff81e7eaa0-ffffffff81e7ee87: ethnl_put_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethnl_put_bitset32(struct sk_buff *skb, int attrtype, const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81edb090)
Location: net/ethtool/bitset.c:232
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_put_bitset
  - net/ethtool/debug.c:debug_fill_reply
  - net/ethtool/wol.c:wol_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/privflags.c:privflags_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
**Symbols:**

```
ffffffff81edb090-ffffffff81edb47a: ethnl_put_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethnl_put_bitset32(struct sk_buff *skb, int attrtype, const u32 *val, const u32 *mask, unsigned int nbits, ethnl_string_array_t names, bool compact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81f9ee50)
Location: net/ethtool/bitset.c:232
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_put_bitset
  - net/ethtool/debug.c:debug_fill_reply
  - net/ethtool/wol.c:wol_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/features.c:features_fill_reply
  - net/ethtool/privflags.c:privflags_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/eee.c:eee_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tsinfo.c:tsinfo_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
  - net/ethtool/tunnels.c:ethnl_tunnel_info_fill_reply
```
**Symbols:**

```
ffffffff81f9ee50-ffffffff81f9f23a: ethnl_put_bitset32 (STB_GLOBAL)
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
