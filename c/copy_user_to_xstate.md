# Function: <code>copy_user_to_xstate</code>

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
int copy_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b2e0)
Location: arch/x86/kernel/fpu/xstate.c:1199
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103b2e0-ffffffff8103b452: copy_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c7d0)
Location: arch/x86/kernel/fpu/xstate.c:1199
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103c7d0-ffffffff8103c942: copy_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103dcf0)
Location: arch/x86/kernel/fpu/xstate.c:1197
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103dcf0-ffffffff8103de62: copy_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040510)
Location: arch/x86/kernel/fpu/xstate.c:1187
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81040510-ffffffff81040689: copy_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040ce0)
Location: arch/x86/kernel/fpu/xstate.c:1187
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81040ce0-ffffffff81040e59: copy_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043f30)
Location: arch/x86/kernel/fpu/xstate.c:1254
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81043f30-ffffffff81044098: copy_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043db0)
Location: arch/x86/kernel/fpu/xstate.c:1184
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81043db0-ffffffff81043f1a: copy_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045ab0)
Location: arch/x86/kernel/fpu/xstate.c:1236
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81045ab0-ffffffff81045c1a: copy_user_to_xstate (STB_GLOBAL)
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
int copy_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040e60)
Location: arch/x86/kernel/fpu/xstate.c:1187
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81040e60-ffffffff81040fd9: copy_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81030640)
Location: arch/x86/kernel/fpu/xstate.c:1187
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81030640-ffffffff810307b9: copy_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040ca0)
Location: arch/x86/kernel/fpu/xstate.c:1187
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81040ca0-ffffffff81040e19: copy_user_to_xstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_user_to_xstate(struct xregs_state *xsave, const void *ubuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81042080)
Location: arch/x86/kernel/fpu/xstate.c:1187
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81042080-ffffffff810421f9: copy_user_to_xstate (STB_GLOBAL)
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
