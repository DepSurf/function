# Function: <code>ethnl_update_bitset</code>

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
int ethnl_update_bitset(long unsigned int *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81a87b20)
Location: net/ethtool/bitset.c:825
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
**Symbols:**

```
ffffffff81a87b20-ffffffff81a87b38: ethnl_update_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethnl_update_bitset(long unsigned int *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81a914c0)
Location: net/ethtool/bitset.c:825
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
```
**Symbols:**

```
ffffffff81a914c0-ffffffff81a914d8: ethnl_update_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethnl_update_bitset(long unsigned int *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81a7ace0)
Location: net/ethtool/bitset.c:825
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
```
**Symbols:**

```
ffffffff81a7ace0-ffffffff81a7acf8: ethnl_update_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ethnl_update_bitset(long unsigned int *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81b35100)
Location: net/ethtool/bitset.c:825
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/fec.c:ethnl_set_fec
```
**Symbols:**

```
ffffffff81b35100-ffffffff81b35118: ethnl_update_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethnl_update_bitset(long unsigned int *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81cc0920)
Location: net/ethtool/bitset.c:825
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/fec.c:ethnl_set_fec
```
**Symbols:**

```
ffffffff81cc0920-ffffffff81cc0942: ethnl_update_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethnl_update_bitset(long unsigned int *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81e7f5b0)
Location: net/ethtool/bitset.c:825
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/fec.c:ethnl_set_fec
```
**Symbols:**

```
ffffffff81e7f5b0-ffffffff81e7f5d2: ethnl_update_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethnl_update_bitset(long unsigned int *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81edbba0)
Location: net/ethtool/bitset.c:825
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/stats.c:stats_parse_request
```
**Symbols:**

```
ffffffff81edbba0-ffffffff81edbbc2: ethnl_update_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethnl_update_bitset(long unsigned int *bitmap, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack, bool *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81f9f960)
Location: net/ethtool/bitset.c:825
Inline: False
Direct callers:
  - net/ethtool/linkmodes.c:ethnl_update_linkmodes
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/stats.c:stats_parse_request
```
**Symbols:**

```
ffffffff81f9f960-ffffffff81f9f982: ethnl_update_bitset (STB_GLOBAL)
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
