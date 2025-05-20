# Function: <code>elfcorehdr_read_notes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81287870)
Location: fs/proc/vmcore.c:152
Inline: True
```
**Symbols:**

```
ffffffff81287870-ffffffff8128788a: elfcorehdr_read_notes.localalias.6 (STB_LOCAL)
ffffffff81287870-ffffffff8128788a: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812b4bc0)
Location: fs/proc/vmcore.c:152
Inline: True
```
**Symbols:**

```
ffffffff812b4bc0-ffffffff812b4bda: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812ca450)
Location: fs/proc/vmcore.c:152
Inline: True
```
**Symbols:**

```
ffffffff812ca450-ffffffff812ca46a: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812d7920)
Location: fs/proc/vmcore.c:152
Inline: True
```
**Symbols:**

```
ffffffff812d7920-ffffffff812d793a: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812fc000)
Location: fs/proc/vmcore.c:152
Inline: True
```
**Symbols:**

```
ffffffff812fc000-ffffffff812fc01a: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81329a70)
Location: fs/proc/vmcore.c:164
Inline: True
```
**Symbols:**

```
ffffffff81329a70-ffffffff81329a8a: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81340f00)
Location: fs/proc/vmcore.c:174
Inline: False
```
**Symbols:**

```
ffffffff81340f00-ffffffff81340f45: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81369300)
Location: fs/proc/vmcore.c:179
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81369300-ffffffff81369329: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81381550)
Location: fs/proc/vmcore.c:179
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81381550-ffffffff81381579: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813cbae0)
Location: fs/proc/vmcore.c:178
Inline: False
Direct callers:
  - fs/proc/vmcore.c:update_note_header_size_elf32
  - fs/proc/vmcore.c:update_note_header_size_elf64
```
**Symbols:**

```
ffffffff813cbae0-ffffffff813cbb09: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813dd770)
Location: fs/proc/vmcore.c:178
Inline: False
Direct callers:
  - fs/proc/vmcore.c:update_note_header_size_elf32
  - fs/proc/vmcore.c:update_note_header_size_elf64
```
**Symbols:**

```
ffffffff813dd770-ffffffff813dd799: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813e4650)
Location: fs/proc/vmcore.c:178
Inline: False
Direct callers:
  - fs/proc/vmcore.c:update_note_header_size_elf32
  - fs/proc/vmcore.c:update_note_header_size_elf64
```
**Symbols:**

```
ffffffff813e4650-ffffffff813e4679: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81436220)
Location: fs/proc/vmcore.c:182
Inline: False
Direct callers:
  - fs/proc/vmcore.c:update_note_header_size_elf32
  - fs/proc/vmcore.c:update_note_header_size_elf64
```
**Symbols:**

```
ffffffff81436220-ffffffff81436249: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff814b0800)
Location: fs/proc/vmcore.c:211
Inline: False
Direct callers:
  - fs/proc/vmcore.c:update_note_header_size_elf32
  - fs/proc/vmcore.c:update_note_header_size_elf64
```
**Symbols:**

```
ffffffff814b0800-ffffffff814b08be: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff815470f0)
Location: fs/proc/vmcore.c:210
Inline: False
Direct callers:
  - fs/proc/vmcore.c:update_note_header_size_elf32
  - fs/proc/vmcore.c:update_note_header_size_elf64
```
**Symbols:**

```
ffffffff815470f0-ffffffff815471ae: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8157ed10)
Location: fs/proc/vmcore.c:210
Inline: False
Direct callers:
  - fs/proc/vmcore.c:update_note_header_size_elf32
  - fs/proc/vmcore.c:update_note_header_size_elf64
```
**Symbols:**

```
ffffffff8157ed10-ffffffff8157edce: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff815b7750)
Location: fs/proc/vmcore.c:210
Inline: False
Direct callers:
  - fs/proc/vmcore.c:update_note_header_size_elf32
  - fs/proc/vmcore.c:update_note_header_size_elf64
```
**Symbols:**

```
ffffffff815b7750-ffffffff815b780e: elfcorehdr_read_notes (STB_WEAK)
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
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffff80001044f408)
Location: fs/proc/vmcore.c:179
Inline: True
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffff80001044f408-ffff80001044f45c: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c06127d8)
Location: fs/proc/vmcore.c:179
Inline: True
```
**Symbols:**

```
c06127d8-c0612810: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c0000000005671c0)
Location: fs/proc/vmcore.c:179
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
c0000000005671c0-c0000000005671f8: elfcorehdr_read_notes (STB_WEAK)
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
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81379b30)
Location: fs/proc/vmcore.c:179
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81379b30-ffffffff81379b59: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8136a600)
Location: fs/proc/vmcore.c:179
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff8136a600-ffffffff8136a629: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81377600)
Location: fs/proc/vmcore.c:179
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff81377600-ffffffff81377629: elfcorehdr_read_notes (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t elfcorehdr_read_notes(char *buf, size_t count, u64 *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8138b0b0)
Location: fs/proc/vmcore.c:179
Inline: False
Direct callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
**Symbols:**

```
ffffffff8138b0b0-ffffffff8138b0d9: elfcorehdr_read_notes (STB_WEAK)
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
