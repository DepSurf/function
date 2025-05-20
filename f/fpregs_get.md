# Function: <code>fpregs_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a9d0)
Location: arch/x86/kernel/fpu/regset.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff8103a9d0-ffffffff8103aaad: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103a200)
Location: arch/x86/kernel/fpu/regset.c:294
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff8103a200-ffffffff8103a2f2: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81039af0)
Location: arch/x86/kernel/fpu/regset.c:294
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff81039af0-ffffffff81039be2: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810379d0)
Location: arch/x86/kernel/fpu/regset.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff810379d0-ffffffff81037b00: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81039c80)
Location: arch/x86/kernel/fpu/regset.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff81039c80-ffffffff81039db0: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103b200)
Location: arch/x86/kernel/fpu/regset.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff8103b200-ffffffff8103b2d8: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103c700)
Location: arch/x86/kernel/fpu/regset.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff8103c700-ffffffff8103c7d8: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ec50)
Location: arch/x86/kernel/fpu/regset.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff8103ec50-ffffffff8103ed55: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f360)
Location: arch/x86/kernel/fpu/regset.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff8103f360-ffffffff8103f465: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81042510)
Location: arch/x86/kernel/fpu/regset.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff81042510-ffffffff81042615: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, struct membuf to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810424f0)
Location: arch/x86/kernel/fpu/regset.c:288
Inline: False
```
**Symbols:**

```
ffffffff810424f0-ffffffff81042612: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, struct membuf to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81043ed0)
Location: arch/x86/kernel/fpu/regset.c:288
Inline: False
```
**Symbols:**

```
ffffffff81043ed0-ffffffff81043ff5: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, struct membuf to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8104a240)
Location: arch/x86/kernel/fpu/regset.c:315
Inline: False
```
**Symbols:**

```
ffffffff8104a240-ffffffff8104a386: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, struct membuf to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81054370)
Location: arch/x86/kernel/fpu/regset.c:319
Inline: False
```
**Symbols:**

```
ffffffff81054370-ffffffff810544fe: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, struct membuf to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81061ff0)
Location: arch/x86/kernel/fpu/regset.c:319
Inline: False
```
**Symbols:**

```
ffffffff81061ff0-ffffffff810620fc: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, struct membuf to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810638d0)
Location: arch/x86/kernel/fpu/regset.c:319
Inline: False
```
**Symbols:**

```
ffffffff810638d0-ffffffff810639dc: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, struct membuf to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8106ae00)
Location: arch/x86/kernel/fpu/regset.c:400
Inline: False
```
**Symbols:**

```
ffffffff8106ae00-ffffffff8106af0c: fpregs_get (STB_GLOBAL)
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
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f4e0)
Location: arch/x86/kernel/fpu/regset.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff8103f4e0-ffffffff8103f5e5: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8102ece0)
Location: arch/x86/kernel/fpu/regset.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff8102ece0-ffffffff8102ede5: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103f320)
Location: arch/x86/kernel/fpu/regset.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff8103f320-ffffffff8103f425: fpregs_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fpregs_get(struct task_struct *target, const struct user_regset *regset, unsigned int pos, unsigned int count, void *kbuf, void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81040600)
Location: arch/x86/kernel/fpu/regset.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:dump_fpu
```
**Symbols:**

```
ffffffff81040600-ffffffff81040705: fpregs_get (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct membuf to</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int pos</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int count</code>
</li>
<li>
<b>Param removed. </b>
<code>void *kbuf</code>
</li>
<li>
<b>Param removed. </b>
<code>void *ubuf</code>
</li>
</ul>
</details>
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
