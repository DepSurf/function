# Function: <code>create_zero_mask</code>

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
In fs/namei.c (ffffffff8121a07a)
Location: arch/x86/include/asm/word-at-a-time.h:58
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
```
```
In lib/string.c (ffffffff813f18c1)
Location: arch/x86/include/asm/word-at-a-time.h:58
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
```
In lib/strncpy_from_user.c (0)
Location: arch/x86/include/asm/word-at-a-time.h:58
Inline: True
```
```
In lib/strnlen_user.c (0)
Location: arch/x86/include/asm/word-at-a-time.h:58
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
In fs/namei.c (ffffffff81240717)
Location: arch/x86/include/asm/word-at-a-time.h:58
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/string.c (ffffffff8143824a)
Location: arch/x86/include/asm/word-at-a-time.h:58
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
```
In lib/strncpy_from_user.c (ffffffff81461ad2)
Location: arch/x86/include/asm/word-at-a-time.h:58
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81461cc1)
Location: arch/x86/include/asm/word-at-a-time.h:58
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
In fs/namei.c (ffffffff81252bf7)
Location: arch/x86/include/asm/word-at-a-time.h:58
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/string.c (ffffffff8145523a)
Location: arch/x86/include/asm/word-at-a-time.h:58
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
```
In lib/strncpy_from_user.c (ffffffff81480610)
Location: arch/x86/include/asm/word-at-a-time.h:58
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81480801)
Location: arch/x86/include/asm/word-at-a-time.h:58
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
In fs/namei.c (ffffffff8125edcc)
Location: arch/x86/include/asm/word-at-a-time.h:58
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff814898cb)
Location: arch/x86/include/asm/word-at-a-time.h:58
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814899da)
Location: arch/x86/include/asm/word-at-a-time.h:58
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff818f6d6a)
Location: arch/x86/include/asm/word-at-a-time.h:58
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
In fs/namei.c (ffffffff8128112c)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff814c5a1b)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814c5b27)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff8197d76a)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff812a7e3c)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff814f68f3)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814f6a1c)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff819d9c7b)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff812ba205)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8150ad3d)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8150ae63)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81a11e9b)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff812d80f5)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff81539474)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81539583)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81a81315)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff812e9c65)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8155a27e)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8155a39f)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81ab8962)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff81321e07)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff815e3ba7)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815e3cc2)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff815f35c8)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff8132d3c7)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8160807f)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff816081b1)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81617c58)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff81332eba)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff815eace7)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815eae5e)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff815fb2a8)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff8138064a)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff816571e7)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8165735f)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81668b78)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff814004ed)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8176ea24)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8176ebf2)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81782556)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff81489971)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8189e334)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8189e4ee)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff8203f3e6)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff814be8a1)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff818e08fc)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff818e0ac3)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff820bd859)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff814f0d21)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8192743c)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8192762c)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff821980d9)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffff800010391d40)
Location: arch/arm64/include/asm/word-at-a-time.h:30
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffff800010666c34)
Location: arch/arm64/include/asm/word-at-a-time.h:30
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:do_strncpy_from_user
```
```
In lib/strnlen_user.c (ffff800010666fa8)
Location: arch/arm64/include/asm/word-at-a-time.h:30
Inline: True
Inline callers:
  - lib/strnlen_user.c:do_strnlen_user
```
```
In lib/string.c (ffff800010d92d58)
Location: arch/arm64/include/asm/word-at-a-time.h:30
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
In fs/namei.c (c057845c)
Location: arch/arm/include/asm/word-at-a-time.h:29
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (c080f764)
Location: arch/arm/include/asm/word-at-a-time.h:29
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (c080f908)
Location: arch/arm/include/asm/word-at-a-time.h:29
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (c0e8f654)
Location: arch/arm/include/asm/word-at-a-time.h:29
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
In fs/namei.c (c000000000489c94)
Location: arch/powerpc/include/asm/word-at-a-time.h:77
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (c00000000081c7e0)
Location: arch/powerpc/include/asm/word-at-a-time.h:77
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (c00000000081ca00)
Location: arch/powerpc/include/asm/word-at-a-time.h:77
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (c000000000ed6dd4)
Location: arch/powerpc/include/asm/word-at-a-time.h:77
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
In lib/strncpy_from_user.c (ffffffe000492b56)
Location: arch/riscv/include/asm/word-at-a-time.h:34
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffe000492c68)
Location: arch/riscv/include/asm/word-at-a-time.h:34
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffe0008bd0f2)
Location: arch/riscv/include/asm/word-at-a-time.h:34
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
In fs/namei.c (ffffffff812e2245)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8155285e)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8155297f)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81a577b2)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff812d2e85)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff81542b3e)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81542c5f)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81a14892)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff812e0055)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8154e59e)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8154e6bf)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81ac3ba2)
Location: arch/x86/include/asm/word-at-a-time.h:59
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
In fs/namei.c (ffffffff812f18b5)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff815683ee)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8156850f)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81ad0072)
Location: arch/x86/include/asm/word-at-a-time.h:59
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
</ul>

## Differences
