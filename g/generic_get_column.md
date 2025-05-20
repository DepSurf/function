# Function: <code>generic_get_column</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814ff390)
Location: block/sed-opal.c:1109
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff814ff390-ffffffff814ff49f: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151d2e0)
Location: block/sed-opal.c:1110
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff8151d2e0-ffffffff8151d3ef: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81580000)
Location: block/sed-opal.c:1112
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff81580000-ffffffff8158010b: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8159d040)
Location: block/sed-opal.c:1112
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff8159d040-ffffffff8159d14b: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a3b60)
Location: block/sed-opal.c:1112
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff815a3b60-ffffffff815a3c6f: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8160c570)
Location: block/sed-opal.c:1112
Inline: False
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff8160c570-ffffffff8160c67f: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816c05d0)
Location: block/sed-opal.c:1112
Inline: False
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff816c05d0-ffffffff816c06e7: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817816b0)
Location: block/sed-opal.c:1152
Inline: False
Direct callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff817816b0-ffffffff817817c7: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817c1715)
Location: block/sed-opal.c:1187
Inline: True
Inline callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_active_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81804d55)
Location: block/sed-opal.c:1304
Inline: True
Inline callers:
  - block/sed-opal.c:get_msid_cpin_pin
  - block/sed-opal.c:get_active_key
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff800010625f28)
Location: block/sed-opal.c:1110
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffff800010625f28-ffff80001062605c: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07cd998)
Location: block/sed-opal.c:1110
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
c07cd998-c07cdacc: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c6ec0)
Location: block/sed-opal.c:1110
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
c0000000007c6ec0-c0000000007c6ffc: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe000457420)
Location: block/sed-opal.c:1110
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffe000457420-ffffffe00045752a: generic_get_column (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815158c0)
Location: block/sed-opal.c:1110
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff815158c0-ffffffff815159cf: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81505bd0)
Location: block/sed-opal.c:1110
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff81505bd0-ffffffff81505cdf: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81511950)
Location: block/sed-opal.c:1110
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff81511950-ffffffff81511a5f: generic_get_column (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int generic_get_column(struct opal_dev *dev, const u8 *table, u64 column);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152b110)
Location: block/sed-opal.c:1110
Inline: False
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:get_active_key
```
**Symbols:**

```
ffffffff8152b110-ffffffff8152b21f: generic_get_column (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
