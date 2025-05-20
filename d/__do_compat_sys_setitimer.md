# Function: <code>__do_compat_sys_setitimer</code>

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
In kernel/time/itimer.c (ffffffff81123c02)
Location: kernel/time/itimer.c:318
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff8112f2d2)
Location: kernel/time/itimer.c:317
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff81139d42)
Location: kernel/time/itimer.c:317
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff811459c2)
Location: kernel/time/itimer.c:313
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff8115524d)
Location: kernel/time/itimer.c:382
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff811514bd)
Location: kernel/time/itimer.c:378
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff81152923)
Location: kernel/time/itimer.c:378
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff81176f23)
Location: kernel/time/itimer.c:378
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x64_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff811ac0b0)
Location: kernel/time/itimer.c:378
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff811ec3a0)
Location: kernel/time/itimer.c:378
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff81200ad0)
Location: kernel/time/itimer.c:378
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff81216f70)
Location: kernel/time/itimer.c:378
Inline: True
Inline callers:
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffff8000101b0254)
Location: kernel/time/itimer.c:313
Inline: True
Inline callers:
  - kernel/time/itimer.c:__arm64_compat_sys_setitimer
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
In kernel/time/itimer.c (c000000000214ca0)
Location: kernel/time/itimer.c:313
Inline: True
Inline callers:
  - kernel/time/itimer.c:__se_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff8113e172)
Location: kernel/time/itimer.c:313
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff81130c92)
Location: kernel/time/itimer.c:313
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff8113be92)
Location: kernel/time/itimer.c:313
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
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
In kernel/time/itimer.c (ffffffff81148972)
Location: kernel/time/itimer.c:313
Inline: True
Inline callers:
  - kernel/time/itimer.c:__x32_compat_sys_setitimer
  - kernel/time/itimer.c:__ia32_compat_sys_setitimer
```
</details>
</li>
</ul>

## Differences
