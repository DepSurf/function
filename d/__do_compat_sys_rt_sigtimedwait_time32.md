# Function: <code>__do_compat_sys_rt_sigtimedwait_time32</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afd30)
Location: kernel/signal.c:3587
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff810b6350)
Location: kernel/signal.c:3592
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff810b9620)
Location: kernel/signal.c:3610
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff810b48d0)
Location: kernel/signal.c:3630
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff810b65a0)
Location: kernel/signal.c:3652
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff810c9430)
Location: kernel/signal.c:3740
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff810e5ab7)
Location: kernel/signal.c:3723
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff81106657)
Location: kernel/signal.c:3725
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff81112947)
Location: kernel/signal.c:3749
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff8111c337)
Location: kernel/signal.c:3760
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffff8000101125ac)
Location: kernel/signal.c:3592
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (c00000000015a058)
Location: kernel/signal.c:3592
Inline: True
Inline callers:
  - kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff810b06c0)
Location: kernel/signal.c:3592
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff8109efe0)
Location: kernel/signal.c:3592
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff810afc20)
Location: kernel/signal.c:3592
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
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
In kernel/signal.c (ffffffff810b7ef0)
Location: kernel/signal.c:3592
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
```
</details>
</li>
</ul>

## Differences
