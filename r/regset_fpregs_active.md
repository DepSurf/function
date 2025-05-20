# Function: <code>regset_fpregs_active</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/kernel/fpu/regset.c:14
Inline: False
```
**Symbols:**

```
ffffffff81039bb0-ffffffff81039bc9: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (0)
Location: arch/x86/kernel/fpu/regset.c:14
Inline: False
```
**Symbols:**

```
ffffffff810394a0-ffffffff810394b9: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81037370)
Location: arch/x86/kernel/fpu/regset.c:15
Inline: True
```
**Symbols:**

```
ffffffff81037370-ffffffff81037389: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81039610)
Location: arch/x86/kernel/fpu/regset.c:16
Inline: True
```
**Symbols:**

```
ffffffff81039610-ffffffff81039629: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103aca0)
Location: arch/x86/kernel/fpu/regset.c:16
Inline: True
```
**Symbols:**

```
ffffffff8103aca0-ffffffff8103acb9: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103c1a0)
Location: arch/x86/kernel/fpu/regset.c:16
Inline: True
```
**Symbols:**

```
ffffffff8103c1a0-ffffffff8103c1b9: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103e6a0)
Location: arch/x86/kernel/fpu/regset.c:16
Inline: False
```
**Symbols:**

```
ffffffff8103e6a0-ffffffff8103e6ae: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ed20)
Location: arch/x86/kernel/fpu/regset.c:16
Inline: False
```
**Symbols:**

```
ffffffff8103ed20-ffffffff8103ed2e: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81041ed0)
Location: arch/x86/kernel/fpu/regset.c:16
Inline: True
```
**Symbols:**

```
ffffffff81041ed0-ffffffff81041ede: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81041ee0)
Location: arch/x86/kernel/fpu/regset.c:16
Inline: True
```
**Symbols:**

```
ffffffff81041ee0-ffffffff81041eee: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff810438e0)
Location: arch/x86/kernel/fpu/regset.c:16
Inline: True
```
**Symbols:**

```
ffffffff810438e0-ffffffff810438ee: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81049d60)
Location: arch/x86/kernel/fpu/regset.c:18
Inline: True
```
**Symbols:**

```
ffffffff81049d60-ffffffff81049d6e: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81053e00)
Location: arch/x86/kernel/fpu/regset.c:22
Inline: True
```
**Symbols:**

```
ffffffff81053e00-ffffffff81053e14: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81061a50)
Location: arch/x86/kernel/fpu/regset.c:22
Inline: True
```
**Symbols:**

```
ffffffff81061a50-ffffffff81061a64: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff81063330)
Location: arch/x86/kernel/fpu/regset.c:22
Inline: True
```
**Symbols:**

```
ffffffff81063330-ffffffff81063344: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8106a640)
Location: arch/x86/kernel/fpu/regset.c:23
Inline: True
```
**Symbols:**

```
ffffffff8106a640-ffffffff8106a654: regset_fpregs_active (STB_GLOBAL)
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
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103eea0)
Location: arch/x86/kernel/fpu/regset.c:16
Inline: False
```
**Symbols:**

```
ffffffff8103eea0-ffffffff8103eeae: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8102e6a0)
Location: arch/x86/kernel/fpu/regset.c:16
Inline: False
```
**Symbols:**

```
ffffffff8102e6a0-ffffffff8102e6ae: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ece0)
Location: arch/x86/kernel/fpu/regset.c:16
Inline: False
```
**Symbols:**

```
ffffffff8103ece0-ffffffff8103ecee: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int regset_fpregs_active(struct task_struct *target, const struct user_regset *regset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/regset.c (ffffffff8103ffc0)
Location: arch/x86/kernel/fpu/regset.c:16
Inline: False
```
**Symbols:**

```
ffffffff8103ffc0-ffffffff8103ffce: regset_fpregs_active (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
