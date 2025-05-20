# Function: <code>erst_read_record</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t erst_read_record(u64 record_id, struct cper_record_header *record, size_t buflen, size_t recordlen, const guid_t *creatorid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff8189dd2f)
Location: drivers/acpi/apei/erst.c:876
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
**Symbols:**

```
ffffffff8189d350-ffffffff8189d3eb: erst_read_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t erst_read_record(u64 record_id, struct cper_record_header *record, size_t buflen, size_t recordlen, const guid_t *creatorid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff819e6c99)
Location: drivers/acpi/apei/erst.c:876
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
**Symbols:**

```
ffffffff819e6a90-ffffffff819e6bc1: erst_read_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t erst_read_record(u64 record_id, struct cper_record_header *record, size_t buflen, size_t recordlen, const guid_t *creatorid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81a2f34a)
Location: drivers/acpi/apei/erst.c:876
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
**Symbols:**

```
ffffffff81a2f130-ffffffff81a2f26e: erst_read_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t erst_read_record(u64 record_id, struct cper_record_header *record, size_t buflen, size_t recordlen, const guid_t *creatorid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81a7a68a)
Location: drivers/acpi/apei/erst.c:909
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_reader
Direct callers:
  - arch/x86/kernel/cpu/mce/apei.c:apei_read_mce
```
**Symbols:**

```
ffffffff81a7a470-ffffffff81a7a5ae: erst_read_record (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
