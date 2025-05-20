# Function: <code>fpu__restore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fpu__restore(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81039b90)
Location: arch/x86/kernel/fpu/core.c:364
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81039b90-ffffffff81039cde: fpu__restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fpu__restore(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038fd0)
Location: arch/x86/kernel/fpu/core.c:452
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81038fd0-ffffffff810391d1: fpu__restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fpu__restore(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038ab0)
Location: arch/x86/kernel/fpu/core.c:397
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81038ab0-ffffffff81038ca5: fpu__restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fpu__restore(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81036b00)
Location: arch/x86/kernel/fpu/core.c:390
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81036b00-ffffffff81036cc5: fpu__restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fpu__restore(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038df0)
Location: arch/x86/kernel/fpu/core.c:317
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81038df0-ffffffff81038f55: fpu__restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fpu__restore(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103a4d0)
Location: arch/x86/kernel/fpu/core.c:318
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103a4d0-ffffffff8103a635: fpu__restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fpu__restore(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103b8a0)
Location: arch/x86/kernel/fpu/core.c:316
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103b8a0-ffffffff8103ba05: fpu__restore (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
