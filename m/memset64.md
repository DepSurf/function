# Function: <code>memset64</code>

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
In mm/zswap.c (ffffffff8124fd16)
Location: arch/x86/include/asm/string_64.h:79
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff81264286)
Location: arch/x86/include/asm/string_64.h:61
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff8127f1dd)
Location: arch/x86/include/asm/string_64.h:46
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff8128ec3d)
Location: arch/x86/include/asm/string_64.h:46
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff812c1a6e)
Location: arch/x86/include/asm/string_64.h:46
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff812cd639)
Location: arch/x86/include/asm/string_64.h:46
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff812d40b8)
Location: arch/x86/include/asm/string_64.h:46
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff81319d82)
Location: arch/x86/include/asm/string_64.h:46
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff8138567a)
Location: arch/x86/include/asm/string_64.h:46
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff814033e3)
Location: arch/x86/include/asm/string_64.h:61
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff814368aa)
Location: arch/x86/include/asm/string_64.h:55
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
```
```
In drivers/video/fbdev/core/sysfillrect.c (ffffffff81991dbc)
Location: arch/x86/include/asm/string_64.h:55
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff814713c7)
Location: arch/x86/include/asm/string_64.h:55
Inline: True
Inline callers:
  - mm/zswap.c:zswap_load
```
```
In drivers/video/fbdev/core/sysfillrect.c (ffffffff819dc2ec)
Location: arch/x86/include/asm/string_64.h:55
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *memset64(uint64_t *s, uint64_t v, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d92ca8)
Location: lib/string.c:806
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
```
**Symbols:**

```
ffff800010d92ca8-ffff800010d92cc4: memset64 (STB_GLOBAL)
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
In mm/zswap.c (c0000000004028c0)
Location: arch/powerpc/include/asm/string.h:73
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *memset64(uint64_t *s, uint64_t v, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bcd90)
Location: lib/string.c:806
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_load
```
**Symbols:**

```
ffffffe0008bcd90-ffffffe0008bcdb0: memset64 (STB_GLOBAL)
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
In mm/zswap.c (ffffffff8128721d)
Location: arch/x86/include/asm/string_64.h:46
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff8127907d)
Location: arch/x86/include/asm/string_64.h:46
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff8128502d)
Location: arch/x86/include/asm/string_64.h:46
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
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
In mm/zswap.c (ffffffff812950b7)
Location: arch/x86/include/asm/string_64.h:46
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
