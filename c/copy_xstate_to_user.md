# Function: <code>copy_xstate_to_user</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int copy_xstate_to_user(void *ubuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103afd0)
Location: arch/x86/kernel/fpu/xstate.c:1073
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff8103afd0-ffffffff8103b168: copy_xstate_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_xstate_to_user(void *ubuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c4c0)
Location: arch/x86/kernel/fpu/xstate.c:1073
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff8103c4c0-ffffffff8103c668: copy_xstate_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_xstate_to_user(void *ubuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103d940)
Location: arch/x86/kernel/fpu/xstate.c:1071
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff8103d940-ffffffff8103db8c: copy_xstate_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_xstate_to_user(void *ubuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040230)
Location: arch/x86/kernel/fpu/xstate.c:1061
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81040230-ffffffff810403bf: copy_xstate_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_xstate_to_user(void *ubuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040950)
Location: arch/x86/kernel/fpu/xstate.c:1061
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81040950-ffffffff81040b81: copy_xstate_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_xstate_to_user(void *ubuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043b90)
Location: arch/x86/kernel/fpu/xstate.c:1128
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81043b90-ffffffff81043dcd: copy_xstate_to_user (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int copy_xstate_to_user(void *ubuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040ad0)
Location: arch/x86/kernel/fpu/xstate.c:1061
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81040ad0-ffffffff81040d01: copy_xstate_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_xstate_to_user(void *ubuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810302b0)
Location: arch/x86/kernel/fpu/xstate.c:1061
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff810302b0-ffffffff810304e1: copy_xstate_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_xstate_to_user(void *ubuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040910)
Location: arch/x86/kernel/fpu/xstate.c:1061
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81040910-ffffffff81040b41: copy_xstate_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_xstate_to_user(void *ubuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041cf0)
Location: arch/x86/kernel/fpu/xstate.c:1061
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81041cf0-ffffffff81041f21: copy_xstate_to_user (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
