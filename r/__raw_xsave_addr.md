# Function: <code>__raw_xsave_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *__raw_xsave_addr(struct xregs_state *xsave, int xstate_feature_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b1c0)
Location: arch/x86/kernel/fpu/xstate.c:775
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
**Symbols:**

```
ffffffff8103b1c0-ffffffff8103b227: __raw_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *__raw_xsave_addr(struct xregs_state *xsave, int xstate_feature_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103aaa0)
Location: arch/x86/kernel/fpu/xstate.c:780
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
**Symbols:**

```
ffffffff8103aaa0-ffffffff8103ab07: __raw_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *__raw_xsave_addr(struct xregs_state *xsave, int xstate_feature_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81038da8)
Location: arch/x86/kernel/fpu/xstate.c:787
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves
  - arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
**Symbols:**

```
ffffffff810385a0-ffffffff810385af: __raw_xsave_addr.part.5 (STB_LOCAL)
ffffffff810389c0-ffffffff810389fb: __raw_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *__raw_xsave_addr(struct xregs_state *xsave, int xstate_feature_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b345)
Location: arch/x86/kernel/fpu/xstate.c:814
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
**Symbols:**

```
ffffffff8103a7e0-ffffffff8103a7ef: __raw_xsave_addr.part.6 (STB_LOCAL)
ffffffff8103ab30-ffffffff8103ab6c: __raw_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *__raw_xsave_addr(struct xregs_state *xsave, int xstate_feature_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103c839)
Location: arch/x86/kernel/fpu/xstate.c:814
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
**Symbols:**

```
ffffffff8103bce0-ffffffff8103bcef: __raw_xsave_addr.part.6 (STB_LOCAL)
ffffffff8103c030-ffffffff8103c06c: __raw_xsave_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103dd59)
Location: arch/x86/kernel/fpu/xstate.c:812
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
**Symbols:**

```
ffffffff8103d1a0-ffffffff8103d1af: __raw_xsave_addr.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104058a)
Location: arch/x86/kernel/fpu/xstate.c:806
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
**Symbols:**

```
ffffffff8103fa70-ffffffff8103fa7f: __raw_xsave_addr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040d5a)
Location: arch/x86/kernel/fpu/xstate.c:806
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
```
**Symbols:**

```
ffffffff81040190-ffffffff8104019f: __raw_xsave_addr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043fb4)
Location: arch/x86/kernel/fpu/xstate.c:859
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81043e35)
Location: arch/x86/kernel/fpu/xstate.c:899
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045b35)
Location: arch/x86/kernel/fpu/xstate.c:934
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104b278)
Location: arch/x86/kernel/fpu/xstate.c:850
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__raw_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:931
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
**Symbols:**

```
ffffffff810558b0-ffffffff8105592a: __raw_xsave_addr (STB_LOCAL)
ffffffff81e49928-ffffffff81e49965: __raw_xsave_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__raw_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:926
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
**Symbols:**

```
ffffffff810633b0-ffffffff8106342a: __raw_xsave_addr (STB_LOCAL)
ffffffff8205264d-ffffffff8205268a: __raw_xsave_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__raw_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:933
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
**Symbols:**

```
ffffffff81064d00-ffffffff81064d7a: __raw_xsave_addr (STB_LOCAL)
ffffffff820d0b24-ffffffff820d0b5b: __raw_xsave_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__raw_xsave_addr(struct xregs_state *xsave, int xfeature_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/kernel/fpu/xstate.c:929
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate
  - arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf
  - arch/x86/kernel/fpu/xstate.c:get_xsave_addr
```
**Symbols:**

```
ffffffff8106c3b0-ffffffff8106c42a: __raw_xsave_addr (STB_LOCAL)
ffffffff821ab64d-ffffffff821ab684: __raw_xsave_addr.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040eda)
Location: arch/x86/kernel/fpu/xstate.c:806
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
```
**Symbols:**

```
ffffffff81040310-ffffffff8104031f: __raw_xsave_addr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810306ba)
Location: arch/x86/kernel/fpu/xstate.c:806
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
```
**Symbols:**

```
ffffffff8102fb10-ffffffff8102fb1f: __raw_xsave_addr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040d1a)
Location: arch/x86/kernel/fpu/xstate.c:806
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
```
**Symbols:**

```
ffffffff81040150-ffffffff8104015f: __raw_xsave_addr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810420fa)
Location: arch/x86/kernel/fpu/xstate.c:806
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user
  - arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel
```
**Symbols:**

```
ffffffff81041520-ffffffff8104152f: __raw_xsave_addr.part.0 (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
