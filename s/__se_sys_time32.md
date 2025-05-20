# Function: <code>__se_sys_time32</code>

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
In kernel/time/time.c (ffffffff811266f0)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
In kernel/time/time.c (ffffffff81132690)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
In kernel/time/time.c (ffffffff81141990)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
In kernel/time/time.c (ffffffff8113dba0)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
In kernel/time/time.c (ffffffff8113edf0)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
In kernel/time/time.c (ffffffff81162280)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
In kernel/time/time.c (ffffffff811951f0)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
In kernel/time/time.c (ffffffff811d3000)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
In kernel/time/time.c (ffffffff811e72f0)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
In kernel/time/time.c (ffffffff811fd020)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
long int __se_sys_time32(long int tloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001faff0)
Location: kernel/time/time.c:105
Inline: False
```
**Symbols:**

```
c0000000001faff0-c0000000001fb0d8: __se_sys_time32 (STB_GLOBAL)
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
In kernel/time/time.c (ffffffff8112ae40)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
In kernel/time/time.c (ffffffff8111d6b0)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
In kernel/time/time.c (ffffffff81128b60)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
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
In kernel/time/time.c (ffffffff811351b0)
Location: kernel/time/time.c:105
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_time32
  - kernel/time/time.c:__x64_sys_time32
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
