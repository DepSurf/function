# Function: <code>__se_sys_fadvise64</code>

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
In mm/fadvise.c (ffffffff81244a15)
Location: mm/fadvise.c:200
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
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
In mm/fadvise.c (ffffffff81206375)
Location: mm/fadvise.c:214
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
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
In mm/fadvise.c (ffffffff8121d6f5)
Location: mm/fadvise.c:214
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
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
In mm/fadvise.c (ffffffff8122b0d5)
Location: mm/fadvise.c:214
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
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
In mm/fadvise.c (0)
Location: mm/fadvise.c:212
Inline: True
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
In mm/fadvise.c (0)
Location: mm/fadvise.c:213
Inline: True
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
In mm/fadvise.c (0)
Location: mm/fadvise.c:213
Inline: True
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
In mm/fadvise.c (0)
Location: mm/fadvise.c:213
Inline: True
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
In mm/fadvise.c (0)
Location: mm/fadvise.c:212
Inline: True
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
In mm/fadvise.c (0)
Location: mm/fadvise.c:212
Inline: True
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
In mm/fadvise.c (0)
Location: mm/fadvise.c:212
Inline: True
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
In mm/fadvise.c (0)
Location: mm/fadvise.c:212
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_fadvise64(long int fd, long long int offset, long int len, long int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (c000000000371720)
Location: mm/fadvise.c:214
Inline: False
```
**Symbols:**

```
c000000000371720-c000000000371758: __se_sys_fadvise64 (STB_GLOBAL)
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
In mm/fadvise.c (ffffffff81223725)
Location: mm/fadvise.c:214
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
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
In mm/fadvise.c (ffffffff812168d5)
Location: mm/fadvise.c:214
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
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
In mm/fadvise.c (ffffffff812214c5)
Location: mm/fadvise.c:214
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
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
In mm/fadvise.c (ffffffff81230685)
Location: mm/fadvise.c:214
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64
  - mm/fadvise.c:__x64_sys_fadvise64
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
