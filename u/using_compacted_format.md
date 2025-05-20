# Function: <code>using_compacted_format</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81f69e49)
Location: arch/x86/kernel/fpu/xstate.c:404
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81f91fcc)
Location: arch/x86/kernel/fpu/xstate.c:475
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
**Symbols:**

```
ffffffff8103b170-ffffffff8103b189: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81fcd27c)
Location: arch/x86/kernel/fpu/xstate.c:480
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
**Symbols:**

```
ffffffff8103aa50-ffffffff8103aa69: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff820ad95e)
Location: arch/x86/kernel/fpu/xstate.c:481
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
**Symbols:**

```
ffffffff81038970-ffffffff81038989: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b831)
Location: arch/x86/kernel/fpu/xstate.c:475
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
**Symbols:**

```
ffffffff8103aa90-ffffffff8103aaa9: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103cd0f)
Location: arch/x86/kernel/fpu/xstate.c:475
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
**Symbols:**

```
ffffffff8103bf90-ffffffff8103bfa9: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103e23c)
Location: arch/x86/kernel/fpu/xstate.c:475
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
**Symbols:**

```
ffffffff8103d450-ffffffff8103d469: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ab49b)
Location: arch/x86/kernel/fpu/xstate.c:469
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103fd00-ffffffff8103fd19: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ae2d4)
Location: arch/x86/kernel/fpu/xstate.c:469
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81040420-ffffffff81040439: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff810445b6)
Location: arch/x86/kernel/fpu/xstate.c:507
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81043780-ffffffff81043799: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81bd4a65)
Location: arch/x86/kernel/fpu/xstate.c:512
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81043810-ffffffff81043829: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff81bc6eb3)
Location: arch/x86/kernel/fpu/xstate.c:547
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
```
**Symbols:**

```
ffffffff81045060-ffffffff81045079: using_compacted_format (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8289c2f3)
Location: arch/x86/kernel/fpu/xstate.c:469
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff810405a0-ffffffff810405b9: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff82894523)
Location: arch/x86/kernel/fpu/xstate.c:469
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8102fd80-ffffffff8102fd99: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af2b6)
Location: arch/x86/kernel/fpu/xstate.c:469
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff810403e0-ffffffff810403f9: using_compacted_format (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int using_compacted_format();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af2e4)
Location: arch/x86/kernel/fpu/xstate.c:469
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
Direct callers:
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff810417b0-ffffffff810417c9: using_compacted_format (STB_GLOBAL)
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
