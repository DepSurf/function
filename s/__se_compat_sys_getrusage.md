# Function: <code>__se_compat_sys_getrusage</code>

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
In kernel/sys.c (ffffffff810a8495)
Location: kernel/sys.c:1816
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff810b11a5)
Location: kernel/sys.c:1817
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff810b6ce5)
Location: kernel/sys.c:1818
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff810bd2a5)
Location: kernel/sys.c:1808
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff810c49e5)
Location: kernel/sys.c:1824
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff810bfde5)
Location: kernel/sys.c:1825
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff810c1815)
Location: kernel/sys.c:1842
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff810d4305)
Location: kernel/sys.c:1851
Inline: True
Inline callers:
  - kernel/sys.c:__x64_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff810ed015)
Location: kernel/sys.c:1863
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff8110e405)
Location: kernel/sys.c:1868
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff8111a665)
Location: kernel/sys.c:1886
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff811240d5)
Location: kernel/sys.c:1899
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffff800010119e78)
Location: kernel/sys.c:1808
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_compat_sys_getrusage
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
long int __se_compat_sys_getrusage(long int who, long int ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c0000000001616c0)
Location: kernel/sys.c:1808
Inline: False
```
**Symbols:**

```
c0000000001616c0-c0000000001616d8: __se_compat_sys_getrusage (STB_GLOBAL)
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
In kernel/sys.c (ffffffff810b7615)
Location: kernel/sys.c:1808
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff810a5f55)
Location: kernel/sys.c:1808
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff810b6b75)
Location: kernel/sys.c:1808
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
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
In kernel/sys.c (ffffffff810beef5)
Location: kernel/sys.c:1808
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrusage
  - kernel/sys.c:__ia32_compat_sys_getrusage
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
