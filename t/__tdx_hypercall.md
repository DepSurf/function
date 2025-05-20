# Function: <code>__tdx_hypercall</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void __tdx_hypercall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdcall.S (ffffffff81003b40)
Location: arch/x86/coco/tdx/tdcall.S
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:handle_io
  - arch/x86/coco/tdx/tdx.c:handle_io
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/coco/tdx/tdx.c:handle_cpuid
  - arch/x86/coco/tdx/tdx.c:tdx_safe_halt
  - arch/x86/coco/tdx/tdx.c:tdx_kvm_hypercall
```
**Symbols:**

```
ffffffff81003b40-ffffffff81003bbb: __tdx_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __tdx_hypercall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdcall.S (ffffffff810043d0)
Location: arch/x86/coco/tdx/tdcall.S
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:handle_io
  - arch/x86/coco/tdx/tdx.c:handle_io
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/coco/tdx/tdx.c:handle_cpuid
  - arch/x86/coco/tdx/tdx.c:tdx_safe_halt
  - arch/x86/coco/tdx/tdx.c:tdx_kvm_hypercall
```
**Symbols:**

```
ffffffff810043d0-ffffffff8100444b: __tdx_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __tdx_hypercall();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdcall.S (ffffffff821396d0)
Location: arch/x86/coco/tdx/tdcall.S
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:handle_io
  - arch/x86/coco/tdx/tdx.c:__halt
  - arch/x86/coco/tdx/tdx.c:tdx_kvm_hypercall
```
**Symbols:**

```
ffffffff821396d0-ffffffff8213974c: __tdx_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 __tdx_hypercall(struct tdx_module_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx-shared.c (ffffffff8221b410)
Location: arch/x86/coco/tdx/tdx-shared.c:73
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_map_gpa
  - arch/x86/coco/tdx/tdx.c:handle_in
  - arch/x86/coco/tdx/tdx.c:mmio_read
  - arch/x86/coco/tdx/tdx.c:handle_cpuid
  - arch/x86/coco/tdx/tdx.c:write_msr
  - arch/x86/coco/tdx/tdx.c:read_msr
  - arch/x86/coco/tdx/tdx.c:__halt
  - arch/x86/coco/tdx/tdx.c:tdx_kvm_hypercall
  - arch/x86/coco/tdx/tdx.c:_tdx_hypercall
  - arch/x86/hyperv/ivm.c:hv_tdx_hypercall
  - arch/x86/hyperv/ivm.c:hv_tdx_msr_read
  - arch/x86/hyperv/ivm.c:hv_tdx_msr_write
```
**Symbols:**

```
ffffffff8221b410-ffffffff8221b445: __tdx_hypercall (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tdx_module_args *args</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
</li>
</ul>
