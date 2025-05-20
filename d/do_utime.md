# Function: <code>do_utime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_utime(char *filename, time_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81f5bc9e)
Location: init/initramfs.c:110
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff81f5bc9e-ffffffff81f5bd12: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_utime(char *filename, time_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81f83c42)
Location: init/initramfs.c:110
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff81f83c42-ffffffff81f83cb6: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_utime(char *filename, time_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81fbf257)
Location: init/initramfs.c:110
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff81fbf257-ffffffff81fbf2cb: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_utime(char *filename, time_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8209f3b6)
Location: init/initramfs.c:111
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8209f3b6-ffffffff8209f42f: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff826a53b6)
Location: init/initramfs.c:112
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff826a53b6-ffffffff826a542f: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff826ce64f)
Location: init/initramfs.c:112
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff826ce64f-ffffffff826ce6b7: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82884692)
Location: init/initramfs.c:102
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff82884692-ffffffff828846fa: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289b6e1)
Location: init/initramfs.c:102
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8289b6e1-ffffffff8289b749: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289e6c6)
Location: init/initramfs.c:102
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8289e6c6-ffffffff8289e72e: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff82cc4f35)
Location: init/initramfs.c:103
Inline: True
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff82cc4f35-ffffffff82cc4f95: do_utime.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff82fb0a62)
Location: init/initramfs.c:106
Inline: True
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff82fb0a62-ffffffff82fb0ab5: do_utime.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff831bab11)
Location: init/initramfs.c:118
Inline: True
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff831bab11-ffffffff831bab6c: do_utime.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff8329b01c)
Location: init/initramfs.c:119
Inline: True
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8329b01c-ffffffff8329b077: do_utime.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff83448a7e)
Location: init/initramfs.c:131
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff83448a7e-ffffffff83448ae7: do_utime (STB_LOCAL)
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
In init/initramfs.c (ffffffff83e638bd)
Location: init/initramfs.c:131
Inline: True
Inline callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
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
In init/initramfs.c (ffffffff83683edd)
Location: init/initramfs.c:125
Inline: True
Inline callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
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
In init/initramfs.c (ffffffff838b304b)
Location: init/initramfs.c:125
Inline: True
Inline callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_name
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
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffff800011432964)
Location: init/initramfs.c:102
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffff800011432964-ffff8000114329d4: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (c15029c4)
Location: init/initramfs.c:102
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
c15029c4-c1502a4c: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (c000000001346294)
Location: init/initramfs.c:102
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
c000000001346294-c000000001346318: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffe0000024b2)
Location: init/initramfs.c:102
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffe0000024b2-ffffffe0000024fe: do_utime (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8288c6c6)
Location: init/initramfs.c:102
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8288c6c6-ffffffff8288c72e: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8288a643)
Location: init/initramfs.c:102
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8288a643-ffffffff8288a6ab: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289f6c6)
Location: init/initramfs.c:102
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8289f6c6-ffffffff8289f72e: do_utime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_utime(char *filename, time64_t mtime);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289f6cb)
Location: init/initramfs.c:102
Inline: False
Direct callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:do_symlink
  - init/initramfs.c:do_copy
  - init/initramfs.c:do_name
```
**Symbols:**

```
ffffffff8289f6cb-ffffffff8289f733: do_utime (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>time_t mtime</code> ➡️ <code>time64_t mtime</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
