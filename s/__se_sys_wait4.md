# Function: <code>__se_sys_wait4</code>

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
In kernel/exit.c (ffffffff81094155)
Location: kernel/exit.c:1673
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff8109c4f5)
Location: kernel/exit.c:1675
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff810a0b15)
Location: kernel/exit.c:1679
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff810a70f5)
Location: kernel/exit.c:1625
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff810ae845)
Location: kernel/exit.c:1629
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff810a9e95)
Location: kernel/exit.c:1654
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff810aaec5)
Location: kernel/exit.c:1701
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff810bc9e5)
Location: kernel/exit.c:1701
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff810d37d5)
Location: kernel/exit.c:1705
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff810f24a5)
Location: kernel/exit.c:1799
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff810fe425)
Location: kernel/exit.c:1804
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff81107ad5)
Location: kernel/exit.c:1807
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffff8000100fe208)
Location: kernel/exit.c:1625
Inline: True
Inline callers:
  - kernel/exit.c:__arm64_sys_wait4
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_wait4(long int upid, long int stat_addr, long int options, long int ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c035b1c8)
Location: kernel/exit.c:1625
Inline: False
```
**Symbols:**

```
c035b1c8-c035b2a4: __se_sys_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_wait4(long int upid, long int stat_addr, long int options, long int ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000145220)
Location: kernel/exit.c:1625
Inline: False
```
**Symbols:**

```
c000000000145220-c00000000014523c: __se_sys_wait4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_wait4(long int upid, long int stat_addr, long int options, long int ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c66ee)
Location: kernel/exit.c:1625
Inline: False
```
**Symbols:**

```
ffffffe0000c66ee-ffffffe0000c6734: __se_sys_wait4 (STB_GLOBAL)
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
In kernel/exit.c (ffffffff810a0a15)
Location: kernel/exit.c:1625
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff8108f435)
Location: kernel/exit.c:1625
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff810a09c5)
Location: kernel/exit.c:1625
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
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
In kernel/exit.c (ffffffff810a8945)
Location: kernel/exit.c:1625
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_sys_wait4
  - kernel/exit.c:__x64_sys_wait4
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
