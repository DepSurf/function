# Function: <code>__se_sys_adjtimex_time32</code>

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
In kernel/time/time.c (ffffffff81127a85)
Location: kernel/time/time.c:351
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffffffff81133a25)
Location: kernel/time/time.c:351
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffffffff81142cb5)
Location: kernel/time/time.c:349
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffffffff8113eec5)
Location: kernel/time/time.c:349
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffffffff811400f5)
Location: kernel/time/time.c:349
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffffffff81163585)
Location: kernel/time/time.c:349
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffffffff811965e5)
Location: kernel/time/time.c:349
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffffffff811d45f5)
Location: kernel/time/time.c:349
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffffffff811e88e5)
Location: kernel/time/time.c:349
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffffffff811fe615)
Location: kernel/time/time.c:349
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffff80001019c0e8)
Location: kernel/time/time.c:351
Inline: True
Inline callers:
  - kernel/time/time.c:__arm64_sys_adjtimex_time32
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_adjtimex_time32(long int utp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e5cf8)
Location: kernel/time/time.c:351
Inline: False
```
**Symbols:**

```
c03e5cf8-c03e5d14: __se_sys_adjtimex_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_adjtimex_time32(long int utp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fbba0)
Location: kernel/time/time.c:351
Inline: False
```
**Symbols:**

```
c0000000001fbba0-c0000000001fbbb4: __se_sys_adjtimex_time32 (STB_GLOBAL)
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
In kernel/time/time.c (ffffffff8112c1d5)
Location: kernel/time/time.c:351
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffffffff8111ea45)
Location: kernel/time/time.c:351
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffffffff81129ef5)
Location: kernel/time/time.c:351
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
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
In kernel/time/time.c (ffffffff81136545)
Location: kernel/time/time.c:351
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_adjtimex_time32
  - kernel/time/time.c:__x64_sys_adjtimex_time32
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
