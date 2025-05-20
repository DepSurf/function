# Function: <code>__uncore_imc_init_box</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __uncore_imc_init_box(struct intel_uncore_box *box, unsigned int base_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (0)
Location: arch/x86/events/intel/uncore_snb.c:1323
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
```
**Symbols:**

```
ffffffff810238c0-ffffffff810239e2: __uncore_imc_init_box (STB_LOCAL)
ffffffff81e45f88-ffffffff81e45fad: __uncore_imc_init_box.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __uncore_imc_init_box(struct intel_uncore_box *box, unsigned int base_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff810286b0)
Location: arch/x86/events/intel/uncore_snb.c:1484
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
```
**Symbols:**

```
ffffffff810286b0-ffffffff810287fa: __uncore_imc_init_box (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __uncore_imc_init_box(struct intel_uncore_box *box, unsigned int base_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff810286e0)
Location: arch/x86/events/intel/uncore_snb.c:1484
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
```
**Symbols:**

```
ffffffff810286e0-ffffffff81028828: __uncore_imc_init_box (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __uncore_imc_init_box(struct intel_uncore_box *box, unsigned int base_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102e840)
Location: arch/x86/events/intel/uncore_snb.c:1484
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_imc_freerunning_init_box
  - arch/x86/events/intel/uncore_snb.c:adl_uncore_imc_init_box
  - arch/x86/events/intel/uncore_snb.c:tgl_uncore_imc_freerunning_init_box
```
**Symbols:**

```
ffffffff8102e840-ffffffff8102e988: __uncore_imc_init_box (STB_LOCAL)
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
