# Function: <code>__se_sys_getrusage</code>

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
In kernel/sys.c (ffffffff810a83d5)
Location: kernel/sys.c:1803
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff810b10e5)
Location: kernel/sys.c:1804
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff810b6c25)
Location: kernel/sys.c:1805
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff810bd1e5)
Location: kernel/sys.c:1795
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff810c4925)
Location: kernel/sys.c:1811
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff810bfd25)
Location: kernel/sys.c:1812
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff810c1755)
Location: kernel/sys.c:1829
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff810d4245)
Location: kernel/sys.c:1838
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff810ecf45)
Location: kernel/sys.c:1850
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff8110e315)
Location: kernel/sys.c:1855
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff8111a575)
Location: kernel/sys.c:1873
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff81123fe5)
Location: kernel/sys.c:1886
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffff800010119dc8)
Location: kernel/sys.c:1795
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_getrusage
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_getrusage(long int who, long int ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036e1d0)
Location: kernel/sys.c:1795
Inline: False
```
**Symbols:**

```
c036e1d0-c036e2b8: __se_sys_getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_getrusage(long int who, long int ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c0000000001615f0)
Location: kernel/sys.c:1795
Inline: False
```
**Symbols:**

```
c0000000001615f0-c000000000161608: __se_sys_getrusage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_getrusage(long int who, long int ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d4940)
Location: kernel/sys.c:1795
Inline: False
```
**Symbols:**

```
ffffffe0000d4940-ffffffe0000d4974: __se_sys_getrusage (STB_GLOBAL)
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
In kernel/sys.c (ffffffff810b7555)
Location: kernel/sys.c:1795
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff810a5e95)
Location: kernel/sys.c:1795
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff810b6ab5)
Location: kernel/sys.c:1795
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
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
In kernel/sys.c (ffffffff810bee35)
Location: kernel/sys.c:1795
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getrusage
  - kernel/sys.c:__x64_sys_getrusage
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
