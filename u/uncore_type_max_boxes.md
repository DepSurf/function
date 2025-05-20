# Function: <code>uncore_type_max_boxes</code>

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
int uncore_type_max_boxes(struct intel_uncore_type **types, int type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81021540)
Location: arch/x86/events/intel/uncore_snbep.c:6024
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init
```
**Symbols:**

```
ffffffff81021540-ffffffff810215a2: uncore_type_max_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uncore_type_max_boxes(struct intel_uncore_type **types, int type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024e40)
Location: arch/x86/events/intel/uncore_snbep.c:6024
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init
```
**Symbols:**

```
ffffffff81024e40-ffffffff81024ebb: uncore_type_max_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uncore_type_max_boxes(struct intel_uncore_type **types, int type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102a250)
Location: arch/x86/events/intel/uncore_snbep.c:6399
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init
```
**Symbols:**

```
ffffffff8102a250-ffffffff8102a2cb: uncore_type_max_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uncore_type_max_boxes(struct intel_uncore_type **types, int type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102a280)
Location: arch/x86/events/intel/uncore_snbep.c:6446
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init
```
**Symbols:**

```
ffffffff8102a280-ffffffff8102a2fb: uncore_type_max_boxes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uncore_type_max_boxes(struct intel_uncore_type **types, int type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810303e0)
Location: arch/x86/events/intel/uncore_snbep.c:6459
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:gnr_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_mmio_init
  - arch/x86/events/intel/uncore_snbep.c:spr_uncore_cpu_init
```
**Symbols:**

```
ffffffff810303e0-ffffffff8103045b: uncore_type_max_boxes (STB_LOCAL)
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
