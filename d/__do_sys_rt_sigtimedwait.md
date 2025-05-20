# Function: <code>__do_sys_rt_sigtimedwait</code>

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
long int __do_sys_rt_sigtimedwait(const sigset_t *uthese, siginfo_t *uinfo, const struct timespec *uts, size_t sigsetsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a1ad0)
Location: kernel/signal.c:3099
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810a1ad0-ffffffff810a1bb4: __do_sys_rt_sigtimedwait (STB_LOCAL)
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
In kernel/signal.c (ffffffff810aa4ad)
Location: kernel/signal.c:3361
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff810af540)
Location: kernel/signal.c:3490
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff810b5b60)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff810b9460)
Location: kernel/signal.c:3513
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4710)
Location: kernel/signal.c:3533
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff810b6320)
Location: kernel/signal.c:3555
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff810c91b0)
Location: kernel/signal.c:3643
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff810e05d9)
Location: kernel/signal.c:3626
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff81105df7)
Location: kernel/signal.c:3628
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff811120d7)
Location: kernel/signal.c:3652
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff8111bac7)
Location: kernel/signal.c:3663
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0369348)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001599a4)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d1366)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
```
</details>
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
In kernel/signal.c (ffffffff810afed0)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff8109e7f0)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff810af430)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
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
In kernel/signal.c (ffffffff810b7700)
Location: kernel/signal.c:3495
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_rt_sigtimedwait
  - kernel/signal.c:__x64_sys_rt_sigtimedwait
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
