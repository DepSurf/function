# Function: <code>__do_compat_sys_sigaction</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction *act, struct compat_old_sigaction *oact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a26c0)
Location: kernel/signal.c:3758
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
**Symbols:**

```
ffffffff810a26c0-ffffffff810a2844: __do_compat_sys_sigaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction *act, struct compat_old_sigaction *oact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab290)
Location: kernel/signal.c:4085
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
**Symbols:**

```
ffffffff810ab290-ffffffff810ab41d: __do_compat_sys_sigaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction *act, struct compat_old_sigaction *oact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0780)
Location: kernel/signal.c:4333
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
**Symbols:**

```
ffffffff810b0780-ffffffff810b090d: __do_compat_sys_sigaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b72a9)
Location: kernel/signal.c:4341
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction *act, struct compat_old_sigaction *oact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bede0)
Location: kernel/signal.c:4359
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
**Symbols:**

```
ffffffff810bede0-ffffffff810bef3f: __do_compat_sys_sigaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction *act, struct compat_old_sigaction *oact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba150)
Location: kernel/signal.c:4396
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
**Symbols:**

```
ffffffff810ba150-ffffffff810ba2d9: __do_compat_sys_sigaction (STB_LOCAL)
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
In kernel/signal.c (ffffffff810bbcda)
Location: kernel/signal.c:4418
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
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
In kernel/signal.c (ffffffff810ce73a)
Location: kernel/signal.c:4502
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e6439)
Location: kernel/signal.c:4517
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81107069)
Location: kernel/signal.c:4519
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811133b9)
Location: kernel/signal.c:4543
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111cda9)
Location: kernel/signal.c:4554
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
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
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction *act, struct compat_old_sigaction *oact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff8000101130f8)
Location: kernel/signal.c:4341
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_compat_sys_sigaction
```
**Symbols:**

```
ffff8000101130f8-ffff8000101133fc: __do_compat_sys_sigaction (STB_LOCAL)
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
long int __do_compat_sys_sigaction(int sig, const struct compat_old_sigaction *act, struct compat_old_sigaction *oact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c00000000015adc0)
Location: kernel/signal.c:4341
Inline: False
Direct callers:
  - kernel/signal.c:__se_compat_sys_sigaction
```
**Symbols:**

```
c00000000015adc0-c00000000015b21c: __do_compat_sys_sigaction (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1619)
Location: kernel/signal.c:4341
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ff39)
Location: kernel/signal.c:4341
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0b79)
Location: kernel/signal.c:4341
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8e49)
Location: kernel/signal.c:4341
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
