# Function: <code>do_sigaction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810915c0)
Location: kernel/signal.c:3047
Inline: False
Direct callers:
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:SyS_signal
```
**Symbols:**

```
ffffffff810915c0-ffffffff8109178a: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094730)
Location: kernel/signal.c:3047
Inline: False
Direct callers:
  - kernel/signal.c:SyS_signal
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
```
**Symbols:**

```
ffffffff81094730-ffffffff810948fa: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099730)
Location: kernel/signal.c:3065
Inline: False
Direct callers:
  - kernel/signal.c:SyS_signal
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
```
**Symbols:**

```
ffffffff81099730-ffffffff81099905: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81096780)
Location: kernel/signal.c:3120
Inline: False
Direct callers:
  - kernel/signal.c:SyS_signal
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
```
**Symbols:**

```
ffffffff81096780-ffffffff8109695b: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d510)
Location: kernel/signal.c:3141
Inline: False
Direct callers:
  - kernel/signal.c:SyS_signal
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:C_SYSC_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:compat_SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
  - kernel/signal.c:SyS_rt_sigaction
```
**Symbols:**

```
ffffffff8109d510-ffffffff8109d6eb: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a2250)
Location: kernel/signal.c:3374
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810a2250-ffffffff810a245d: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aadb0)
Location: kernel/signal.c:3698
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810aadb0-ffffffff810ab001: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b02b0)
Location: kernel/signal.c:3946
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810b02b0-ffffffff810b04fd: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b68c0)
Location: kernel/signal.c:3954
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810b68c0-ffffffff810b6b0d: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810be910)
Location: kernel/signal.c:3972
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810be910-ffffffff810beb5d: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9c10)
Location: kernel/signal.c:3993
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810b9c10-ffffffff810b9e96: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bb400)
Location: kernel/signal.c:4015
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810bb400-ffffffff810bb686: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cdd10)
Location: kernel/signal.c:4103
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x64_compat_sys_rt_sigaction
  - kernel/signal.c:__x64_compat_sys_rt_sigaction
  - kernel/signal.c:__x64_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810cdd10-ffffffff810cdf95: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e5ed0)
Location: kernel/signal.c:4086
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810e5ed0-ffffffff810e6157: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81106ad0)
Location: kernel/signal.c:4088
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff81106ad0-ffffffff81106d57: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81112dc0)
Location: kernel/signal.c:4112
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff81112dc0-ffffffff8111309e: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111c7b0)
Location: kernel/signal.c:4123
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff8111c7b0-ffffffff8111ca8e: do_sigaction (STB_GLOBAL)
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
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010112a08)
Location: kernel/signal.c:3954
Inline: False
Direct callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__arm64_sys_rt_sigaction
  - kernel/signal.c:__arm64_sys_rt_sigaction
```
**Symbols:**

```
ffff800010112a08-ffff800010112bf8: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0369b80)
Location: kernel/signal.c:3954
Inline: False
Direct callers:
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__do_sys_sigaction
  - kernel/signal.c:__se_sys_rt_sigaction
  - kernel/signal.c:__se_sys_rt_sigaction
```
**Symbols:**

```
c0369b80-c0369ddc: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c00000000015a4b0)
Location: kernel/signal.c:3954
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_signal
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_sys_rt_sigaction
  - kernel/signal.c:__se_sys_rt_sigaction
```
**Symbols:**

```
c00000000015a4b0-c00000000015a7c0: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d1a3c)
Location: kernel/signal.c:3954
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigaction
  - kernel/signal.c:__se_sys_rt_sigaction
```
**Symbols:**

```
ffffffe0000d1a3c-ffffffe0000d1c2e: do_sigaction (STB_GLOBAL)
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
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0c30)
Location: kernel/signal.c:3954
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810b0c30-ffffffff810b0e7d: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f550)
Location: kernel/signal.c:3954
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff8109f550-ffffffff8109f797: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0190)
Location: kernel/signal.c:3954
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810b0190-ffffffff810b03dd: do_sigaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_sigaction(int sig, struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8460)
Location: kernel/signal.c:3954
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__ia32_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
  - kernel/signal.c:__x64_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810b8460-ffffffff810b86a4: do_sigaction (STB_GLOBAL)
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
