# Function: <code>__se_compat_sys_sigpending</code>

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
In kernel/signal.c (ffffffff8109d217)
Location: kernel/signal.c:3577
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff810a5507)
Location: kernel/signal.c:3906
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff810aa1e7)
Location: kernel/signal.c:4154
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff810b07d7)
Location: kernel/signal.c:4162
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff810b8a27)
Location: kernel/signal.c:4180
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff810b3cd7)
Location: kernel/signal.c:4217
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff810b5267)
Location: kernel/signal.c:4239
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff810c7847)
Location: kernel/signal.c:4323
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff810dd667)
Location: kernel/signal.c:4338
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff810fd717)
Location: kernel/signal.c:4340
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff81109787)
Location: kernel/signal.c:4364
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff81113127)
Location: kernel/signal.c:4375
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffff80001010bbd0)
Location: kernel/signal.c:4162
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_compat_sys_sigpending
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
long int __se_compat_sys_sigpending(long int set32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000152ff0)
Location: kernel/signal.c:4162
Inline: False
```
**Symbols:**

```
c000000000152ff0-c0000000001530e0: __se_compat_sys_sigpending (STB_GLOBAL)
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
In kernel/signal.c (ffffffff810aab47)
Location: kernel/signal.c:4162
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff810994e7)
Location: kernel/signal.c:4162
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff810aa0a7)
Location: kernel/signal.c:4162
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
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
In kernel/signal.c (ffffffff810b1527)
Location: kernel/signal.c:4162
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigpending
  - kernel/signal.c:__ia32_compat_sys_sigpending
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
