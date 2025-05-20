# Function: <code>compat_restore_altstack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81091b70)
Location: kernel/signal.c:3210
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
```
**Symbols:**

```
ffffffff81091b70-ffffffff81091c97: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094cc0)
Location: kernel/signal.c:3213
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
```
**Symbols:**

```
ffffffff81094cc0-ffffffff81094dd0: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099cd0)
Location: kernel/signal.c:3233
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
```
**Symbols:**

```
ffffffff81099cd0-ffffffff81099de0: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81096dc0)
Location: kernel/signal.c:3273
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
```
**Symbols:**

```
ffffffff81096dc0-ffffffff81096e74: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109db60)
Location: kernel/signal.c:3294
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
```
**Symbols:**

```
ffffffff8109db60-ffffffff8109dc14: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a2ce0)
Location: kernel/signal.c:3533
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
```
**Symbols:**

```
ffffffff810a2ce0-ffffffff810a2cf9: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab8d0)
Location: kernel/signal.c:3861
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
```
**Symbols:**

```
ffffffff810ab8d0-ffffffff810ab8e9: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0dc0)
Location: kernel/signal.c:4109
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
```
**Symbols:**

```
ffffffff810b0dc0-ffffffff810b0dd9: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7510)
Location: kernel/signal.c:4117
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810b7510-ffffffff810b7529: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bf460)
Location: kernel/signal.c:4135
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810bf460-ffffffff810bf479: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba670)
Location: kernel/signal.c:4172
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810ba670-ffffffff810ba689: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bbfa0)
Location: kernel/signal.c:4194
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810bbfa0-ffffffff810bbfb9: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ce9c0)
Location: kernel/signal.c:4282
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810ce9c0-ffffffff810ce9d9: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e6940)
Location: kernel/signal.c:4297
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810e6940-ffffffff810e6961: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811075d0)
Location: kernel/signal.c:4299
Inline: False
Direct callers:
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff811075d0-ffffffff811075f1: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811138c0)
Location: kernel/signal.c:4323
Inline: False
Direct callers:
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff811138c0-ffffffff811138e1: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111d2b0)
Location: kernel/signal.c:4334
Inline: False
Direct callers:
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff8111d2b0-ffffffff8111d2d1: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff8000101137d8)
Location: kernel/signal.c:4117
Inline: False
Direct callers:
  - arch/arm64/kernel/signal32.c:__arm64_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffff8000101137d8-ffff800010113814: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c00000000015b4f0)
Location: kernel/signal.c:4117
Inline: False
Direct callers:
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
```
**Symbols:**

```
c00000000015b4f0-c00000000015b530: compat_restore_altstack (STB_GLOBAL)
```
</details>
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
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1880)
Location: kernel/signal.c:4117
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810b1880-ffffffff810b1899: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a01a0)
Location: kernel/signal.c:4117
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810a01a0-ffffffff810a01b9: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0de0)
Location: kernel/signal.c:4117
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810b0de0-ffffffff810b0df9: compat_restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compat_restore_altstack(const compat_stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b90b0)
Location: kernel/signal.c:4117
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810b90b0-ffffffff810b90c9: compat_restore_altstack (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
