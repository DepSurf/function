# Function: <code>copy_to_kernel_nofault</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int copy_to_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812581c0)
Location: mm/maccess.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:write_mem_msg
```
**Symbols:**

```
ffffffff812581c0-ffffffff81258251: copy_to_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int copy_to_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812629f0)
Location: mm/maccess.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:write_mem_msg
```
**Symbols:**

```
ffffffff812629f0-ffffffff81262a81: copy_to_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int copy_to_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81267410)
Location: mm/maccess.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:write_mem_msg
```
**Symbols:**

```
ffffffff81267410-ffffffff812674a1: copy_to_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int copy_to_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812a3e50)
Location: mm/maccess.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:write_mem_msg
```
**Symbols:**

```
ffffffff812a3e50-ffffffff812a3ee1: copy_to_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int copy_to_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812fbeb0)
Location: mm/maccess.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:write_mem_msg
```
**Symbols:**

```
ffffffff812fbeb0-ffffffff812fbf55: copy_to_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int copy_to_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff813660d0)
Location: mm/maccess.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:write_mem_msg
```
**Symbols:**

```
ffffffff813660d0-ffffffff81366175: copy_to_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int copy_to_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81398570)
Location: mm/maccess.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:write_mem_msg
```
**Symbols:**

```
ffffffff81398570-ffffffff81398615: copy_to_kernel_nofault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int copy_to_kernel_nofault(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff813c2370)
Location: mm/maccess.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_arch_remove_breakpoint
  - arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint
  - kernel/debug/debug_core.c:kgdb_arch_remove_breakpoint
  - kernel/debug/gdbstub.c:gdb_serial_stub
  - kernel/debug/gdbstub.c:write_mem_msg
```
**Symbols:**

```
ffffffff813c2370-ffffffff813c2415: copy_to_kernel_nofault (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
