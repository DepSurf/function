# Function: <code>ethnl_parse_bitset</code>

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
int ethnl_parse_bitset(long unsigned int *val, long unsigned int *mask, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81a877f0)
Location: net/ethtool/bitset.c:606
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81a877f0-ffffffff81a87ad6: ethnl_parse_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethnl_parse_bitset(long unsigned int *val, long unsigned int *mask, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81a91170)
Location: net/ethtool/bitset.c:604
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81a91170-ffffffff81a91477: ethnl_parse_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethnl_parse_bitset(long unsigned int *val, long unsigned int *mask, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81a7a980)
Location: net/ethtool/bitset.c:604
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81a7a980-ffffffff81a7aca0: ethnl_parse_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethnl_parse_bitset(long unsigned int *val, long unsigned int *mask, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:604
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81d39837-ffffffff81d3986e: ethnl_parse_bitset.cold (STB_LOCAL)
ffffffff81b34d90-ffffffff81b350be: ethnl_parse_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethnl_parse_bitset(long unsigned int *val, long unsigned int *mask, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:604
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff81f05fba-ffffffff81f05fdb: ethnl_parse_bitset.cold (STB_LOCAL)
ffffffff81cc0560-ffffffff81cc08bb: ethnl_parse_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ethnl_parse_bitset(long unsigned int *val, long unsigned int *mask, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:604
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff820adca5-ffffffff820adcc6: ethnl_parse_bitset.cold (STB_LOCAL)
ffffffff81e7f1b0-ffffffff81e7f512: ethnl_parse_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ethnl_parse_bitset(long unsigned int *val, long unsigned int *mask, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:604
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff8212eef3-ffffffff8212ef14: ethnl_parse_bitset.cold (STB_LOCAL)
ffffffff81edb7a0-ffffffff81edbb02: ethnl_parse_bitset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ethnl_parse_bitset(long unsigned int *val, long unsigned int *mask, unsigned int nbits, const struct nlattr *attr, ethnl_string_array_t names, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:604
Inline: False
Direct callers:
  - net/ethtool/features.c:ethnl_set_features
```
**Symbols:**

```
ffffffff82210c84-ffffffff82210ca5: ethnl_parse_bitset.cold (STB_LOCAL)
ffffffff81f9f560-ffffffff81f9f8c9: ethnl_parse_bitset (STB_GLOBAL)
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
