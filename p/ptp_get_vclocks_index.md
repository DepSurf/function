# Function: <code>ptp_get_vclocks_index</code>

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
int ptp_get_vclocks_index(int pclock_index, int **vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff819db1c0)
Location: drivers/ptp/ptp_vclock.c:153
Inline: False
Direct callers:
  - net/ethtool/common.c:ethtool_get_phc_vclocks
```
**Symbols:**

```
ffffffff819db1c0-ffffffff819db2e3: ptp_get_vclocks_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptp_get_vclocks_index(int pclock_index, int **vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81b3eae0)
Location: drivers/ptp/ptp_vclock.c:233
Inline: False
Direct callers:
  - net/ethtool/common.c:ethtool_get_phc_vclocks
```
**Symbols:**

```
ffffffff81b3eae0-ffffffff81b3ec14: ptp_get_vclocks_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ptp_get_vclocks_index(int pclock_index, int **vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81cd4e60)
Location: drivers/ptp/ptp_vclock.c:233
Inline: False
Direct callers:
  - net/ethtool/common.c:ethtool_get_phc_vclocks
```
**Symbols:**

```
ffffffff81cd4e60-ffffffff81cd4f94: ptp_get_vclocks_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ptp_get_vclocks_index(int pclock_index, int **vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81d3cac0)
Location: drivers/ptp/ptp_vclock.c:233
Inline: False
Direct callers:
  - net/ethtool/common.c:ethtool_get_phc_vclocks
```
**Symbols:**

```
ffffffff81d3cac0-ffffffff81d3cc14: ptp_get_vclocks_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ptp_get_vclocks_index(int pclock_index, int **vclock_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_vclock.c (ffffffff81df3400)
Location: drivers/ptp/ptp_vclock.c:233
Inline: False
Direct callers:
  - net/ethtool/common.c:ethtool_get_phc_vclocks
```
**Symbols:**

```
ffffffff81df3400-ffffffff81df3554: ptp_get_vclocks_index (STB_GLOBAL)
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
