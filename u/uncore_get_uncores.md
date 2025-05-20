# Function: <code>uncore_get_uncores</code>

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
struct intel_uncore_type **uncore_get_uncores(enum uncore_access_type type_id, int num_extra, struct intel_uncore_type **extra);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81023450)
Location: arch/x86/events/intel/uncore_snbep.c:5992
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init
```
**Symbols:**

```
ffffffff81023450-ffffffff810235a9: uncore_get_uncores (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct intel_uncore_type **uncore_get_uncores(enum uncore_access_type type_id, int num_extra, struct intel_uncore_type **extra);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81027280)
Location: arch/x86/events/intel/uncore_snbep.c:5992
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init
```
**Symbols:**

```
ffffffff81027280-ffffffff810273e3: uncore_get_uncores (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct intel_uncore_type **uncore_get_uncores(enum uncore_access_type type_id, int num_extra, struct intel_uncore_type **extra);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102cd80)
Location: arch/x86/events/intel/uncore_snbep.c:6367
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init
```
**Symbols:**

```
ffffffff8102cd80-ffffffff8102cf1c: uncore_get_uncores (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct intel_uncore_type **uncore_get_uncores(enum uncore_access_type type_id, int num_extra, struct intel_uncore_type **extra);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102cfc0)
Location: arch/x86/events/intel/uncore_snbep.c:6414
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init
```
**Symbols:**

```
ffffffff8102cfc0-ffffffff8102d16a: uncore_get_uncores (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct intel_uncore_type **uncore_get_uncores(enum uncore_access_type type_id, int num_extra, struct intel_uncore_type **extra, int max_num_types, struct intel_uncore_type **uncores);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810331c0)
Location: arch/x86/events/intel/uncore_snbep.c:6426
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:gnr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:gnr_uncore_pci_init
  - arch/x86/events/intel/uncore_snbep.c:gnr_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_pci_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init
```
**Symbols:**

```
ffffffff810331c0-ffffffff8103333d: uncore_get_uncores (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int max_num_types</code>
</li>
<li>
<b>Param added. </b>
<code>struct intel_uncore_type **uncores</code>
</li>
</ul>
</details>
</li>
</ul>
