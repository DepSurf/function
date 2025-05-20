# Function: <code>fpu__activate_fpstate_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fpu__activate_fpstate_write(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103a170)
Location: arch/x86/kernel/fpu/core.c:335
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_set
```
**Symbols:**

```
ffffffff8103a170-ffffffff8103a1eb: fpu__activate_fpstate_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fpu__activate_fpstate_write(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810396b0)
Location: arch/x86/kernel/fpu/core.c:358
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
**Symbols:**

```
ffffffff810396b0-ffffffff810397ad: fpu__activate_fpstate_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fpu__activate_fpstate_write(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81039000)
Location: arch/x86/kernel/fpu/core.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
**Symbols:**

```
ffffffff81039000-ffffffff810390fd: fpu__activate_fpstate_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fpu__activate_fpstate_write(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81036f90)
Location: arch/x86/kernel/fpu/core.c:296
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
```
**Symbols:**

```
ffffffff81036f90-ffffffff81037066: fpu__activate_fpstate_write (STB_GLOBAL)
```
</details>
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
</ul>
