# Function: <code>convert_from_fxsr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a7a0)
Location: arch/x86/kernel/fpu/regset.c:205
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff8103a7a0-ffffffff8103a916: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81039fe0)
Location: arch/x86/kernel/fpu/regset.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff81039fe0-ffffffff8103a153: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810398d0)
Location: arch/x86/kernel/fpu/regset.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff810398d0-ffffffff81039a43: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810377a0)
Location: arch/x86/kernel/fpu/regset.c:231
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff810377a0-ffffffff8103792a: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81039a50)
Location: arch/x86/kernel/fpu/regset.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff81039a50-ffffffff81039bda: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103afe0)
Location: arch/x86/kernel/fpu/regset.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff8103afe0-ffffffff8103b156: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103c4e0)
Location: arch/x86/kernel/fpu/regset.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff8103c4e0-ffffffff8103c656: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ea40)
Location: arch/x86/kernel/fpu/regset.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff8103ea40-ffffffff8103ebb6: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f150)
Location: arch/x86/kernel/fpu/regset.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff8103f150-ffffffff8103f2c6: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81042300)
Location: arch/x86/kernel/fpu/regset.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff81042300-ffffffff81042479: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810422e0)
Location: arch/x86/kernel/fpu/regset.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff810422e0-ffffffff81042459: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81043ce0)
Location: arch/x86/kernel/fpu/regset.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff81043ce0-ffffffff81043e2f: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8104a180)
Location: arch/x86/kernel/fpu/regset.c:283
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff8104a180-ffffffff8104a197: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810542a0)
Location: arch/x86/kernel/fpu/regset.c:287
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff810542a0-ffffffff810542c7: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81061f00)
Location: arch/x86/kernel/fpu/regset.c:287
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff81061f00-ffffffff81061f27: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810637e0)
Location: arch/x86/kernel/fpu/regset.c:287
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff810637e0-ffffffff81063807: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8106ad10)
Location: arch/x86/kernel/fpu/regset.c:368
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff8106ad10-ffffffff8106ad37: convert_from_fxsr (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f2d0)
Location: arch/x86/kernel/fpu/regset.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff8103f2d0-ffffffff8103f446: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8102ead0)
Location: arch/x86/kernel/fpu/regset.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff8102ead0-ffffffff8102ec46: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f110)
Location: arch/x86/kernel/fpu/regset.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff8103f110-ffffffff8103f286: convert_from_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void convert_from_fxsr(struct user_i387_ia32_struct *env, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810403f0)
Location: arch/x86/kernel/fpu/regset.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/signal.c:save_fsave_header
```
**Symbols:**

```
ffffffff810403f0-ffffffff81040566: convert_from_fxsr (STB_GLOBAL)
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
