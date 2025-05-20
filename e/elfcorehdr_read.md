# Function: <code>elfcorehdr_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (0)
Location: fs/proc/vmcore.c:144
Inline: True
```
**Symbols:**

```
ffffffff81287890-ffffffff812878a0: elfcorehdr_read (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812b4ba0)
Location: fs/proc/vmcore.c:144
Inline: True
```
**Symbols:**

```
ffffffff812b4ba0-ffffffff812b4bba: elfcorehdr_read (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812ca430)
Location: fs/proc/vmcore.c:144
Inline: True
```
**Symbols:**

```
ffffffff812ca430-ffffffff812ca44a: elfcorehdr_read (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812d7900)
Location: fs/proc/vmcore.c:144
Inline: True
```
**Symbols:**

```
ffffffff812d7900-ffffffff812d791a: elfcorehdr_read (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812fbfe0)
Location: fs/proc/vmcore.c:144
Inline: True
```
**Symbols:**

```
ffffffff812fbfe0-ffffffff812fbffa: elfcorehdr_read (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81329a50)
Location: fs/proc/vmcore.c:156
Inline: True
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff81329a50-ffffffff81329a6a: elfcorehdr_read (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81340ee0)
Location: fs/proc/vmcore.c:166
Inline: True
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
ffffffff81340ee0-ffffffff81340efd: elfcorehdr_read (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813692b0)
Location: fs/proc/vmcore.c:171
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff813692b0-ffffffff813692f8: elfcorehdr_read (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff810727c0)
Location: arch/x86/kernel/crash_dump_64.c:74
Inline: True
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff810727c0-ffffffff810727f9: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff81079780)
Location: arch/x86/kernel/crash_dump_64.c:74
Inline: True
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81079780-ffffffff810797b9: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff81079660)
Location: arch/x86/kernel/crash_dump_64.c:74
Inline: True
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81079660-ffffffff81079699: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff8107a600)
Location: arch/x86/kernel/crash_dump_64.c:74
Inline: True
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff8107a600-ffffffff8107a639: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff81088750)
Location: arch/x86/kernel/crash_dump_64.c:74
Inline: True
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81088750-ffffffff81088789: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff81098910)
Location: arch/x86/kernel/crash_dump_64.c:55
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81098910-ffffffff810989c4: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff810af070)
Location: arch/x86/kernel/crash_dump_64.c:55
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff810af070-ffffffff810af124: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff810b2070)
Location: arch/x86/kernel/crash_dump_64.c:55
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff810b2070-ffffffff810b2124: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff810b94a0)
Location: arch/x86/kernel/crash_dump_64.c:55
Inline: False
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff810b94a0-ffffffff810b9554: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/crash_dump.c (ffff8000100aba78)
Location: arch/arm64/kernel/crash_dump.c:64
Inline: True
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffff8000100aba78-ffff8000100abacc: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c06127fc)
Location: fs/proc/vmcore.c:171
Inline: True
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:vmcore_init
```
**Symbols:**

```
c0612c70-c0612ca8: elfcorehdr_read (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c000000000567180)
Location: fs/proc/vmcore.c:171
Inline: True
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
c000000000567180-c0000000005671b8: elfcorehdr_read (STB_WEAK)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff810717c0)
Location: arch/x86/kernel/crash_dump_64.c:74
Inline: True
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff810717c0-ffffffff810717f9: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff810617d0)
Location: arch/x86/kernel/crash_dump_64.c:74
Inline: True
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff810617d0-ffffffff81061809: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff81071770)
Location: arch/x86/kernel/crash_dump_64.c:74
Inline: True
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81071770-ffffffff810717a9: elfcorehdr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash_dump_64.c (ffffffff810737d0)
Location: arch/x86/kernel/crash_dump_64.c:74
Inline: True
Direct callers:
  - fs/proc/vmcore.c:vmcore_init
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff810737d0-ffffffff81073809: elfcorehdr_read (STB_GLOBAL)
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
