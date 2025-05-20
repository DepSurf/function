# Function: <code>ethnl_update_bitset32</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ethnl_update_bitset32(u32 *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81a87b25)
Location: net/ethtool/bitset.c:554
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_update_bitset
Direct callers:
  - net/ethtool/bitset.c:ethnl_update_bitset
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
```
**Symbols:**

```
ffffffff81a86fe0-ffffffff81a871ad: ethnl_update_bitset32.part.0 (STB_LOCAL)
ffffffff81a877d0-ffffffff81a877e8: ethnl_update_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ethnl_update_bitset32(u32 *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81a914c5)
Location: net/ethtool/bitset.c:552
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_update_bitset
Direct callers:
  - net/ethtool/bitset.c:ethnl_update_bitset
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
```
**Symbols:**

```
ffffffff81a90960-ffffffff81a90b35: ethnl_update_bitset32.part.0 (STB_LOCAL)
ffffffff81a91150-ffffffff81a91168: ethnl_update_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ethnl_update_bitset32(u32 *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81a7ace5)
Location: net/ethtool/bitset.c:552
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_update_bitset
Direct callers:
  - net/ethtool/bitset.c:ethnl_update_bitset
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/eee.c:ethnl_set_eee
  - net/ethtool/eee.c:ethnl_set_eee
```
**Symbols:**

```
ffffffff81a7a150-ffffffff81a7a335: ethnl_update_bitset32.part.0 (STB_LOCAL)
ffffffff81a7a960-ffffffff81a7a978: ethnl_update_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ethnl_update_bitset32(u32 *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81b35105)
Location: net/ethtool/bitset.c:552
Inline: True
Inline callers:
  - net/ethtool/bitset.c:ethnl_update_bitset
Direct callers:
  - net/ethtool/bitset.c:ethnl_update_bitset
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/eee.c:ethnl_set_eee
```
**Symbols:**

```
ffffffff81b34570-ffffffff81b3474f: ethnl_update_bitset32.part.0 (STB_LOCAL)
ffffffff81b34d70-ffffffff81b34d88: ethnl_update_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethnl_update_bitset32(u32 *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81cc0350)
Location: net/ethtool/bitset.c:552
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_update_bitset
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/eee.c:ethnl_set_eee
```
**Symbols:**

```
ffffffff81cc0350-ffffffff81cc055b: ethnl_update_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethnl_update_bitset32(u32 *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81e7ef90)
Location: net/ethtool/bitset.c:552
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_update_bitset
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/eee.c:ethnl_set_eee
```
**Symbols:**

```
ffffffff81e7ef90-ffffffff81e7f19b: ethnl_update_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethnl_update_bitset32(u32 *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81edb580)
Location: net/ethtool/bitset.c:552
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_update_bitset
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/eee.c:ethnl_set_eee
```
**Symbols:**

```
ffffffff81edb580-ffffffff81edb78c: ethnl_update_bitset32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethnl_update_bitset32(u32 *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81f9f340)
Location: net/ethtool/bitset.c:552
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_update_bitset
  - net/ethtool/debug.c:ethnl_set_debug
  - net/ethtool/wol.c:ethnl_set_wol
  - net/ethtool/privflags.c:ethnl_set_privflags
  - net/ethtool/eee.c:ethnl_set_eee
```
**Symbols:**

```
ffffffff81f9f340-ffffffff81f9f54f: ethnl_update_bitset32 (STB_GLOBAL)
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
