# Function: <code>copy_kernel_to_xstate</code>

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
int copy_kernel_to_xstate(struct xregs_state *xsave, const void *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b170)
Location: arch/x86/kernel/fpu/xstate.c:1146
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff8103b170-ffffffff8103b2d3: copy_kernel_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_kernel_to_xstate(struct xregs_state *xsave, const void *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c670)
Location: arch/x86/kernel/fpu/xstate.c:1146
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff8103c670-ffffffff8103c7cf: copy_kernel_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_kernel_to_xstate(struct xregs_state *xsave, const void *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103db90)
Location: arch/x86/kernel/fpu/xstate.c:1144
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff8103db90-ffffffff8103dcef: copy_kernel_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_kernel_to_xstate(struct xregs_state *xsave, const void *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810403c0)
Location: arch/x86/kernel/fpu/xstate.c:1134
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff810403c0-ffffffff81040509: copy_kernel_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_kernel_to_xstate(struct xregs_state *xsave, const void *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040b90)
Location: arch/x86/kernel/fpu/xstate.c:1134
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff81040b90-ffffffff81040cd9: copy_kernel_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_kernel_to_xstate(struct xregs_state *xsave, const void *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043dd0)
Location: arch/x86/kernel/fpu/xstate.c:1201
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff81043dd0-ffffffff81043f21: copy_kernel_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_kernel_to_xstate(struct xregs_state *xsave, const void *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043c50)
Location: arch/x86/kernel/fpu/xstate.c:1131
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff81043c50-ffffffff81043da1: copy_kernel_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_kernel_to_xstate(struct xregs_state *xsave, const void *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045960)
Location: arch/x86/kernel/fpu/xstate.c:1183
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff81045960-ffffffff81045aaf: copy_kernel_to_xstate (STB_GLOBAL)
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
int copy_kernel_to_xstate(struct xregs_state *xsave, const void *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040d10)
Location: arch/x86/kernel/fpu/xstate.c:1134
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff81040d10-ffffffff81040e59: copy_kernel_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_kernel_to_xstate(struct xregs_state *xsave, const void *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810304f0)
Location: arch/x86/kernel/fpu/xstate.c:1134
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff810304f0-ffffffff81030639: copy_kernel_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_kernel_to_xstate(struct xregs_state *xsave, const void *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040b50)
Location: arch/x86/kernel/fpu/xstate.c:1134
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff81040b50-ffffffff81040c99: copy_kernel_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_kernel_to_xstate(struct xregs_state *xsave, const void *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041f30)
Location: arch/x86/kernel/fpu/xstate.c:1134
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff81041f30-ffffffff81042079: copy_kernel_to_xstate (STB_GLOBAL)
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
