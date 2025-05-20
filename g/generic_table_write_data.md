# Function: <code>generic_table_write_data</code>

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
int generic_table_write_data(struct opal_dev *dev, const u64 data, u64 offset, u64 size, const u8 *uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81580580)
Location: block/sed-opal.c:1226
Inline: False
Direct callers:
  - block/sed-opal.c:write_table_data
  - block/sed-opal.c:write_shadow_mbr
```
**Symbols:**

```
ffffffff81580580-ffffffff81580815: generic_table_write_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_table_write_data(struct opal_dev *dev, const u64 data, u64 offset, u64 size, const u8 *uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8159d5c0)
Location: block/sed-opal.c:1226
Inline: False
Direct callers:
  - block/sed-opal.c:write_table_data
  - block/sed-opal.c:write_shadow_mbr
```
**Symbols:**

```
ffffffff8159d5c0-ffffffff8159d855: generic_table_write_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_table_write_data(struct opal_dev *dev, const u64 data, u64 offset, u64 size, const u8 *uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a4210)
Location: block/sed-opal.c:1226
Inline: False
Direct callers:
  - block/sed-opal.c:write_table_data
  - block/sed-opal.c:write_shadow_mbr
```
**Symbols:**

```
ffffffff815a4210-ffffffff815a44a2: generic_table_write_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_table_write_data(struct opal_dev *dev, const u64 data, u64 offset, u64 size, const u8 *uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8160cc10)
Location: block/sed-opal.c:1226
Inline: False
Direct callers:
  - block/sed-opal.c:write_table_data
  - block/sed-opal.c:write_shadow_mbr
```
**Symbols:**

```
ffffffff8160cc10-ffffffff8160ce9c: generic_table_write_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_table_write_data(struct opal_dev *dev, const u64 data, u64 offset, u64 size, const u8 *uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816c0cc0)
Location: block/sed-opal.c:1226
Inline: False
Direct callers:
  - block/sed-opal.c:write_table_data
  - block/sed-opal.c:write_shadow_mbr
```
**Symbols:**

```
ffffffff816c0cc0-ffffffff816c0f4f: generic_table_write_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_table_write_data(struct opal_dev *dev, const u64 data, u64 offset, u64 size, const u8 *uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81781e00)
Location: block/sed-opal.c:1266
Inline: False
Direct callers:
  - block/sed-opal.c:write_table_data
  - block/sed-opal.c:write_shadow_mbr
```
**Symbols:**

```
ffffffff81781e00-ffffffff8178208c: generic_table_write_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_table_write_data(struct opal_dev *dev, const u64 data, u64 offset, u64 size, const u8 *uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817c1f30)
Location: block/sed-opal.c:1280
Inline: False
Direct callers:
  - block/sed-opal.c:write_table_data
  - block/sed-opal.c:write_shadow_mbr
```
**Symbols:**

```
ffffffff817c1f30-ffffffff817c21b8: generic_table_write_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_table_write_data(struct opal_dev *dev, const u64 data, u64 offset, u64 size, const u8 *uid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81805ac0)
Location: block/sed-opal.c:1397
Inline: False
Direct callers:
  - block/sed-opal.c:write_table_data
  - block/sed-opal.c:write_shadow_mbr
```
**Symbols:**

```
ffffffff81805ac0-ffffffff81805d27: generic_table_write_data (STB_LOCAL)
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
