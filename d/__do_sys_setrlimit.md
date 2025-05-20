# Function: <code>__do_sys_setrlimit</code>

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
In kernel/sys.c (ffffffff810a7a9d)
Location: kernel/sys.c:1677
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff810b07ad)
Location: kernel/sys.c:1678
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff810b624d)
Location: kernel/sys.c:1678
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff810bc80d)
Location: kernel/sys.c:1668
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff810c419d)
Location: kernel/sys.c:1684
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff810bf59d)
Location: kernel/sys.c:1685
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff810c0fce)
Location: kernel/sys.c:1702
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff810d3abe)
Location: kernel/sys.c:1711
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff810e90dc)
Location: kernel/sys.c:1723
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff8110999c)
Location: kernel/sys.c:1728
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff81115d2c)
Location: kernel/sys.c:1746
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff8111f71c)
Location: kernel/sys.c:1746
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffff800010119708)
Location: kernel/sys.c:1668
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_setrlimit
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
In kernel/sys.c (c036dd1c)
Location: kernel/sys.c:1668
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setrlimit
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
In kernel/sys.c (c000000000161038)
Location: kernel/sys.c:1668
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setrlimit
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
In kernel/sys.c (ffffffe0000d45b2)
Location: kernel/sys.c:1668
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setrlimit
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
In kernel/sys.c (ffffffff810b6b7d)
Location: kernel/sys.c:1668
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff810a54bd)
Location: kernel/sys.c:1668
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff810b60dd)
Location: kernel/sys.c:1668
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
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
In kernel/sys.c (ffffffff810be44d)
Location: kernel/sys.c:1668
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setrlimit
  - kernel/sys.c:__x64_sys_setrlimit
```
</details>
</li>
</ul>

## Differences
