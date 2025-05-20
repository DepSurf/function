# Function: <code>ethtool_rxnfc_copy_to_user</code>

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
int ethtool_rxnfc_copy_to_user(void *useraddr, const struct ethtool_rxnfc *rxnfc, size_t size, const u32 *rule_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81b2ecb0)
Location: net/ethtool/ioctl.c:899
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_set_rxnfc
```
**Symbols:**

```
ffffffff81b2ecb0-ffffffff81b2ed75: ethtool_rxnfc_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethtool_rxnfc_copy_to_user(void *useraddr, const struct ethtool_rxnfc *rxnfc, size_t size, const u32 *rule_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81cb9310)
Location: net/ethtool/ioctl.c:921
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_set_rxnfc
```
**Symbols:**

```
ffffffff81cb9310-ffffffff81cb93dc: ethtool_rxnfc_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethtool_rxnfc_copy_to_user(void *useraddr, const struct ethtool_rxnfc *rxnfc, size_t size, const u32 *rule_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81e77ab0)
Location: net/ethtool/ioctl.c:909
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_set_rxnfc
```
**Symbols:**

```
ffffffff81e77ab0-ffffffff81e77b7c: ethtool_rxnfc_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethtool_rxnfc_copy_to_user(void *useraddr, const struct ethtool_rxnfc *rxnfc, size_t size, const u32 *rule_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81ed3c30)
Location: net/ethtool/ioctl.c:910
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_set_rxnfc
```
**Symbols:**

```
ffffffff81ed3c30-ffffffff81ed3cfc: ethtool_rxnfc_copy_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethtool_rxnfc_copy_to_user(void *useraddr, const struct ethtool_rxnfc *rxnfc, size_t size, const u32 *rule_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/ioctl.c (ffffffff81f97620)
Location: net/ethtool/ioctl.c:945
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:ethtool_get_rxnfc
  - net/ethtool/ioctl.c:ethtool_set_rxnfc
```
**Symbols:**

```
ffffffff81f97620-ffffffff81f976f8: ethtool_rxnfc_copy_to_user (STB_LOCAL)
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
