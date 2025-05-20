# Function: <code>dump_user_range</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dump_user_range(struct coredump_params *cprm, long unsigned int start, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813b95a0)
Location: fs/coredump.c:879
Inline: False
Direct callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
**Symbols:**

```
ffffffff813b95a0-ffffffff813b9694: dump_user_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dump_user_range(struct coredump_params *cprm, long unsigned int start, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813c0710)
Location: fs/coredump.c:913
Inline: False
Direct callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
**Symbols:**

```
ffffffff813c0710-ffffffff813c07f9: dump_user_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dump_user_range(struct coredump_params *cprm, long unsigned int start, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81410580)
Location: fs/coredump.c:920
Inline: False
Direct callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
**Symbols:**

```
ffffffff81410580-ffffffff81410662: dump_user_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dump_user_range(struct coredump_params *cprm, long unsigned int start, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81486070)
Location: fs/coredump.c:859
Inline: False
Direct callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
**Symbols:**

```
ffffffff81486070-ffffffff81486192: dump_user_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dump_user_range(struct coredump_params *cprm, long unsigned int start, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81519800)
Location: fs/coredump.c:898
Inline: False
Direct callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
**Symbols:**

```
ffffffff81519800-ffffffff81519a3b: dump_user_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dump_user_range(struct coredump_params *cprm, long unsigned int start, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff815510e0)
Location: fs/coredump.c:898
Inline: False
Direct callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
**Symbols:**

```
ffffffff815510e0-ffffffff8155132f: dump_user_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dump_user_range(struct coredump_params *cprm, long unsigned int start, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81586f70)
Location: fs/coredump.c:929
Inline: False
Direct callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
```
**Symbols:**

```
ffffffff81586f70-ffffffff8158722e: dump_user_range (STB_GLOBAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
