# Function: <code>ethtool_rxnfc_copy_from_compat</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ethtool_rxnfc_copy_from_compat(struct ethtool_rxnfc *rxnfc, const struct compat_ethtool_rxnfc *useraddr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81b2c790)
Location: net/ethtool/ioctl.c:813
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_from_user
```
**Symbols:**

```
ffffffff81b2c790-ffffffff81b2c93f: ethtool_rxnfc_copy_from_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethtool_rxnfc_copy_from_compat(struct ethtool_rxnfc *rxnfc, const struct compat_ethtool_rxnfc *useraddr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81cb7300)
Location: net/ethtool/ioctl.c:835
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_from_user
```
**Symbols:**

```
ffffffff81cb7300-ffffffff81cb74ae: ethtool_rxnfc_copy_from_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethtool_rxnfc_copy_from_compat(struct ethtool_rxnfc *rxnfc, const struct compat_ethtool_rxnfc *useraddr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e75590)
Location: net/ethtool/ioctl.c:823
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_from_user
```
**Symbols:**

```
ffffffff81e75590-ffffffff81e7573e: ethtool_rxnfc_copy_from_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethtool_rxnfc_copy_from_compat(struct ethtool_rxnfc *rxnfc, const struct compat_ethtool_rxnfc *useraddr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81ed1770)
Location: net/ethtool/ioctl.c:824
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_from_user
```
**Symbols:**

```
ffffffff81ed1770-ffffffff81ed191e: ethtool_rxnfc_copy_from_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethtool_rxnfc_copy_from_compat(struct ethtool_rxnfc *rxnfc, const struct compat_ethtool_rxnfc *useraddr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81f95290)
Location: net/ethtool/ioctl.c:827
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_rxnfc_copy_from_user
```
**Symbols:**

```
ffffffff81f95290-ffffffff81f9543e: ethtool_rxnfc_copy_from_compat (STB_LOCAL)
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
