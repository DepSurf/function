# Function: <code>generic_get_table_info</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81500191)
Location: block/sed-opal.c:1141
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151e0e1)
Location: block/sed-opal.c:1142
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81580268)
Location: block/sed-opal.c:1144
Inline: True
Inline callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8159d2c7)
Location: block/sed-opal.c:1144
Inline: True
Inline callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a3f1d)
Location: block/sed-opal.c:1144
Inline: True
Inline callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
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
In block/sed-opal.c (ffffffff8160c92d)
Location: block/sed-opal.c:1144
Inline: True
Inline callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff816c0950)
Location: block/sed-opal.c:1144
Inline: True
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
```
**Symbols:**

```
ffffffff816c0950-ffffffff816c09a6: generic_get_table_info.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81781a70)
Location: block/sed-opal.c:1184
Inline: True
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
```
**Symbols:**

```
ffffffff81781a70-ffffffff81781ac6: generic_get_table_info.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff817c1ba0)
Location: block/sed-opal.c:1198
Inline: True
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
```
**Symbols:**

```
ffffffff817c1ba0-ffffffff817c1bfd: generic_get_table_info.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff818051e0)
Location: block/sed-opal.c:1315
Inline: True
Direct callers:
  - block/sed-opal.c:read_table_data
  - block/sed-opal.c:generic_table_write_data
```
**Symbols:**

```
ffffffff818051e0-ffffffff8180523d: generic_get_table_info.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (0)
Location: block/sed-opal.c:1142
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07ce8f0)
Location: block/sed-opal.c:1142
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c8054)
Location: block/sed-opal.c:1142
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe000458802)
Location: block/sed-opal.c:1142
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815166c1)
Location: block/sed-opal.c:1142
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815069d1)
Location: block/sed-opal.c:1142
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81512751)
Location: block/sed-opal.c:1142
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152bf11)
Location: block/sed-opal.c:1142
Inline: True
Inline callers:
  - block/sed-opal.c:write_shadow_mbr
```
</details>
</li>
</ul>

## Differences
