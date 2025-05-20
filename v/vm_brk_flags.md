# Function: <code>vm_brk_flags</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fe130)
Location: mm/mmap.c:2955
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff811fe130-ffffffff811fe210: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int len, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812166e0)
Location: mm/mmap.c:2981
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff812166e0-ffffffff812167c0: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81237470)
Location: mm/mmap.c:3023
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff81237470-ffffffff81237588: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124ad40)
Location: mm/mmap.c:3069
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff8124ad40-ffffffff8124ae58: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125d100)
Location: mm/mmap.c:3075
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff8125d100-ffffffff8125d223: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126b8d0)
Location: mm/mmap.c:3081
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff8126b8d0-ffffffff8126b9f3: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129b710)
Location: mm/mmap.c:3092
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff8129b710-ffffffff8129b833: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a68f0)
Location: mm/mmap.c:3150
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff812a68f0-ffffffff812a6a5f: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812ac8a0)
Location: mm/mmap.c:3121
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff812ac8a0-ffffffff812aca0c: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812edff0)
Location: mm/mmap.c:3107
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff812edff0-ffffffff812ee16d: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813513e0)
Location: mm/mmap.c:3107
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff813513e0-ffffffff81351554: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813cae60)
Location: mm/mmap.c:3026
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff813cae60-ffffffff813cb0b4: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff813ff0b0)
Location: mm/mmap.c:3118
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff813ff0b0-ffffffff813ff301: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8142b600)
Location: mm/mmap.c:3212
Inline: False
Direct callers:
  - fs/binfmt_elf.c:elf_load
  - fs/compat_binfmt_elf.c:elf_load
```
**Symbols:**

```
ffffffff8142b600-ffffffff8142b855: vm_brk_flags (STB_GLOBAL)
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010303028)
Location: mm/mmap.c:3081
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffff800010303028-ffff800010303134: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c05216b8)
Location: mm/mmap.c:3081
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
```
**Symbols:**

```
c05216b8-c05217d4: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003cf8f0)
Location: mm/mmap.c:3081
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
c0000000003cf8f0-c0000000003cfa94: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe00020fca8)
Location: mm/mmap.c:3081
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffe00020fca8-ffffffe00020fd6a: vm_brk_flags (STB_GLOBAL)
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
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81263f20)
Location: mm/mmap.c:3081
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff81263f20-ffffffff81264043: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81256340)
Location: mm/mmap.c:3081
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff81256340-ffffffff81256463: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81261cc0)
Location: mm/mmap.c:3081
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff81261cc0-ffffffff81261de3: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vm_brk_flags(long unsigned int addr, long unsigned int request, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81271680)
Location: mm/mmap.c:3081
Inline: False
Direct callers:
  - mm/mmap.c:vm_brk
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:set_brk
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:set_brk
```
**Symbols:**

```
ffffffff81271680-ffffffff812717a3: vm_brk_flags (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int request</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int len</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
