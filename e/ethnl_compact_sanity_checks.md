# Function: <code>ethnl_compact_sanity_checks</code>

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
int ethnl_compact_sanity_checks(unsigned int nbits, const struct nlattr *nest, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81a869b0)
Location: net/ethtool/bitset.c:482
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff81a869b0-ffffffff81a86bee: ethnl_compact_sanity_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethnl_compact_sanity_checks(unsigned int nbits, const struct nlattr *nest, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81a902c0)
Location: net/ethtool/bitset.c:480
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff81a902c0-ffffffff81a90529: ethnl_compact_sanity_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethnl_compact_sanity_checks(unsigned int nbits, const struct nlattr *nest, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/bitset.c (ffffffff81a799e0)
Location: net/ethtool/bitset.c:480
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff81a799e0-ffffffff81a79cb0: ethnl_compact_sanity_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ethnl_compact_sanity_checks(unsigned int nbits, const struct nlattr *nest, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:480
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
```
**Symbols:**

```
ffffffff81b33f60-ffffffff81b34265: ethnl_compact_sanity_checks (STB_LOCAL)
ffffffff81d3976b-ffffffff81d39788: ethnl_compact_sanity_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ethnl_compact_sanity_checks(unsigned int nbits, const struct nlattr *nest, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:480
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
```
**Symbols:**

```
ffffffff81cbf6c0-ffffffff81cbf9af: ethnl_compact_sanity_checks (STB_LOCAL)
ffffffff81f05ee6-ffffffff81f05f01: ethnl_compact_sanity_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ethnl_compact_sanity_checks(unsigned int nbits, const struct nlattr *nest, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:480
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
```
**Symbols:**

```
ffffffff81e7e280-ffffffff81e7e56f: ethnl_compact_sanity_checks (STB_LOCAL)
ffffffff820adbe9-ffffffff820adc04: ethnl_compact_sanity_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ethnl_compact_sanity_checks(unsigned int nbits, const struct nlattr *nest, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:480
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
```
**Symbols:**

```
ffffffff81eda840-ffffffff81edab2f: ethnl_compact_sanity_checks (STB_LOCAL)
ffffffff8212ee37-ffffffff8212ee52: ethnl_compact_sanity_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ethnl_compact_sanity_checks(unsigned int nbits, const struct nlattr *nest, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/bitset.c (0)
Location: net/ethtool/bitset.c:480
Inline: False
Direct callers:
  - net/ethtool/bitset.c:ethnl_parse_bitset
  - net/ethtool/bitset.c:ethnl_update_bitset32
```
**Symbols:**

```
ffffffff81f9e620-ffffffff81f9e8ee: ethnl_compact_sanity_checks (STB_LOCAL)
ffffffff82210bc8-ffffffff82210be3: ethnl_compact_sanity_checks.cold (STB_LOCAL)
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
