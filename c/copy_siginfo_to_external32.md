# Function: <code>copy_siginfo_to_external32</code>

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
void copy_siginfo_to_external32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810be430)
Location: kernel/signal.c:3266
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:x32_copy_siginfo_to_user
  - kernel/signal.c:__copy_siginfo_to_user32
```
**Symbols:**

```
ffffffff810be430-ffffffff810be5ae: copy_siginfo_to_external32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_siginfo_to_external32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9730)
Location: kernel/signal.c:3286
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:x32_copy_siginfo_to_user
  - kernel/signal.c:__copy_siginfo_to_user32
```
**Symbols:**

```
ffffffff810b9730-ffffffff810b98ae: copy_siginfo_to_external32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_siginfo_to_external32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810baf00)
Location: kernel/signal.c:3314
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:x32_copy_siginfo_to_user
  - kernel/signal.c:__copy_siginfo_to_user32
```
**Symbols:**

```
ffffffff810baf00-ffffffff810bb097: copy_siginfo_to_external32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void copy_siginfo_to_external32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cd810)
Location: kernel/signal.c:3402
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:x32_copy_siginfo_to_user
  - kernel/signal.c:__copy_siginfo_to_user32
```
**Symbols:**

```
ffffffff810cd810-ffffffff810cd9a7: copy_siginfo_to_external32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void copy_siginfo_to_external32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e5730)
Location: kernel/signal.c:3382
Inline: False
Direct callers:
  - kernel/signal.c:__copy_siginfo_to_user32
  - fs/compat_binfmt_elf.c:fill_note_info
```
**Symbols:**

```
ffffffff810e5730-ffffffff810e58e9: copy_siginfo_to_external32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void copy_siginfo_to_external32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811062a0)
Location: kernel/signal.c:3384
Inline: False
Direct callers:
  - kernel/signal.c:__copy_siginfo_to_user32
  - fs/compat_binfmt_elf.c:fill_note_info
```
**Symbols:**

```
ffffffff811062a0-ffffffff81106459: copy_siginfo_to_external32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void copy_siginfo_to_external32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81112580)
Location: kernel/signal.c:3408
Inline: False
Direct callers:
  - kernel/signal.c:__copy_siginfo_to_user32
  - fs/compat_binfmt_elf.c:fill_note_info
```
**Symbols:**

```
ffffffff81112580-ffffffff8111274a: copy_siginfo_to_external32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void copy_siginfo_to_external32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111bf70)
Location: kernel/signal.c:3419
Inline: False
Direct callers:
  - kernel/signal.c:__copy_siginfo_to_user32
  - fs/compat_binfmt_elf.c:fill_note_info
```
**Symbols:**

```
ffffffff8111bf70-ffffffff8111c13a: copy_siginfo_to_external32 (STB_GLOBAL)
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
