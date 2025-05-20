# Function: <code>tdx_kvm_hypercall</code>

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
long int tdx_kvm_hypercall(unsigned int nr, long unsigned int p1, long unsigned int p2, long unsigned int p3, long unsigned int p4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81002b20)
Location: arch/x86/coco/tdx/tdx.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_kick_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff81002b20-ffffffff81002b8a: tdx_kvm_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int tdx_kvm_hypercall(unsigned int nr, long unsigned int p1, long unsigned int p2, long unsigned int p3, long unsigned int p4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff810034a0)
Location: arch/x86/coco/tdx/tdx.c:84
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_kick_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff810034a0-ffffffff8100350a: tdx_kvm_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int tdx_kvm_hypercall(unsigned int nr, long unsigned int p1, long unsigned int p2, long unsigned int p3, long unsigned int p4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81002bf0)
Location: arch/x86/coco/tdx/tdx.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_kick_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff81002bf0-ffffffff81002c6f: tdx_kvm_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int tdx_kvm_hypercall(unsigned int nr, long unsigned int p1, long unsigned int p2, long unsigned int p3, long unsigned int p4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81002d80)
Location: arch/x86/coco/tdx/tdx.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_kick_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
**Symbols:**

```
ffffffff81002d80-ffffffff81002dff: tdx_kvm_hypercall (STB_GLOBAL)
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
