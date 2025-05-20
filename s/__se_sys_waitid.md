# Function: <code>__se_sys_waitid</code>

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
In kernel/exit.c (ffffffff81092e95)
Location: kernel/exit.c:1596
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff8109b165)
Location: kernel/exit.c:1599
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff8109f7c5)
Location: kernel/exit.c:1603
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff810a5e45)
Location: kernel/exit.c:1549
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff810ad9e5)
Location: kernel/exit.c:1553
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff810a9065)
Location: kernel/exit.c:1562
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff810aa0f5)
Location: kernel/exit.c:1609
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff810bbc35)
Location: kernel/exit.c:1609
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff810d2735)
Location: kernel/exit.c:1613
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff810f11e5)
Location: kernel/exit.c:1707
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff810fd155)
Location: kernel/exit.c:1712
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff81107695)
Location: kernel/exit.c:1715
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffff8000100fc660)
Location: kernel/exit.c:1549
Inline: True
Inline callers:
  - kernel/exit.c:__arm64_sys_waitid
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_waitid(long int which, long int upid, long int infop, long int options, long int ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c035b038)
Location: kernel/exit.c:1549
Inline: False
```
**Symbols:**

```
c035b038-c035b064: __se_sys_waitid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_waitid(long int which, long int upid, long int infop, long int options, long int ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000143860)
Location: kernel/exit.c:1549
Inline: False
```
**Symbols:**

```
c000000000143860-c000000000143880: __se_sys_waitid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_waitid(long int which, long int upid, long int infop, long int options, long int ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c653e)
Location: kernel/exit.c:1549
Inline: False
```
**Symbols:**

```
ffffffe0000c653e-ffffffe0000c658e: __se_sys_waitid (STB_GLOBAL)
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
In kernel/exit.c (ffffffff8109f765)
Location: kernel/exit.c:1549
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff8108e195)
Location: kernel/exit.c:1549
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff8109f715)
Location: kernel/exit.c:1549
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
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
In kernel/exit.c (ffffffff810a7675)
Location: kernel/exit.c:1549
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_waitid
  - kernel/exit.c:__x64_sys_waitid
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
