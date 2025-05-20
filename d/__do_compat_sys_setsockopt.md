# Function: <code>__do_compat_sys_setsockopt</code>

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
In net/compat.c (ffffffff818c9515)
Location: net/compat.c:414
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
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
In net/compat.c (ffffffff818f43e5)
Location: net/compat.c:418
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
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
In net/compat.c (ffffffff81953e45)
Location: net/compat.c:394
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
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
In net/compat.c (ffffffff8198a395)
Location: net/compat.c:394
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
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
In net/compat.c (ffffffff81a62725)
Location: net/compat.c:413
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
```
</details>
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
In net/compat.c (ffff800010c32e50)
Location: net/compat.c:394
Inline: True
Inline callers:
  - net/compat.c:__arm64_compat_sys_setsockopt
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
In net/compat.c (c000000000d2be7c)
Location: net/compat.c:394
Inline: True
Inline callers:
  - net/compat.c:__se_compat_sys_setsockopt
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
In net/compat.c (ffffffff8192a205)
Location: net/compat.c:394
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
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
In net/compat.c (ffffffff818e3fb5)
Location: net/compat.c:394
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
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
In net/compat.c (ffffffff8197b395)
Location: net/compat.c:394
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
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
In net/compat.c (ffffffff8199d8e5)
Location: net/compat.c:394
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
```
</details>
</li>
</ul>

## Differences
