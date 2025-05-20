# Function: <code>tdx_handle_virt_exception</code>

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
bool tdx_handle_virt_exception(struct pt_regs *regs, struct ve_info *ve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:616
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
```
**Symbols:**

```
ffffffff81e43e0b-ffffffff81e43e2d: tdx_handle_virt_exception.cold (STB_LOCAL)
ffffffff81003930-ffffffff81003aef: tdx_handle_virt_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tdx_handle_virt_exception(struct pt_regs *regs, struct ve_info *ve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff810041a0)
Location: arch/x86/coco/tdx/tdx.c:658
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
```
**Symbols:**

```
ffffffff810041a0-ffffffff8100435b: tdx_handle_virt_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tdx_handle_virt_exception(struct pt_regs *regs, struct ve_info *ve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81003930)
Location: arch/x86/coco/tdx/tdx.c:659
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
```
**Symbols:**

```
ffffffff81003930-ffffffff81003af6: tdx_handle_virt_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tdx_handle_virt_exception(struct pt_regs *regs, struct ve_info *ve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81003cd0)
Location: arch/x86/coco/tdx/tdx.c:684
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_virtualization_exception
```
**Symbols:**

```
ffffffff81003cd0-ffffffff81003ddc: tdx_handle_virt_exception (STB_GLOBAL)
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
