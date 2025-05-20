# Function: <code>membuf_write</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8104254a)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043c12)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_part
  - arch/x86/kernel/fpu/xstate.c:copy_part
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104457c)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8104658a)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81043f2a)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810452cd)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
```
```
In arch/x86/kernel/ptrace.c (ffffffff810461cf)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81047fa0)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8104a2c4)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104bdd7)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
```
```
In arch/x86/kernel/ptrace.c (ffffffff8104c8af)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8104e8b0)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81054428)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8105686e)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
```
```
In arch/x86/kernel/ptrace.c (ffffffff8105796f)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff81059a5e)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int membuf_write(struct membuf *s, const void *v, size_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81061760)
Location: include/linux/regset.h:37
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063220)
Location: include/linux/regset.h:37
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106514f)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff810673fe)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
**Symbols:**

```
ffffffff81061760-ffffffff81061802: membuf_write (STB_LOCAL)
ffffffff81063220-ffffffff8106326a: membuf_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int membuf_write(struct membuf *s, const void *v, size_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81063030)
Location: include/linux/regset.h:37
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064b70)
Location: include/linux/regset.h:37
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106699f)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff810685b0)
Location: include/linux/regset.h:37
Inline: True
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
**Symbols:**

```
ffffffff81063030-ffffffff810630d2: membuf_write (STB_LOCAL)
ffffffff81064b70-ffffffff81064bba: membuf_write.isra.0 (STB_LOCAL)
ffffffff810685b0-ffffffff81068662: membuf_write.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int membuf_write(struct membuf *s, const void *v, size_t size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8106a320)
Location: include/linux/regset.h:37
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:ssp_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106c000)
Location: include/linux/regset.h:37
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
```
```
In arch/x86/kernel/ptrace.c (ffffffff8106de1f)
Location: include/linux/regset.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:ioperm_get
```
```
In arch/x86/kernel/tls.c (ffffffff8106fa30)
Location: include/linux/regset.h:37
Inline: True
Direct callers:
  - arch/x86/kernel/tls.c:regset_tls_get
```
**Symbols:**

```
ffffffff8106a320-ffffffff8106a3c2: membuf_write (STB_LOCAL)
ffffffff8106c000-ffffffff8106c04a: membuf_write.isra.0 (STB_LOCAL)
ffffffff8106fa30-ffffffff8106fae2: membuf_write.constprop.0.isra.0 (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
