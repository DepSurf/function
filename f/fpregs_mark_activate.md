# Function: <code>fpregs_mark_activate</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103de00)
Location: arch/x86/kernel/fpu/core.c:365
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103de00-ffffffff8103de8c: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e5c0)
Location: arch/x86/kernel/fpu/core.c:365
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103e5c0-ffffffff8103e64c: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810419d4)
Location: arch/x86/kernel/fpu/core.c:388
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff810417e0-ffffffff8104186a: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041860)
Location: arch/x86/kernel/fpu/core.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81041860-ffffffff810418d2: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81043260)
Location: arch/x86/kernel/fpu/core.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81043260-ffffffff810432d2: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810495d0)
Location: arch/x86/kernel/fpu/core.c:440
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
**Symbols:**

```
ffffffff810495d0-ffffffff8104963f: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81053990)
Location: arch/x86/kernel/fpu/core.c:777
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
**Symbols:**

```
ffffffff81053990-ffffffff81053a1e: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81061400)
Location: arch/x86/kernel/fpu/core.c:774
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
**Symbols:**

```
ffffffff81061400-ffffffff8106148e: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81062cd0)
Location: arch/x86/kernel/fpu/core.c:774
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
**Symbols:**

```
ffffffff81062cd0-ffffffff81062d5e: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81069fc0)
Location: arch/x86/kernel/fpu/core.c:827
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
```
**Symbols:**

```
ffffffff81069fc0-ffffffff8106a04e: fpregs_mark_activate (STB_GLOBAL)
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
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e740)
Location: arch/x86/kernel/fpu/core.c:365
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103e740-ffffffff8103e7cc: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8102df40)
Location: arch/x86/kernel/fpu/core.c:365
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8102df40-ffffffff8102dfcc: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e580)
Location: arch/x86/kernel/fpu/core.c:365
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103e580-ffffffff8103e60c: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fpregs_mark_activate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103f710)
Location: arch/x86/kernel/fpu/core.c:365
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103f710-ffffffff8103f7b1: fpregs_mark_activate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
