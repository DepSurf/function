# Function: <code>__do_compat_sys_gettimeofday</code>

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
In kernel/time/time.c (ffffffff81111187)
Location: kernel/time/time.c:228
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff8111c849)
Location: kernel/time/time.c:225
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff81127179)
Location: kernel/time/time.c:225
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff81133119)
Location: kernel/time/time.c:225
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff811422d9)
Location: kernel/time/time.c:224
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff8113e4e9)
Location: kernel/time/time.c:224
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff8113f739)
Location: kernel/time/time.c:224
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff81162bc9)
Location: kernel/time/time.c:224
Inline: True
Inline callers:
  - kernel/time/time.c:__x64_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff81195539)
Location: kernel/time/time.c:224
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff811d33a9)
Location: kernel/time/time.c:224
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff811e7699)
Location: kernel/time/time.c:224
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff811fd3c9)
Location: kernel/time/time.c:224
Inline: True
Inline callers:
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffff80001019b630)
Location: kernel/time/time.c:225
Inline: True
Inline callers:
  - kernel/time/time.c:__arm64_compat_sys_gettimeofday
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
In kernel/time/time.c (c0000000001fb118)
Location: kernel/time/time.c:225
Inline: True
Inline callers:
  - kernel/time/time.c:__se_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff8112b8c9)
Location: kernel/time/time.c:225
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff8111e139)
Location: kernel/time/time.c:225
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff811295e9)
Location: kernel/time/time.c:225
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
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
In kernel/time/time.c (ffffffff81135c39)
Location: kernel/time/time.c:225
Inline: True
Inline callers:
  - kernel/time/time.c:__x32_compat_sys_gettimeofday
  - kernel/time/time.c:__ia32_compat_sys_gettimeofday
```
</details>
</li>
</ul>

## Differences
