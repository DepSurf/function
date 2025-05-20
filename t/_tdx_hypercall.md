# Function: <code>_tdx_hypercall</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff8100371b)
Location: arch/x86/coco/tdx/tdx.c:50
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:handle_io
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/coco/tdx/tdx.c:handle_mmio
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
In arch/x86/coco/tdx/tdx.c (ffffffff81003f2b)
Location: arch/x86/coco/tdx/tdx.c:52
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:handle_io
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/coco/tdx/tdx.c:handle_mmio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 _tdx_hypercall(u64 fn, u64 r12, u64 r13, u64 r14, u64 r15);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81003572)
Location: arch/x86/include/asm/shared/tdx.h:58
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:handle_io
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
```
**Symbols:**

```
ffffffff81002b60-ffffffff81002bd7: _tdx_hypercall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 _tdx_hypercall(u64 fn, u64 r12, u64 r13, u64 r14, u64 r15);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81002e10)
Location: arch/x86/include/asm/shared/tdx.h:104
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_io
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/coco/tdx/tdx.c:tdx_hcall_get_quote
```
**Symbols:**

```
ffffffff81002e10-ffffffff81002e87: _tdx_hypercall (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
