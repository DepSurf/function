# Function: <code>__se_sys_signal</code>

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
In kernel/signal.c (ffffffff810a2924)
Location: kernel/signal.c:3826
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (ffffffff810ab4f4)
Location: kernel/signal.c:4153
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (ffffffff810b09e6)
Location: kernel/signal.c:4401
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (ffffffff810b6fb6)
Location: kernel/signal.c:4409
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (ffffffff810befa6)
Location: kernel/signal.c:4427
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (ffffffff810ba346)
Location: kernel/signal.c:4464
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (ffffffff810bbae0)
Location: kernel/signal.c:4486
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (ffffffff810ce3c0)
Location: kernel/signal.c:4570
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (0)
Location: kernel/signal.c:4585
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (0)
Location: kernel/signal.c:4587
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (0)
Location: kernel/signal.c:4611
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (0)
Location: kernel/signal.c:4622
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_signal(long int sig, long int handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c00000000015b240)
Location: kernel/signal.c:4409
Inline: False
```
**Symbols:**

```
c00000000015b240-c00000000015b2cc: __se_sys_signal (STB_GLOBAL)
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
In kernel/signal.c (ffffffff810b1326)
Location: kernel/signal.c:4409
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (ffffffff8109fc46)
Location: kernel/signal.c:4409
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (ffffffff810b0886)
Location: kernel/signal.c:4409
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
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
In kernel/signal.c (ffffffff810b8b56)
Location: kernel/signal.c:4409
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
