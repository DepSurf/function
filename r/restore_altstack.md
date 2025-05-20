# Function: <code>restore_altstack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81091930)
Location: kernel/signal.c:3160
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
**Symbols:**

```
ffffffff81091930-ffffffff81091966: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094aa0)
Location: kernel/signal.c:3158
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
**Symbols:**

```
ffffffff81094aa0-ffffffff81094ad1: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099ab0)
Location: kernel/signal.c:3178
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
**Symbols:**

```
ffffffff81099ab0-ffffffff81099ae1: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81096bd0)
Location: kernel/signal.c:3220
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
**Symbols:**

```
ffffffff81096bd0-ffffffff81096c40: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d970)
Location: kernel/signal.c:3241
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
**Symbols:**

```
ffffffff8109d970-ffffffff8109d9e0: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a2bf0)
Location: kernel/signal.c:3474
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810a2bf0-ffffffff810a2c60: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab7d0)
Location: kernel/signal.c:3800
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810ab7d0-ffffffff810ab840: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0cb0)
Location: kernel/signal.c:4048
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810b0cb0-ffffffff810b0d20: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7400)
Location: kernel/signal.c:4056
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810b7400-ffffffff810b7470: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bf2e0)
Location: kernel/signal.c:4074
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810bf2e0-ffffffff810bf3b9: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba500)
Location: kernel/signal.c:4111
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810ba500-ffffffff810ba5d9: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bbe30)
Location: kernel/signal.c:4133
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810bbe30-ffffffff810bbf09: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ce890)
Location: kernel/signal.c:4225
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810ce890-ffffffff810ce969: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e6840)
Location: kernel/signal.c:4240
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810e6840-ffffffff810e68d2: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811074b0)
Location: kernel/signal.c:4242
Inline: False
Direct callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff811074b0-ffffffff81107542: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811137a0)
Location: kernel/signal.c:4266
Inline: False
Direct callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff811137a0-ffffffff81113832: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111d190)
Location: kernel/signal.c:4277
Inline: False
Direct callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff8111d190-ffffffff8111d222: restore_altstack (STB_GLOBAL)
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
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010113430)
Location: kernel/signal.c:4056
Inline: False
Direct callers:
  - arch/arm64/kernel/signal.c:__arm64_sys_rt_sigreturn
```
**Symbols:**

```
ffff800010113430-ffff8000101135b4: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036a220)
Location: kernel/signal.c:4056
Inline: False
Direct callers:
  - arch/arm/kernel/signal.c:sys_rt_sigreturn
```
**Symbols:**

```
c036a220-c036a2f4: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c00000000015b2d0)
Location: kernel/signal.c:4056
Inline: False
Direct callers:
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
```
**Symbols:**

```
c00000000015b2d0-c00000000015b370: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d1cd6)
Location: kernel/signal.c:4056
Inline: False
Direct callers:
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
```
**Symbols:**

```
ffffffe0000d1cd6-ffffffe0000d1d28: restore_altstack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1770)
Location: kernel/signal.c:4056
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810b1770-ffffffff810b17e0: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a0090)
Location: kernel/signal.c:4056
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810a0090-ffffffff810a0100: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0cd0)
Location: kernel/signal.c:4056
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810b0cd0-ffffffff810b0d40: restore_altstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int restore_altstack(const stack_t *uss);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8fa0)
Location: kernel/signal.c:4056
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810b8fa0-ffffffff810b9010: restore_altstack (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
