# Function: <code>__se_sys_sigpending</code>

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
In kernel/signal.c (ffffffff8109d145)
Location: kernel/signal.c:3562
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff810a5434)
Location: kernel/signal.c:3890
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff810aa116)
Location: kernel/signal.c:4138
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff810b0706)
Location: kernel/signal.c:4146
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff810b8956)
Location: kernel/signal.c:4164
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff810b3c06)
Location: kernel/signal.c:4201
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff810b51a6)
Location: kernel/signal.c:4223
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff810c7786)
Location: kernel/signal.c:4307
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff810ddc44)
Location: kernel/signal.c:4322
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff810fddb4)
Location: kernel/signal.c:4324
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff81109e24)
Location: kernel/signal.c:4348
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff811137c4)
Location: kernel/signal.c:4359
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffff80001010bdc8)
Location: kernel/signal.c:4146
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_sigpending
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_sigpending(long int uset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036a3d4)
Location: kernel/signal.c:4146
Inline: False
```
**Symbols:**

```
c036a3d4-c036a490: __se_sys_sigpending (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_sigpending(long int uset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000152f60)
Location: kernel/signal.c:4146
Inline: False
```
**Symbols:**

```
c000000000152f60-c000000000152fec: __se_sys_sigpending (STB_GLOBAL)
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
In kernel/signal.c (ffffffff810aaa76)
Location: kernel/signal.c:4146
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff81099416)
Location: kernel/signal.c:4146
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff810a9fd6)
Location: kernel/signal.c:4146
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
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
In kernel/signal.c (ffffffff810b1746)
Location: kernel/signal.c:4146
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_sigpending
  - kernel/signal.c:__x64_sys_sigpending
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
