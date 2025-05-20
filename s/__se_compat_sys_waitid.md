# Function: <code>__se_compat_sys_waitid</code>

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
In kernel/exit.c (ffffffff81093055)
Location: kernel/exit.c:1715
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff8109b305)
Location: kernel/exit.c:1717
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff8109f965)
Location: kernel/exit.c:1721
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff810a5fe5)
Location: kernel/exit.c:1667
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff810adba5)
Location: kernel/exit.c:1671
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff810a9235)
Location: kernel/exit.c:1696
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff810aa275)
Location: kernel/exit.c:1743
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff810bbdb5)
Location: kernel/exit.c:1743
Inline: True
Inline callers:
  - kernel/exit.c:__x64_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff810d28a5)
Location: kernel/exit.c:1747
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff810f1375)
Location: kernel/exit.c:1841
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff810fd2c5)
Location: kernel/exit.c:1846
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff81107805)
Location: kernel/exit.c:1849
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffff8000100fceb8)
Location: kernel/exit.c:1667
Inline: True
Inline callers:
  - kernel/exit.c:__arm64_compat_sys_waitid
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
long int __se_compat_sys_waitid(long int which, long int pid, long int infop, long int options, long int uru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000143c50)
Location: kernel/exit.c:1667
Inline: False
```
**Symbols:**

```
c000000000143c50-c000000000143c70: __se_compat_sys_waitid (STB_GLOBAL)
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
In kernel/exit.c (ffffffff8109f905)
Location: kernel/exit.c:1667
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff8108e335)
Location: kernel/exit.c:1667
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff8109f8b5)
Location: kernel/exit.c:1667
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
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
In kernel/exit.c (ffffffff810a7815)
Location: kernel/exit.c:1667
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_waitid
  - kernel/exit.c:__ia32_compat_sys_waitid
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
