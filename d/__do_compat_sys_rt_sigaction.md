# Function: <code>__do_compat_sys_rt_sigaction</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a2a93)
Location: kernel/signal.c:3675
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab673)
Location: kernel/signal.c:4002
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0b63)
Location: kernel/signal.c:4250
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
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
In kernel/signal.c (ffffffff810b7133)
Location: kernel/signal.c:4258
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bf193)
Location: kernel/signal.c:4276
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_rt_sigaction(int sig, const struct compat_sigaction *act, struct compat_sigaction *oact, compat_size_t sigsetsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9fa0)
Location: kernel/signal.c:4313
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810b9fa0-ffffffff810ba103: __do_compat_sys_rt_sigaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_rt_sigaction(int sig, const struct compat_sigaction *act, struct compat_sigaction *oact, compat_size_t sigsetsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bb790)
Location: kernel/signal.c:4335
Inline: False
Direct callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
```
**Symbols:**

```
ffffffff810bb790-ffffffff810bb8f7: __do_compat_sys_rt_sigaction (STB_LOCAL)
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
In kernel/signal.c (ffffffff810ce5c3)
Location: kernel/signal.c:4419
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
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
In kernel/signal.c (ffffffff810e62a3)
Location: kernel/signal.c:4434
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
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
In kernel/signal.c (ffffffff81106ec3)
Location: kernel/signal.c:4436
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
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
In kernel/signal.c (ffffffff81113203)
Location: kernel/signal.c:4460
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
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
In kernel/signal.c (ffffffff8111cbf3)
Location: kernel/signal.c:4471
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
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
long int __do_compat_sys_rt_sigaction(int sig, const struct compat_sigaction *act, struct compat_sigaction *oact, compat_size_t sigsetsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010112d40)
Location: kernel/signal.c:4258
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigaction
```
**Symbols:**

```
ffff800010112d40-ffff8000101130bc: __do_compat_sys_rt_sigaction (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c00000000015a944)
Location: kernel/signal.c:4258
Inline: True
Inline callers:
  - kernel/signal.c:__se_compat_sys_rt_sigaction
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
In kernel/signal.c (ffffffff810b14a3)
Location: kernel/signal.c:4258
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
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
In kernel/signal.c (ffffffff8109fdc3)
Location: kernel/signal.c:4258
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
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
In kernel/signal.c (ffffffff810b0a03)
Location: kernel/signal.c:4258
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
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
In kernel/signal.c (ffffffff810b8cd3)
Location: kernel/signal.c:4258
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
