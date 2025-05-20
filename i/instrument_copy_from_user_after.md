# Function: <code>instrument_copy_from_user_after</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/instrumented.h:153
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/instrumented.h:153
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/instrumented.h:153
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/instrumented.h:153
Inline: True
```
```
In mm/maccess.c (0)
Location: include/linux/instrumented.h:153
Inline: True
```
```
In mm/memory.c (ffffffff813c07e2)
Location: include/linux/instrumented.h:153
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In lib/iov_iter.c (0)
Location: include/linux/instrumented.h:153
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/instrumented.h:153
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/instrumented.h:153
Inline: True
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/instrumented.h:153
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In mm/maccess.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In mm/memory.c (ffffffff813f54df)
Location: include/linux/instrumented.h:144
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In lib/iov_iter.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In arch/x86/kernel/fpu/signal.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In arch/x86/kernel/tls.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In mm/maccess.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In mm/memory.c (ffffffff81415aaf)
Location: include/linux/instrumented.h:144
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In lib/iov_iter.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In lib/usercopy.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In arch/x86/lib/insn-eval.c (0)
Location: include/linux/instrumented.h:144
Inline: True
```
```
In arch/x86/lib/usercopy.c (0)
Location: include/linux/instrumented.h:144
Inline: True
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
