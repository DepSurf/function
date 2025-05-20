# Function: <code>fpu__save</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81039f40)
Location: arch/x86/kernel/fpu/core.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff81039f40-ffffffff8103a007: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810392f0)
Location: arch/x86/kernel/fpu/core.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff810392f0-ffffffff8103944c: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038950)
Location: arch/x86/kernel/fpu/core.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff81038950-ffffffff81038aac: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810369f0)
Location: arch/x86/kernel/fpu/core.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff810369f0-ffffffff81036af7: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038f60)
Location: arch/x86/kernel/fpu/core.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff81038f60-ffffffff8103906d: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103a190)
Location: arch/x86/kernel/fpu/core.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103a190-ffffffff8103a292: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103b6b0)
Location: arch/x86/kernel/fpu/core.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103b6b0-ffffffff8103b7b2: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103dfb0)
Location: arch/x86/kernel/fpu/core.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103dfb0-ffffffff8103e0f6: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e770)
Location: arch/x86/kernel/fpu/core.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103e770-ffffffff8103e8b6: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041a80)
Location: arch/x86/kernel/fpu/core.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff81041a80-ffffffff81041b88: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041af0)
Location: arch/x86/kernel/fpu/core.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff81041af0-ffffffff81041bd3: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810434f0)
Location: arch/x86/kernel/fpu/core.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff810434f0-ffffffff810435d3: fpu__save (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e8f0)
Location: arch/x86/kernel/fpu/core.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103e8f0-ffffffff8103ea36: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8102e0f0)
Location: arch/x86/kernel/fpu/core.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8102e0f0-ffffffff8102e236: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e730)
Location: arch/x86/kernel/fpu/core.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103e730-ffffffff8103e876: fpu__save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fpu__save(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103f900)
Location: arch/x86/kernel/fpu/core.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:math_error
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/xstate.c:get_xsave_field_ptr
```
**Symbols:**

```
ffffffff8103f900-ffffffff8103fa92: fpu__save (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
