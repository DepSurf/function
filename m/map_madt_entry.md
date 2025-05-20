# Function: <code>map_madt_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81482899)
Location: drivers/acpi/processor_core.c:111
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_phys_id
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff814d126f)
Location: drivers/acpi/processor_core.c:111
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff814d126f-ffffffff814d1322: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id, bool ignore_disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff814f3361)
Location: drivers/acpi/processor_core.c:114
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:__acpi_get_phys_id
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff814f3361-ffffffff814f3425: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81501160)
Location: drivers/acpi/processor_core.c:111
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff81501160-ffffffff81501221: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81543590)
Location: drivers/acpi/processor_core.c:111
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff81543590-ffffffff81543651: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81579500)
Location: drivers/acpi/processor_core.c:111
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff81579500-ffffffff815795bb: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81591180)
Location: drivers/acpi/processor_core.c:111
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff81591180-ffffffff8159123b: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815c1fe0)
Location: drivers/acpi/processor_core.c:112
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff815c1fe0-ffffffff815c209e: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815e32c0)
Location: drivers/acpi/processor_core.c:112
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff815e32c0-ffffffff815e337e: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff8168e850)
Location: drivers/acpi/processor_core.c:112
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff8168e850-ffffffff8168e910: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff816ac520)
Location: drivers/acpi/processor_core.c:109
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff816ac520-ffffffff816ac5e0: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff8168eaa0)
Location: drivers/acpi/processor_core.c:109
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff8168eaa0-ffffffff8168eb5a: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff817044b0)
Location: drivers/acpi/processor_core.c:109
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff817044b0-ffffffff8170456a: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81832560)
Location: drivers/acpi/processor_core.c:109
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff81832560-ffffffff8183265a: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81965df0)
Location: drivers/acpi/processor_core.c:109
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff81965df0-ffffffff81965eea: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff819ac350)
Location: drivers/acpi/processor_core.c:135
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff819ac350-ffffffff819ac47a: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff819f6710)
Location: drivers/acpi/processor_core.c:159
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff819f6710-ffffffff819f6872: map_madt_entry (STB_LOCAL)
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
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffff80001076f918)
Location: drivers/acpi/processor_core.c:112
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffff80001076f918-ffff80001076fa74: map_madt_entry (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815d5200)
Location: drivers/acpi/processor_core.c:112
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff815d5200-ffffffff815d52be: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815bedc0)
Location: drivers/acpi/processor_core.c:112
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff815bedc0-ffffffff815bee7e: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815d75a0)
Location: drivers/acpi/processor_core.c:112
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff815d75a0-ffffffff815d765e: map_madt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
phys_cpuid_t map_madt_entry(struct acpi_table_madt *madt, int type, u32 acpi_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815f1460)
Location: drivers/acpi/processor_core.c:112
Inline: False
Direct callers:
  - drivers/acpi/processor_core.c:acpi_map_madt_entry
```
**Symbols:**

```
ffffffff815f1460-ffffffff815f151e: map_madt_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool ignore_disabled</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool ignore_disabled</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
