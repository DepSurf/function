# Function: <code>ethtool_link_modes_to_fecparam</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81a819e5)
Location: net/ethtool/fec.c:48
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81b3b6b6)
Location: net/ethtool/fec.c:48
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81cc76b8)
Location: net/ethtool/fec.c:48
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81e86d28)
Location: net/ethtool/fec.c:48
Inline: True
Inline callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethtool_link_modes_to_fecparam(struct ethtool_fecparam *fec, long unsigned int *link_modes, u8 fec_auto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81ee33b0)
Location: net/ethtool/fec.c:48
Inline: False
Direct callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
**Symbols:**

```
ffffffff81ee33b0-ffffffff81ee343c: ethtool_link_modes_to_fecparam (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethtool_link_modes_to_fecparam(struct ethtool_fecparam *fec, long unsigned int *link_modes, u8 fec_auto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81fa7190)
Location: net/ethtool/fec.c:48
Inline: False
Direct callers:
  - net/ethtool/fec.c:ethnl_set_fec
```
**Symbols:**

```
ffffffff81fa7190-ffffffff81fa721c: ethtool_link_modes_to_fecparam (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
