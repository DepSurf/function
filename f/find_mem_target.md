# Function: <code>find_mem_target</code>

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
struct memory_target *find_mem_target(unsigned int mem_pxm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff828f39b6)
Location: drivers/acpi/hmat/hmat.c:66
Inline: False
Direct callers:
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff828f39b6-ffffffff828f39dc: find_mem_target (STB_LOCAL)
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
In drivers/acpi/hmat/hmat.c (ffffffff8163b0dc)
Location: drivers/acpi/hmat/hmat.c:78
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_callback
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
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
In drivers/acpi/numa/hmat.c (ffffffff816e80cc)
Location: drivers/acpi/numa/hmat.c:85
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_callback
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
  - drivers/acpi/numa/hmat.c:alloc_memory_target
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
In drivers/acpi/numa/hmat.c (ffffffff81705aec)
Location: drivers/acpi/numa/hmat.c:93
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_callback
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
  - drivers/acpi/numa/hmat.c:alloc_memory_target
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
In drivers/acpi/numa/hmat.c (ffffffff816e716c)
Location: drivers/acpi/numa/hmat.c:93
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_callback
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/numa/hmat.c:hmat_parse_subtable
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
In drivers/acpi/numa/hmat.c (ffffffff8176077c)
Location: drivers/acpi/numa/hmat.c:93
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_callback
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
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
In drivers/acpi/numa/hmat.c (ffffffff818941ac)
Location: drivers/acpi/numa/hmat.c:93
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_callback
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
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
In drivers/acpi/numa/hmat.c (ffffffff819dbccc)
Location: drivers/acpi/numa/hmat.c:92
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_callback
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
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
In drivers/acpi/numa/hmat.c (ffffffff81a2398c)
Location: drivers/acpi/numa/hmat.c:92
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_callback
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
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
In drivers/acpi/numa/hmat.c (ffffffff8393f692)
Location: drivers/acpi/numa/hmat.c:101
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:hmat_calculate_adistance
  - drivers/acpi/numa/hmat.c:hmat_callback
  - drivers/acpi/numa/hmat.c:alloc_target
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
In drivers/acpi/hmat/hmat.c (ffff8000107a640c)
Location: drivers/acpi/hmat/hmat.c:78
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_callback
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff8160843c)
Location: drivers/acpi/hmat/hmat.c:78
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_callback
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
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
In drivers/acpi/hmat/hmat.c (ffffffff815fa58c)
Location: drivers/acpi/hmat/hmat.c:78
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_callback
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/hmat/hmat.c (ffffffff8164925c)
Location: drivers/acpi/hmat/hmat.c:78
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:hmat_callback
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
