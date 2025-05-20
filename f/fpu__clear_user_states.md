# Function: <code>fpu__clear_user_states</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fpu__clear_user_states(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041e20)
Location: arch/x86/kernel/fpu/core.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81041e20-ffffffff81041e35: fpu__clear_user_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fpu__clear_user_states(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041e30)
Location: arch/x86/kernel/fpu/core.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81041e30-ffffffff81041e45: fpu__clear_user_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fpu__clear_user_states(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81043830)
Location: arch/x86/kernel/fpu/core.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81043830-ffffffff81043845: fpu__clear_user_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fpu__clear_user_states(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810499c0)
Location: arch/x86/kernel/fpu/core.c:372
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
```
**Symbols:**

```
ffffffff810499c0-ffffffff81049a7f: fpu__clear_user_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fpu__clear_user_states(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81053b40)
Location: arch/x86/kernel/fpu/core.c:709
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
```
**Symbols:**

```
ffffffff81053b40-ffffffff81053c1c: fpu__clear_user_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fpu__clear_user_states(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810615e0)
Location: arch/x86/kernel/fpu/core.c:706
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
```
**Symbols:**

```
ffffffff810615e0-ffffffff810616bc: fpu__clear_user_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fpu__clear_user_states(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81062eb0)
Location: arch/x86/kernel/fpu/core.c:706
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
```
**Symbols:**

```
ffffffff81062eb0-ffffffff81062f90: fpu__clear_user_states (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fpu__clear_user_states(struct fpu *fpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8106a1a0)
Location: arch/x86/kernel/fpu/core.c:741
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
```
**Symbols:**

```
ffffffff8106a1a0-ffffffff8106a27c: fpu__clear_user_states (STB_GLOBAL)
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
