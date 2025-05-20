# Function: <code>ve_instr_len</code>

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
int ve_instr_len(struct ve_info *ve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:157
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:handle_io
  - arch/x86/coco/tdx/tdx.c:handle_cpuid
  - arch/x86/coco/tdx/tdx.c:handle_cpuid
```
**Symbols:**

```
ffffffff81002c10-ffffffff81002cc1: ve_instr_len (STB_LOCAL)
ffffffff81e43d66-ffffffff81e43d8f: ve_instr_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ve_instr_len(struct ve_info *ve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:199
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:handle_io
  - arch/x86/coco/tdx/tdx.c:handle_cpuid
  - arch/x86/coco/tdx/tdx.c:handle_cpuid
```
**Symbols:**

```
ffffffff81003660-ffffffff81003711: ve_instr_len (STB_LOCAL)
ffffffff820500b7-ffffffff820500e0: ve_instr_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ve_instr_len(struct ve_info *ve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:205
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:handle_io
  - arch/x86/coco/tdx/tdx.c:handle_cpuid
  - arch/x86/coco/tdx/tdx.c:handle_cpuid
```
**Symbols:**

```
ffffffff81002dd0-ffffffff81002e83: ve_instr_len (STB_LOCAL)
ffffffff820ce561-ffffffff820ce58a: ve_instr_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ve_instr_len(struct ve_info *ve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:229
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:handle_io
  - arch/x86/coco/tdx/tdx.c:handle_cpuid
  - arch/x86/coco/tdx/tdx.c:handle_cpuid
  - arch/x86/coco/tdx/tdx.c:write_msr
  - arch/x86/coco/tdx/tdx.c:read_msr
```
**Symbols:**

```
ffffffff81003180-ffffffff81003233: ve_instr_len (STB_LOCAL)
ffffffff821a8d96-ffffffff821a8dbf: ve_instr_len.cold (STB_LOCAL)
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
