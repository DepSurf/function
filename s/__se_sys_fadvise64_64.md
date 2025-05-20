# Function: <code>__se_sys_fadvise64_64</code>

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
In mm/fadvise.c (ffffffff812449c5)
Location: mm/fadvise.c:193
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
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
In mm/fadvise.c (ffffffff81206325)
Location: mm/fadvise.c:207
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
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
In mm/fadvise.c (ffffffff8121d6a5)
Location: mm/fadvise.c:207
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
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
In mm/fadvise.c (ffffffff8122b085)
Location: mm/fadvise.c:207
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
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
In mm/fadvise.c (ffffffff81257e25)
Location: mm/fadvise.c:205
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
In mm/fadvise.c (ffffffff812626f5)
Location: mm/fadvise.c:206
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
In mm/fadvise.c (ffffffff81267185)
Location: mm/fadvise.c:206
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
In mm/fadvise.c (ffffffff812a3bc5)
Location: mm/fadvise.c:206
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
In mm/fadvise.c (ffffffff812fbb05)
Location: mm/fadvise.c:205
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
In mm/fadvise.c (ffffffff81365c95)
Location: mm/fadvise.c:205
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
In mm/fadvise.c (ffffffff81398175)
Location: mm/fadvise.c:205
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
In mm/fadvise.c (ffffffff813c1fa5)
Location: mm/fadvise.c:205
Inline: True
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
In mm/fadvise.c (ffff8000102b9390)
Location: mm/fadvise.c:207
Inline: True
Inline callers:
  - mm/fadvise.c:__arm64_sys_fadvise64_64
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_fadvise64_64(long int fd, long long int offset, long long int len, long int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (c04e5b44)
Location: mm/fadvise.c:207
Inline: False
```
**Symbols:**

```
c04e5b44-c04e5b78: __se_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_fadvise64_64(long int fd, long long int offset, long long int len, long int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (c0000000003716e0)
Location: mm/fadvise.c:207
Inline: False
```
**Symbols:**

```
c0000000003716e0-c000000000371718: __se_sys_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_fadvise64_64(long int fd, long long int offset, long long int len, long int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/fadvise.c (ffffffe0001dcf12)
Location: mm/fadvise.c:207
Inline: False
```
**Symbols:**

```
ffffffe0001dcf12-ffffffe0001dcf58: __se_sys_fadvise64_64 (STB_GLOBAL)
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
In mm/fadvise.c (ffffffff812236d5)
Location: mm/fadvise.c:207
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
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
In mm/fadvise.c (ffffffff81216885)
Location: mm/fadvise.c:207
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
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
In mm/fadvise.c (ffffffff81221475)
Location: mm/fadvise.c:207
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
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
In mm/fadvise.c (ffffffff81230635)
Location: mm/fadvise.c:207
Inline: True
Inline callers:
  - mm/fadvise.c:__ia32_sys_fadvise64_64
  - mm/fadvise.c:__x64_sys_fadvise64_64
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
