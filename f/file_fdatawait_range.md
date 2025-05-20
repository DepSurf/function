# Function: <code>file_fdatawait_range</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cafc0)
Location: mm/filemap.c:578
Inline: False
Direct callers:
  - fs/sync.c:SyS_sync_file_range2
  - fs/sync.c:SyS_sync_file_range2
```
**Symbols:**

```
ffffffff811cafc0-ffffffff811cafe4: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ec220)
Location: mm/filemap.c:578
Inline: False
Direct callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:ksys_sync_file_range
```
**Symbols:**

```
ffffffff811ec220-ffffffff811ec244: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fe580)
Location: mm/filemap.c:555
Inline: False
Direct callers:
  - fs/sync.c:ksys_sync_file_range
  - fs/sync.c:ksys_sync_file_range
```
**Symbols:**

```
ffffffff811fe580-ffffffff811fe5a4: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812137a0)
Location: mm/filemap.c:590
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff812137a0-ffffffff812137c6: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81220f70)
Location: mm/filemap.c:596
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff81220f70-ffffffff81220f96: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124ebd0)
Location: mm/filemap.c:596
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff8124ebd0-ffffffff8124ebf8: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812591c0)
Location: mm/filemap.c:597
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff812591c0-ffffffff812591e8: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125e3f0)
Location: mm/filemap.c:588
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff8125e3f0-ffffffff8125e418: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129b000)
Location: mm/filemap.c:606
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff8129b000-ffffffff8129b028: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812efe50)
Location: mm/filemap.c:594
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff812efe50-ffffffff812efe81: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135b060)
Location: mm/filemap.c:591
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff8135b060-ffffffff8135b091: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138dcf0)
Location: mm/filemap.c:598
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff8138dcf0-ffffffff8138dd21: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b7430)
Location: mm/filemap.c:593
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff813b7430-ffffffff813b7461: file_fdatawait_range (STB_GLOBAL)
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
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102af4c0)
Location: mm/filemap.c:596
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffff8000102af4c0-ffff8000102af50c: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04daf9c)
Location: mm/filemap.c:596
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
c04daf9c-c04dafd8: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c0000000003629c0)
Location: mm/filemap.c:596
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
c0000000003629c0-c000000000362a04: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d47b6)
Location: mm/filemap.c:596
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffe0001d47b6-ffffffe0001d47fa: file_fdatawait_range (STB_GLOBAL)
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
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812195c0)
Location: mm/filemap.c:596
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff812195c0-ffffffff812195e6: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120c7d0)
Location: mm/filemap.c:596
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff8120c7d0-ffffffff8120c7f6: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81217360)
Location: mm/filemap.c:596
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff81217360-ffffffff81217386: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int file_fdatawait_range(struct file *file, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226410)
Location: mm/filemap.c:596
Inline: False
Direct callers:
  - fs/sync.c:sync_file_range
  - fs/sync.c:sync_file_range
```
**Symbols:**

```
ffffffff81226410-ffffffff81226436: file_fdatawait_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
