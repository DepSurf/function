# Function: <code>intel_uncore_generic_init_uncores</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
struct intel_uncore_type **intel_uncore_generic_init_uncores(enum uncore_access_type type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81021a40)
Location: arch/x86/events/intel/uncore_discovery.c:572
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_mmio_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_pci_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_cpu_init
```
**Symbols:**

```
ffffffff81021a40-ffffffff81021c4a: intel_uncore_generic_init_uncores (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct intel_uncore_type **intel_uncore_generic_init_uncores(enum uncore_access_type type_id, int num_extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81025f50)
Location: arch/x86/events/intel/uncore_discovery.c:572
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_get_uncores
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_mmio_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_pci_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_cpu_init
```
**Symbols:**

```
ffffffff81025f50-ffffffff8102617f: intel_uncore_generic_init_uncores (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct intel_uncore_type **intel_uncore_generic_init_uncores(enum uncore_access_type type_id, int num_extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81029fb0)
Location: arch/x86/events/intel/uncore_discovery.c:580
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_get_uncores
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_mmio_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_pci_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_cpu_init
```
**Symbols:**

```
ffffffff81029fb0-ffffffff8102a1cb: intel_uncore_generic_init_uncores (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct intel_uncore_type **intel_uncore_generic_init_uncores(enum uncore_access_type type_id, int num_extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030ac0)
Location: arch/x86/events/intel/uncore_discovery.c:580
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_get_uncores
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_mmio_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_pci_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_cpu_init
```
**Symbols:**

```
ffffffff81030ac0-ffffffff81030cdb: intel_uncore_generic_init_uncores (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct intel_uncore_type **intel_uncore_generic_init_uncores(enum uncore_access_type type_id, int num_extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030ac0)
Location: arch/x86/events/intel/uncore_discovery.c:600
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_get_uncores
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_mmio_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_pci_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_cpu_init
```
**Symbols:**

```
ffffffff81030ac0-ffffffff81030ce3: intel_uncore_generic_init_uncores (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct intel_uncore_type **intel_uncore_generic_init_uncores(enum uncore_access_type type_id, int num_extra);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81036d90)
Location: arch/x86/events/intel/uncore_discovery.c:601
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:uncore_get_uncores
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_mmio_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_pci_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_uncore_cpu_init
```
**Symbols:**

```
ffffffff81036d90-ffffffff81036fe8: intel_uncore_generic_init_uncores (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int num_extra</code>
</li>
</ul>
</details>
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
