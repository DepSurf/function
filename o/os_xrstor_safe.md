# Function: <code>os_xrstor_safe</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff8104aa31)
Location: arch/x86/include/asm/fpu/internal.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int os_xrstor_safe(struct fpstate *fpstate, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff81054910)
Location: arch/x86/kernel/fpu/xstate.h:307
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff81054910-ffffffff810549be: os_xrstor_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int os_xrstor_safe(struct fpstate *fpstate, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff81062330)
Location: arch/x86/kernel/fpu/xstate.h:307
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff81062330-ffffffff810623de: os_xrstor_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int os_xrstor_safe(struct fpstate *fpstate, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff81063e00)
Location: arch/x86/kernel/fpu/xstate.h:307
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff81063e00-ffffffff81063eae: os_xrstor_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int os_xrstor_safe(struct fpstate *fpstate, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff8106b310)
Location: arch/x86/kernel/fpu/xstate.h:308
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff8106b310-ffffffff8106b3be: os_xrstor_safe (STB_LOCAL)
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
