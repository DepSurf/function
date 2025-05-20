# Function: <code>siginfo_layout</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d040)
Location: kernel/signal.c:2674
Inline: True
Direct callers:
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff8109d040-ffffffff8109d09b: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a1a10)
Location: kernel/signal.c:2807
Inline: True
Direct callers:
  - kernel/signal.c:copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff810a1a10-ffffffff810a1aa5: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a9f90)
Location: kernel/signal.c:3018
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff810a9f90-ffffffff810aa024: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac940)
Location: kernel/signal.c:3147
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff810ac940-ffffffff810ac9d4: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2f50)
Location: kernel/signal.c:3152
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff810b2f50-ffffffff810b2fe4: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bb9e0)
Location: kernel/signal.c:3170
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_external32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff810bb9e0-ffffffff810bba74: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6ca0)
Location: kernel/signal.c:3190
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_external32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff810b6ca0-ffffffff810b6d34: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8260)
Location: kernel/signal.c:3212
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_external32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff810b8260-ffffffff810b82ff: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ca6f0)
Location: kernel/signal.c:3297
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff810ca6f0-ffffffff810ca7e1: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e2050)
Location: kernel/signal.c:3277
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff810e2050-ffffffff810e2159: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811023e0)
Location: kernel/signal.c:3279
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff811023e0-ffffffff811024e9: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110e620)
Location: kernel/signal.c:3303
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff8110e620-ffffffff8110e72b: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81117fa0)
Location: kernel/signal.c:3314
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:get_signal
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff81117fa0-ffffffff811180ab: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010ed60)
Location: kernel/signal.c:3152
Inline: True
Direct callers:
  - arch/arm64/kernel/traps.c:force_signal_inject
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffff80001010ed60-ffff80001010ee48: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0366a8c)
Location: kernel/signal.c:3152
Inline: True
Direct callers:
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
c0366a8c-c0366b74: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000156100)
Location: kernel/signal.c:3152
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
c000000000156100-c0000000001561ec: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cf40e)
Location: kernel/signal.c:3152
Inline: True
Direct callers:
  - kernel/signal.c:send_signal
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffe0000cf40e-ffffffe0000cf4c8: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad2c0)
Location: kernel/signal.c:3152
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff810ad2c0-ffffffff810ad354: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109bc40)
Location: kernel/signal.c:3152
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff8109bc40-ffffffff8109bcd4: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac820)
Location: kernel/signal.c:3152
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff810ac820-ffffffff810ac8b4: siginfo_layout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
enum siginfo_layout siginfo_layout(unsigned int sig, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4990)
Location: kernel/signal.c:3152
Inline: True
Direct callers:
  - kernel/signal.c:post_copy_siginfo_from_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - fs/signalfd.c:signalfd_copyinfo
```
**Symbols:**

```
ffffffff810b4990-ffffffff810b4a24: siginfo_layout (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int sig</code> ➡️ <code>unsigned int sig</code>
</li>
</ul>
</details>
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
