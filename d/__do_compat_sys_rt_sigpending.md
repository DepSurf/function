# Function: <code>__do_compat_sys_rt_sigpending</code>

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
In kernel/signal.c (ffffffff8109d277)
Location: kernel/signal.c:2791
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff810a5567)
Location: kernel/signal.c:2969
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff810aa249)
Location: kernel/signal.c:3098
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff810b0839)
Location: kernel/signal.c:3103
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff810b8a89)
Location: kernel/signal.c:3121
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff810b3d39)
Location: kernel/signal.c:3141
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff810b52c9)
Location: kernel/signal.c:3163
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff810c78a9)
Location: kernel/signal.c:3248
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff810de579)
Location: kernel/signal.c:3228
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff810feac9)
Location: kernel/signal.c:3230
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff8110ab39)
Location: kernel/signal.c:3254
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff811144d9)
Location: kernel/signal.c:3265
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffff80001010bfc8)
Location: kernel/signal.c:3103
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_compat_sys_rt_sigpending
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
In kernel/signal.c (c000000000152e84)
Location: kernel/signal.c:3103
Inline: True
Inline callers:
  - kernel/signal.c:__se_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff810aaba9)
Location: kernel/signal.c:3103
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff81099549)
Location: kernel/signal.c:3103
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff810aa109)
Location: kernel/signal.c:3103
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
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
In kernel/signal.c (ffffffff810b22e9)
Location: kernel/signal.c:3103
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_rt_sigpending
  - kernel/signal.c:__ia32_compat_sys_rt_sigpending
```
</details>
</li>
</ul>

## Differences
