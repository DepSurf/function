# Function: <code>alloc_memory_target</code>

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
In drivers/acpi/hmat/hmat.c (ffffffff828f3aba)
Location: drivers/acpi/hmat/hmat.c:95
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
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
In drivers/acpi/hmat/hmat.c (ffffffff828fcc07)
Location: drivers/acpi/hmat/hmat.c:107
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void alloc_memory_target(unsigned int mem_pxm, resource_size_t start, resource_size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff82d13dab)
Location: drivers/acpi/numa/hmat.c:114
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
```
**Symbols:**

```
ffffffff82d13dab-ffffffff82d13e9a: alloc_memory_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void alloc_memory_target(unsigned int mem_pxm, resource_size_t start, resource_size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/hmat.c (ffffffff830019a4)
Location: drivers/acpi/numa/hmat.c:123
Inline: False
Direct callers:
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
```
**Symbols:**

```
ffffffff830019a4-ffffffff83001a96: alloc_memory_target (STB_LOCAL)
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
In drivers/acpi/numa/hmat.c (ffffffff8320c885)
Location: drivers/acpi/numa/hmat.c:123
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
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
In drivers/acpi/numa/hmat.c (ffffffff832f503e)
Location: drivers/acpi/numa/hmat.c:123
Inline: True
Inline callers:
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
In drivers/acpi/numa/hmat.c (ffffffff834ad995)
Location: drivers/acpi/numa/hmat.c:123
Inline: True
Inline callers:
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
In drivers/acpi/numa/hmat.c (ffffffff83ee6405)
Location: drivers/acpi/numa/hmat.c:122
Inline: True
Inline callers:
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
In drivers/acpi/numa/hmat.c (ffffffff8370bdd5)
Location: drivers/acpi/numa/hmat.c:122
Inline: True
Inline callers:
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
In drivers/acpi/numa/hmat.c (ffffffff8393f1fb)
Location: drivers/acpi/numa/hmat.c:196
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:srat_parse_mem_affinity
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
In drivers/acpi/hmat/hmat.c (ffff80001147f868)
Location: drivers/acpi/hmat/hmat.c:107
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
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
In drivers/acpi/hmat/hmat.c (ffffffff828e504a)
Location: drivers/acpi/hmat/hmat.c:107
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
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
In drivers/acpi/hmat/hmat.c (ffffffff828dd24e)
Location: drivers/acpi/hmat/hmat.c:107
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
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
In drivers/acpi/hmat/hmat.c (ffffffff828fdc5b)
Location: drivers/acpi/hmat/hmat.c:107
Inline: True
Inline callers:
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
