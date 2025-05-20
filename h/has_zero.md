# Function: <code>has_zero</code>

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
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
```
```
In lib/string.c (ffffffff813f17e8)
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
```
In lib/strncpy_from_user.c (ffffffff81419c50)
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81419d6a)
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strlen_user
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
In fs/namei.c (ffffffff81240663)
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/string.c (ffffffff81438178)
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
```
In lib/strncpy_from_user.c (ffffffff81461a37)
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81461c6c)
Location: arch/x86/include/asm/word-at-a-time.h:46
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
In fs/namei.c (ffffffff81252b43)
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/string.c (ffffffff81455168)
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
```
In lib/strncpy_from_user.c (ffffffff81480573)
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814807ac)
Location: arch/x86/include/asm/word-at-a-time.h:46
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
In fs/namei.c (ffffffff8125ed28)
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff81489816)
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8148996a)
Location: arch/x86/include/asm/word-at-a-time.h:46
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff818f6c78)
Location: arch/x86/include/asm/word-at-a-time.h:46
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
In fs/namei.c (ffffffff81281088)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff814c5966)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814c5aba)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff8197d678)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff812a7e07)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:link_path_walk
  - fs/namei.c:link_path_walk
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff814f6875)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff814f69d0)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff819d9b92)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff812ba1f3)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8150aca2)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8150ae11)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81a11db2)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff812d80e3)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff815393f4)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81539546)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81a812ff)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff812e9c53)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8155a20e)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8155a35f)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81ab894c)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff81321df5)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff815e3b3a)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815e3c6a)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff815f35b2)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff8132d3b5)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff81607ff2)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8160816d)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81617c42)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff81332ea8)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff815eacd1)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815eadf1)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff815fb292)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff81380638)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff816571d1)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff816572f2)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81668b62)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff814004d7)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8176ea12)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8176eb58)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81782544)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff81489912)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8189e322)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8189e48d)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff8203f3d4)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff814be842)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff818e08ea)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff818e0a62)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff820bd847)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff814f0cc2)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8192742a)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81927590)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff821980c7)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffff800010391d20)
Location: arch/arm64/include/asm/word-at-a-time.h:20
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffff800010666b90)
Location: arch/arm64/include/asm/word-at-a-time.h:20
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:do_strncpy_from_user
```
```
In lib/strnlen_user.c (ffff800010666e64)
Location: arch/arm64/include/asm/word-at-a-time.h:20
Inline: True
Inline callers:
  - lib/strnlen_user.c:do_strnlen_user
```
```
In lib/string.c (ffff800010d92d44)
Location: arch/arm64/include/asm/word-at-a-time.h:20
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
In fs/namei.c (c0578440)
Location: arch/arm/include/asm/word-at-a-time.h:19
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (c080f67c)
Location: arch/arm/include/asm/word-at-a-time.h:19
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (c080f898)
Location: arch/arm/include/asm/word-at-a-time.h:19
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (c0e8f644)
Location: arch/arm/include/asm/word-at-a-time.h:19
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
In fs/namei.c (c000000000489c40)
Location: arch/powerpc/include/asm/word-at-a-time.h:60
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (c00000000081c680)
Location: arch/powerpc/include/asm/word-at-a-time.h:60
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (c00000000081c954)
Location: arch/powerpc/include/asm/word-at-a-time.h:60
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (c000000000ed6dc4)
Location: arch/powerpc/include/asm/word-at-a-time.h:60
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
In lib/strncpy_from_user.c (ffffffe000492a92)
Location: arch/riscv/include/asm/word-at-a-time.h:20
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffe000492c18)
Location: arch/riscv/include/asm/word-at-a-time.h:20
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffe0008bd0e0)
Location: arch/riscv/include/asm/word-at-a-time.h:20
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
In fs/namei.c (ffffffff812e2233)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff815527ee)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8155293f)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81a5779c)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff812d2e73)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff81542ace)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff81542c1f)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81a1487c)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff812e0043)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8154e52e)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff8154e67f)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81ac3b8c)
Location: arch/x86/include/asm/word-at-a-time.h:47
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
In fs/namei.c (ffffffff812f18a3)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In lib/strncpy_from_user.c (ffffffff8156837e)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff815684cf)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In lib/string.c (ffffffff81ad005c)
Location: arch/x86/include/asm/word-at-a-time.h:47
Inline: True
Inline callers:
  - lib/string.c:strscpy
```
</details>
</li>
</ul>

## Differences
