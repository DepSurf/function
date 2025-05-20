# Function: <code>__traceiter_x86_fpu_before_restore</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_x86_fpu_before_restore(void *__data, struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041170)
Location: arch/x86/include/asm/trace/fpu.h:47
Inline: False
```
**Symbols:**

```
ffffffff81041170-ffffffff810411ad: __traceiter_x86_fpu_before_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_x86_fpu_before_restore(void *__data, struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81042b70)
Location: arch/x86/include/asm/trace/fpu.h:47
Inline: False
```
**Symbols:**

```
ffffffff81042b70-ffffffff81042bab: __traceiter_x86_fpu_before_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_x86_fpu_before_restore(void *__data, struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81048ee0)
Location: arch/x86/include/asm/trace/fpu.h:47
Inline: False
```
**Symbols:**

```
ffffffff81048ee0-ffffffff81048f1b: __traceiter_x86_fpu_before_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_x86_fpu_before_restore(void *__data, struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810522d0)
Location: arch/x86/include/asm/trace/fpu.h:47
Inline: False
```
**Symbols:**

```
ffffffff810522d0-ffffffff81052313: __traceiter_x86_fpu_before_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_x86_fpu_before_restore(void *__data, struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8105fb00)
Location: arch/x86/include/asm/trace/fpu.h:47
Inline: False
```
**Symbols:**

```
ffffffff8105fb00-ffffffff8105fb43: __traceiter_x86_fpu_before_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_x86_fpu_before_restore(void *__data, struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81061270)
Location: arch/x86/include/asm/trace/fpu.h:47
Inline: False
```
**Symbols:**

```
ffffffff81061270-ffffffff810612b3: __traceiter_x86_fpu_before_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_x86_fpu_before_restore(void *__data, struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81068380)
Location: arch/x86/include/asm/trace/fpu.h:47
Inline: False
```
**Symbols:**

```
ffffffff81068380-ffffffff810683c3: __traceiter_x86_fpu_before_restore (STB_GLOBAL)
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
