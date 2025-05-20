# Function: <code>fpu__get_fpstate_size</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int fpu__get_fpstate_size();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff8104aef0)
Location: arch/x86/kernel/fpu/signal.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:init_sigframe_size
```
**Symbols:**

```
ffffffff8104aef0-ffffffff8104af1d: fpu__get_fpstate_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int fpu__get_fpstate_size();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff8345a0bd)
Location: arch/x86/kernel/fpu/signal.c:522
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:init_sigframe_size
```
**Symbols:**

```
ffffffff8345a0bd-ffffffff8345a0df: fpu__get_fpstate_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int fpu__get_fpstate_size();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff83e79d10)
Location: arch/x86/kernel/fpu/signal.c:522
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:init_sigframe_size
```
**Symbols:**

```
ffffffff83e79d10-ffffffff83e79d32: fpu__get_fpstate_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int fpu__get_fpstate_size();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff8369c430)
Location: arch/x86/kernel/fpu/signal.c:522
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:init_sigframe_size
```
**Symbols:**

```
ffffffff8369c430-ffffffff8369c452: fpu__get_fpstate_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int fpu__get_fpstate_size();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/signal.c (ffffffff838cc110)
Location: arch/x86/kernel/fpu/signal.c:519
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:init_sigframe_size
```
**Symbols:**

```
ffffffff838cc110-ffffffff838cc132: fpu__get_fpstate_size (STB_GLOBAL)
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
