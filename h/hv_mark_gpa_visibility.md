# Function: <code>hv_mark_gpa_visibility</code>

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
int hv_mark_gpa_visibility(u16 count, const u64 *pfn, enum hv_mem_host_visibility visibility);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/ivm.c (0)
Location: arch/x86/hyperv/ivm.c:279
Inline: False
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility
```
**Symbols:**

```
ffffffff8103f240-ffffffff8103f48d: hv_mark_gpa_visibility (STB_LOCAL)
ffffffff81e47342-ffffffff81e4735c: hv_mark_gpa_visibility.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hv_mark_gpa_visibility(u16 count, const u64 *pfn, enum hv_mem_host_visibility visibility);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81048380)
Location: arch/x86/hyperv/ivm.c:279
Inline: False
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility
```
**Symbols:**

```
ffffffff81048380-ffffffff810485dd: hv_mark_gpa_visibility (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hv_mark_gpa_visibility(u16 count, const u64 *pfn, enum hv_mem_host_visibility visibility);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81048730)
Location: arch/x86/hyperv/ivm.c:247
Inline: False
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_vtom_set_host_visibility
```
**Symbols:**

```
ffffffff81048730-ffffffff81048989: hv_mark_gpa_visibility (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hv_mark_gpa_visibility(u16 count, const u64 *pfn, enum hv_mem_host_visibility visibility);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8104f820)
Location: arch/x86/hyperv/ivm.c:464
Inline: False
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_vtom_set_host_visibility
```
**Symbols:**

```
ffffffff8104f820-ffffffff8104f9e9: hv_mark_gpa_visibility (STB_LOCAL)
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
