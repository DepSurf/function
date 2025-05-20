# Function: <code>find_zero</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (0)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
```
```
In lib/string.c (0)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
```
```
In lib/strncpy_from_user.c (0)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
```
```
In lib/strnlen_user.c (0)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8124071e)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/string.c (ffffffff81438255)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
```
In lib/strncpy_from_user.c (ffffffff81461adc)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81461cce)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - lib/strnlen_user.c:strlen_user
  - lib/strnlen_user.c:strnlen_user
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81252bfe)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/string.c (ffffffff81455245)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
```
In lib/strncpy_from_user.c (ffffffff8148061a)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8148080e)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - lib/strnlen_user.c:strlen_user
  - lib/strnlen_user.c:strnlen_user
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125edd3)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff814898d5)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814899e7)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff818f6d75)
Location: arch/x86/include/asm/word-at-a-time.h:67
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81281133)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff814c5a25)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814c5b34)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff8197d775)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a7e54)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff814f68f3)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814f6a1c)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff819d9c9f)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ba228)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8150ad3d)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8150ae63)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81a11ebf)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8118)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff81539474)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81539583)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81a81337)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9c88)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8155a27e)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8155a39f)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81ab8984)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321e20)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff815e3ba7)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815e3cc2)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff815f35dc)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132d3e0)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff81608093)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff816081b1)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81617c6c)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332ed3)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff815eacfb)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815eae5e)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff815fb2bc)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81380663)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff816571fb)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8165735f)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81668b8c)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81400506)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8176ea3a)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8176ebf2)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff8178256b)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81489980)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8189e34a)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8189e4ee)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff8203f3fb)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/namei.c (ffffffff814be8b0)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff818e0911)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff818e0ac3)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff820bd86e)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In fs/namei.c (ffffffff814f0d30)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff81927451)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8192762c)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff821980ee)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010391d54)
Location: arch/arm64/include/asm/word-at-a-time.h:36
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffff800010666c44)
Location: arch/arm64/include/asm/word-at-a-time.h:36
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:do_strncpy_from_user
```
```
In lib/strnlen_user.c (ffff800010666fb8)
Location: arch/arm64/include/asm/word-at-a-time.h:36
Inline: True
Inline callers:
  - lib/strnlen_user.c:do_strnlen_user
```
```
In lib/string.c (ffff800010d92d70)
Location: arch/arm64/include/asm/word-at-a-time.h:36
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0578478)
Location: arch/arm/include/asm/word-at-a-time.h:35
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (c080f764)
Location: arch/arm/include/asm/word-at-a-time.h:35
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (c080f908)
Location: arch/arm/include/asm/word-at-a-time.h:35
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (c0e8f670)
Location: arch/arm/include/asm/word-at-a-time.h:35
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000489ca8)
Location: arch/powerpc/include/asm/word-at-a-time.h:91
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (c00000000081c7ec)
Location: arch/powerpc/include/asm/word-at-a-time.h:91
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (c00000000081ca10)
Location: arch/powerpc/include/asm/word-at-a-time.h:91
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (c000000000ed6df8)
Location: arch/powerpc/include/asm/word-at-a-time.h:91
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/strncpy_from_user.c (ffffffe000492b62)
Location: arch/riscv/include/asm/word-at-a-time.h:40
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffe000492c74)
Location: arch/riscv/include/asm/word-at-a-time.h:40
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffe0008bd102)
Location: arch/riscv/include/asm/word-at-a-time.h:40
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e2268)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8155285e)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8155297f)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81a577d4)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d2ea8)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff81542b3e)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81542c5f)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81a148b4)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e0078)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8154e59e)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8154e6bf)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81ac3bc4)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f18d8)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff815683ee)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8156850f)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81ad0094)
Location: arch/x86/include/asm/word-at-a-time.h:68
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
</ul>

## Differences
