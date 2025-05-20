# Function: <code>update_note_header_size_elf32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81f91352)
Location: fs/proc/vmcore.c:710
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81fbbcc2)
Location: fs/proc/vmcore.c:713
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81ff86dc)
Location: fs/proc/vmcore.c:713
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff820db796)
Location: fs/proc/vmcore.c:713
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff826e442b)
Location: fs/proc/vmcore.c:713
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8270ea41)
Location: fs/proc/vmcore.c:867
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828c5bb0)
Location: fs/proc/vmcore.c:889
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828df3eb)
Location: fs/proc/vmcore.c:894
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828e7dc1)
Location: fs/proc/vmcore.c:894
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int update_note_header_size_elf32(const Elf32_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff82d02528)
Location: fs/proc/vmcore.c:894
Inline: False
```
**Symbols:**

```
ffffffff82d02528-ffffffff82d02666: update_note_header_size_elf32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int update_note_header_size_elf32(const Elf32_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff82fef821)
Location: fs/proc/vmcore.c:894
Inline: False
```
**Symbols:**

```
ffffffff82fef821-ffffffff82fef95f: update_note_header_size_elf32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int update_note_header_size_elf32(const Elf32_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff831fa0d3)
Location: fs/proc/vmcore.c:894
Inline: False
```
**Symbols:**

```
ffffffff831fa0d3-ffffffff831fa211: update_note_header_size_elf32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int update_note_header_size_elf32(const Elf32_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff832e1003)
Location: fs/proc/vmcore.c:898
Inline: False
```
**Symbols:**

```
ffffffff832e1003-ffffffff832e1141: update_note_header_size_elf32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int update_note_header_size_elf32(const Elf32_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff834970cb)
Location: fs/proc/vmcore.c:916
Inline: False
```
**Symbols:**

```
ffffffff834970cb-ffffffff83497216: update_note_header_size_elf32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int update_note_header_size_elf32(const Elf32_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff83ecc490)
Location: fs/proc/vmcore.c:915
Inline: False
```
**Symbols:**

```
ffffffff83ecc490-ffffffff83ecc652: update_note_header_size_elf32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int update_note_header_size_elf32(const Elf32_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff836f1510)
Location: fs/proc/vmcore.c:914
Inline: False
```
**Symbols:**

```
ffffffff836f1510-ffffffff836f16d2: update_note_header_size_elf32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int update_note_header_size_elf32(const Elf32_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff839245f0)
Location: fs/proc/vmcore.c:914
Inline: False
```
**Symbols:**

```
ffffffff839245f0-ffffffff839247b2: update_note_header_size_elf32 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffff80001146199c)
Location: fs/proc/vmcore.c:894
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c1539528)
Location: fs/proc/vmcore.c:894
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c00000000138d56c)
Location: fs/proc/vmcore.c:894
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828d0c75)
Location: fs/proc/vmcore.c:894
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828c9391)
Location: fs/proc/vmcore.c:894
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828e39f5)
Location: fs/proc/vmcore.c:894
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff828e8e0b)
Location: fs/proc/vmcore.c:894
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
