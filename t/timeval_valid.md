# Function: <code>timeval_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eb453)
Location: include/linux/time.h:113
Inline: True
Inline callers:
  - kernel/time/time.c:SyS_settimeofday
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f2107)
Location: include/linux/time.h:113
Inline: True
Inline callers:
  - kernel/time/time.c:SyS_settimeofday
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f9287)
Location: include/linux/time.h:113
Inline: True
Inline callers:
  - kernel/time/time.c:SyS_settimeofday
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fb62f)
Location: include/linux/time.h:122
Inline: True
Inline callers:
  - kernel/time/time.c:SyS_settimeofday
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105f7f)
Location: include/linux/time32.h:185
Inline: True
Inline callers:
  - kernel/time/time.c:SyS_settimeofday
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81111397)
Location: include/linux/time32.h:173
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
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
In kernel/time/time.c (ffffffff8111caa7)
Location: include/linux/time32.h:155
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
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
In kernel/time/time.c (ffffffff811275d0)
Location: include/linux/time32.h:185
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
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
In kernel/time/time.c (ffffffff81133570)
Location: include/linux/time32.h:185
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/time/time.c (ffff80001019bc60)
Location: include/linux/time32.h:185
Inline: True
Inline callers:
  - kernel/time/time.c:__arm64_compat_sys_settimeofday
  - kernel/time/time.c:__arm64_sys_settimeofday
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
In kernel/time/time.c (c03e5858)
Location: include/linux/time32.h:185
Inline: True
Inline callers:
  - kernel/time/time.c:__se_sys_settimeofday
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
In kernel/time/time.c (c0000000001fb714)
Location: include/linux/time32.h:185
Inline: True
Inline callers:
  - kernel/time/time.c:__se_compat_sys_settimeofday
  - kernel/time/time.c:__se_sys_settimeofday
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
In kernel/time/time.c (ffffffe00012ab84)
Location: include/linux/time32.h:185
Inline: True
Inline callers:
  - kernel/time/time.c:__se_sys_settimeofday
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
In kernel/time/time.c (ffffffff8112bd20)
Location: include/linux/time32.h:185
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
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
In kernel/time/time.c (ffffffff8111e590)
Location: include/linux/time32.h:185
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
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
In kernel/time/time.c (ffffffff81129a40)
Location: include/linux/time32.h:185
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
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
In kernel/time/time.c (ffffffff81136090)
Location: include/linux/time32.h:185
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_compat_sys_settimeofday
  - kernel/time/time.c:__ia32_sys_settimeofday
  - kernel/time/time.c:__x64_sys_settimeofday
```
</details>
</li>
</ul>

## Differences
