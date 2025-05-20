# Function: <code>copyout_from_xsaves</code>

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
int copyout_from_xsaves(unsigned int pos, unsigned int count, void *kbuf, void *ubuf, struct xregs_state *xsave);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b3c0)
Location: arch/x86/kernel/fpu/xstate.c:949
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff8103b3c0-ffffffff8103b5fb: copyout_from_xsaves (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int copyout_from_xsaves(unsigned int pos, unsigned int count, void *kbuf, void *ubuf, struct xregs_state *xsave);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103ac60)
Location: arch/x86/kernel/fpu/xstate.c:947
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff8103ac60-ffffffff8103ae9b: copyout_from_xsaves (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int copyout_from_xsaves(unsigned int pos, unsigned int count, void *kbuf, void *ubuf, struct xregs_state *xsave);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038ac0)
Location: arch/x86/kernel/fpu/xstate.c:954
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81038ac0-ffffffff81038d59: copyout_from_xsaves (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
