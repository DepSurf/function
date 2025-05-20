# Function: <code>fpstate_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81039a70)
Location: arch/x86/kernel/fpu/core.c:210
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_read
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
Direct callers:
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81039a70-ffffffff81039a9c: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038d10)
Location: arch/x86/kernel/fpu/core.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81038d10-ffffffff81038d52: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038800)
Location: arch/x86/kernel/fpu/core.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81038800-ffffffff81038849: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810368c0)
Location: arch/x86/kernel/fpu/core.c:172
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff810368c0-ffffffff81036907: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81038cc0)
Location: arch/x86/kernel/fpu/core.c:172
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff81038cc0-ffffffff81038d07: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103a140)
Location: arch/x86/kernel/fpu/core.c:173
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103a140-ffffffff8103a187: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103b660)
Location: arch/x86/kernel/fpu/core.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/core.c:fpu__prepare_write
  - arch/x86/kernel/fpu/core.c:fpu__prepare_read
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
```
**Symbols:**

```
ffffffff8103b660-ffffffff8103b6a7: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103dc80)
Location: arch/x86/kernel/fpu/core.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff8103dc80-ffffffff8103dcc7: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e440)
Location: arch/x86/kernel/fpu/core.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff8103e440-ffffffff8103e487: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041430)
Location: arch/x86/kernel/fpu/core.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff81041430-ffffffff81041477: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041510)
Location: arch/x86/kernel/fpu/core.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff81041510-ffffffff81041557: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81042f10)
Location: arch/x86/kernel/fpu/core.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff81042f10-ffffffff81042f57: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81049210)
Location: arch/x86/kernel/fpu/core.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
**Symbols:**

```
ffffffff81049210-ffffffff81049257: fpstate_init (STB_GLOBAL)
```
</details>
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
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e5c0)
Location: arch/x86/kernel/fpu/core.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff8103e5c0-ffffffff8103e607: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8102ddc0)
Location: arch/x86/kernel/fpu/core.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff8102ddc0-ffffffff8102de07: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e400)
Location: arch/x86/kernel/fpu/core.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff8103e400-ffffffff8103e447: fpstate_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103f590)
Location: arch/x86/kernel/fpu/core.c:149
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
```
**Symbols:**

```
ffffffff8103f590-ffffffff8103f5d7: fpstate_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
