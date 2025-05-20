# Function: <code>ethtool_fec_to_link_modes</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ethtool_fec_to_link_modes(u32 fec, long unsigned int *link_modes, u8 *fec_auto);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81a81785)
Location: net/ethtool/fec.c:32
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
Direct callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
```
**Symbols:**

```
ffffffff81a81350-ffffffff81a813a4: ethtool_fec_to_link_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ethtool_fec_to_link_modes(u32 fec, long unsigned int *link_modes, u8 *fec_auto);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81b3b4cc)
Location: net/ethtool/fec.c:32
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
Direct callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
```
**Symbols:**

```
ffffffff81b3b0a0-ffffffff81b3b0f4: ethtool_fec_to_link_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ethtool_fec_to_link_modes(u32 fec, long unsigned int *link_modes, u8 *fec_auto);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81cc74bf)
Location: net/ethtool/fec.c:32
Inline: True
Inline callers:
  - net/ethtool/fec.c:fec_prepare_data
Direct callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
```
**Symbols:**

```
ffffffff81cc7040-ffffffff81cc70a0: ethtool_fec_to_link_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ethtool_fec_to_link_modes(u32 fec, long unsigned int *link_modes, u8 *fec_auto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81e86710)
Location: net/ethtool/fec.c:32
Inline: False
Direct callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
```
**Symbols:**

```
ffffffff81e86710-ffffffff81e86770: ethtool_fec_to_link_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ethtool_fec_to_link_modes(u32 fec, long unsigned int *link_modes, u8 *fec_auto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81ee30f0)
Location: net/ethtool/fec.c:32
Inline: False
Direct callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
```
**Symbols:**

```
ffffffff81ee30f0-ffffffff81ee3150: ethtool_fec_to_link_modes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ethtool_fec_to_link_modes(u32 fec, long unsigned int *link_modes, u8 *fec_auto);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81fa6ed0)
Location: net/ethtool/fec.c:32
Inline: False
Direct callers:
  - net/ethtool/fec.c:ethnl_set_fec
  - net/ethtool/fec.c:fec_prepare_data
  - net/ethtool/fec.c:fec_prepare_data
```
**Symbols:**

```
ffffffff81fa6ed0-ffffffff81fa6f30: ethtool_fec_to_link_modes (STB_LOCAL)
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
