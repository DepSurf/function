# Function: <code>convert_to_fxsr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void convert_to_fxsr(struct task_struct *tsk, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a920)
Location: arch/x86/kernel/fpu/regset.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103a920-ffffffff8103a9c4: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void convert_to_fxsr(struct task_struct *tsk, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a160)
Location: arch/x86/kernel/fpu/regset.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103a160-ffffffff8103a1f2: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void convert_to_fxsr(struct task_struct *tsk, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81039a50)
Location: arch/x86/kernel/fpu/regset.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81039a50-ffffffff81039ae2: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void convert_to_fxsr(struct task_struct *tsk, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81037930)
Location: arch/x86/kernel/fpu/regset.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81037930-ffffffff810379c2: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void convert_to_fxsr(struct task_struct *tsk, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81039be0)
Location: arch/x86/kernel/fpu/regset.c:272
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81039be0-ffffffff81039c72: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void convert_to_fxsr(struct task_struct *tsk, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103b160)
Location: arch/x86/kernel/fpu/regset.c:272
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103b160-ffffffff8103b1f2: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void convert_to_fxsr(struct task_struct *tsk, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103c660)
Location: arch/x86/kernel/fpu/regset.c:272
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103c660-ffffffff8103c6f2: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ebc0)
Location: arch/x86/kernel/fpu/regset.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103ebc0-ffffffff8103ec4f: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f2d0)
Location: arch/x86/kernel/fpu/regset.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103f2d0-ffffffff8103f35f: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81042480)
Location: arch/x86/kernel/fpu/regset.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81042480-ffffffff8104250f: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81042460)
Location: arch/x86/kernel/fpu/regset.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81042460-ffffffff810424ef: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81043e30)
Location: arch/x86/kernel/fpu/regset.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81043e30-ffffffff81043ec2: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8104a1a0)
Location: arch/x86/kernel/fpu/regset.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff8104a1a0-ffffffff8104a232: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810542d0)
Location: arch/x86/kernel/fpu/regset.c:292
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff810542d0-ffffffff81054370: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81061f40)
Location: arch/x86/kernel/fpu/regset.c:292
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff81061f40-ffffffff81061fe0: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81063820)
Location: arch/x86/kernel/fpu/regset.c:292
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff81063820-ffffffff810638c0: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8106ad50)
Location: arch/x86/kernel/fpu/regset.c:373
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
```
**Symbols:**

```
ffffffff8106ad50-ffffffff8106adf0: convert_to_fxsr (STB_GLOBAL)
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
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f450)
Location: arch/x86/kernel/fpu/regset.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103f450-ffffffff8103f4df: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8102ec50)
Location: arch/x86/kernel/fpu/regset.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8102ec50-ffffffff8102ecdf: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f290)
Location: arch/x86/kernel/fpu/regset.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103f290-ffffffff8103f31f: convert_to_fxsr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void convert_to_fxsr(struct fxregs_state *fxsave, const struct user_i387_ia32_struct *env);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81040570)
Location: arch/x86/kernel/fpu/regset.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81040570-ffffffff810405ff: convert_to_fxsr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fxregs_state *fxsave</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
</ul>
</details>
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
