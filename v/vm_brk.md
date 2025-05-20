# Function: <code>vm_brk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c6c20)
Location: mm/mmap.c:2822
Inline: False
Direct callers:
  - fs/binfmt_elf.c:set_brk
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff811c6c20-ffffffff811c6c9a: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e3360)
Location: mm/mmap.c:2756
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff811e3360-ffffffff811e33ee: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f3340)
Location: mm/mmap.c:2909
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff811f3340-ffffffff811f33ce: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fe210)
Location: mm/mmap.c:2975
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff811fe210-ffffffff811fe222: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812167c0)
Location: mm/mmap.c:3001
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff812167c0-ffffffff812167d2: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81237590)
Location: mm/mmap.c:3050
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff81237590-ffffffff812375a2: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124ae60)
Location: mm/mmap.c:3096
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff8124ae60-ffffffff8124ae72: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125d230)
Location: mm/mmap.c:3102
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff8125d230-ffffffff8125d242: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126ba00)
Location: mm/mmap.c:3108
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff8126ba00-ffffffff8126ba12: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129b840)
Location: mm/mmap.c:3119
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff8129b840-ffffffff8129b852: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a6a60)
Location: mm/mmap.c:3177
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff812a6a60-ffffffff812a6a72: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812aca10)
Location: mm/mmap.c:3148
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff812aca10-ffffffff812aca22: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ee170)
Location: mm/mmap.c:3134
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff812ee170-ffffffff812ee182: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81351560)
Location: mm/mmap.c:3134
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff81351560-ffffffff8135157c: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813cb0d0)
Location: mm/mmap.c:3073
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff813cb0d0-ffffffff813cb0ec: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813ff320)
Location: mm/mmap.c:3165
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff813ff320-ffffffff813ff33c: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010303138)
Location: mm/mmap.c:3108
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffff800010303138-ffff800010303170: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c05217d4)
Location: mm/mmap.c:3108
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
```
**Symbols:**

```
c05217d4-c05217f4: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cfaa0)
Location: mm/mmap.c:3108
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
c0000000003cfaa0-c0000000003cfab8: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020fd6a)
Location: mm/mmap.c:3108
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffe00020fd6a-ffffffe00020fd9e: vm_brk (STB_GLOBAL)
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
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81264050)
Location: mm/mmap.c:3108
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff81264050-ffffffff81264062: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81256470)
Location: mm/mmap.c:3108
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff81256470-ffffffff81256482: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81261df0)
Location: mm/mmap.c:3108
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff81261df0-ffffffff81261e02: vm_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vm_brk(long unsigned int addr, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812717b0)
Location: mm/mmap.c:3108
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_library
```
**Symbols:**

```
ffffffff812717b0-ffffffff812717c2: vm_brk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
