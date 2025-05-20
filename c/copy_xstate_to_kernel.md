# Function: <code>copy_xstate_to_kernel</code>

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
int copy_xstate_to_kernel(void *kbuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ac30)
Location: arch/x86/kernel/fpu/xstate.c:989
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff8103ac30-ffffffff8103afc4: copy_xstate_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_xstate_to_kernel(void *kbuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c130)
Location: arch/x86/kernel/fpu/xstate.c:989
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff8103c130-ffffffff8103c4b7: copy_xstate_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_xstate_to_kernel(void *kbuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103d5b0)
Location: arch/x86/kernel/fpu/xstate.c:987
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff8103d5b0-ffffffff8103d937: copy_xstate_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_xstate_to_kernel(void *kbuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103fea0)
Location: arch/x86/kernel/fpu/xstate.c:977
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff8103fea0-ffffffff81040229: copy_xstate_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_xstate_to_kernel(void *kbuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810405c0)
Location: arch/x86/kernel/fpu/xstate.c:977
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff810405c0-ffffffff81040949: copy_xstate_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_xstate_to_kernel(void *kbuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043970)
Location: arch/x86/kernel/fpu/xstate.c:1047
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81043970-ffffffff81043b90: copy_xstate_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_xstate_to_kernel(struct membuf to, struct xregs_state *xsave);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043a20)
Location: arch/x86/kernel/fpu/xstate.c:1075
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81043a20-ffffffff81043c4b: copy_xstate_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_xstate_to_kernel(struct membuf to, struct xregs_state *xsave);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045260)
Location: arch/x86/kernel/fpu/xstate.c:1100
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81045260-ffffffff81045957: copy_xstate_to_kernel (STB_GLOBAL)
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
int copy_xstate_to_kernel(void *kbuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040740)
Location: arch/x86/kernel/fpu/xstate.c:977
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81040740-ffffffff81040ac9: copy_xstate_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_xstate_to_kernel(void *kbuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8102ff20)
Location: arch/x86/kernel/fpu/xstate.c:977
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff8102ff20-ffffffff810302a9: copy_xstate_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_xstate_to_kernel(void *kbuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040580)
Location: arch/x86/kernel/fpu/xstate.c:977
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81040580-ffffffff81040909: copy_xstate_to_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_xstate_to_kernel(void *kbuf, struct xregs_state *xsave, unsigned int offset_start, unsigned int size_total);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81041960)
Location: arch/x86/kernel/fpu/xstate.c:977
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81041960-ffffffff81041ce9: copy_xstate_to_kernel (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct membuf to</code>
</li>
<li>
<b>Param removed. </b>
<code>void *kbuf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int offset_start</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int size_total</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
