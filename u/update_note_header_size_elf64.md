# Function: <code>update_note_header_size_elf64</code>

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
In fs/proc/vmcore.c (ffffffff81f910cf)
Location: fs/proc/vmcore.c:524
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
In fs/proc/vmcore.c (ffffffff81fbba3d)
Location: fs/proc/vmcore.c:527
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
In fs/proc/vmcore.c (ffffffff81ff8457)
Location: fs/proc/vmcore.c:527
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
In fs/proc/vmcore.c (ffffffff820db50a)
Location: fs/proc/vmcore.c:527
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
In fs/proc/vmcore.c (ffffffff826e419f)
Location: fs/proc/vmcore.c:527
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
In fs/proc/vmcore.c (ffffffff8270e79e)
Location: fs/proc/vmcore.c:676
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
In fs/proc/vmcore.c (ffffffff828c590d)
Location: fs/proc/vmcore.c:698
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
In fs/proc/vmcore.c (ffffffff828def70)
Location: fs/proc/vmcore.c:703
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf64_headers
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
In fs/proc/vmcore.c (ffffffff828e7948)
Location: fs/proc/vmcore.c:703
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int update_note_header_size_elf64(const Elf64_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff82d01feb)
Location: fs/proc/vmcore.c:703
Inline: False
```
**Symbols:**

```
ffffffff82d01feb-ffffffff82d0212a: update_note_header_size_elf64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int update_note_header_size_elf64(const Elf64_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff82fef2da)
Location: fs/proc/vmcore.c:703
Inline: False
```
**Symbols:**

```
ffffffff82fef2da-ffffffff82fef419: update_note_header_size_elf64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int update_note_header_size_elf64(const Elf64_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff831f9b8b)
Location: fs/proc/vmcore.c:703
Inline: False
```
**Symbols:**

```
ffffffff831f9b8b-ffffffff831f9cca: update_note_header_size_elf64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int update_note_header_size_elf64(const Elf64_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff832e0ab4)
Location: fs/proc/vmcore.c:707
Inline: False
```
**Symbols:**

```
ffffffff832e0ab4-ffffffff832e0bf3: update_note_header_size_elf64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int update_note_header_size_elf64(const Elf64_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff83496b29)
Location: fs/proc/vmcore.c:725
Inline: False
```
**Symbols:**

```
ffffffff83496b29-ffffffff83496c74: update_note_header_size_elf64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int update_note_header_size_elf64(const Elf64_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff83ecbd70)
Location: fs/proc/vmcore.c:724
Inline: False
```
**Symbols:**

```
ffffffff83ecbd70-ffffffff83ecbf38: update_note_header_size_elf64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int update_note_header_size_elf64(const Elf64_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff836f0df0)
Location: fs/proc/vmcore.c:723
Inline: False
```
**Symbols:**

```
ffffffff836f0df0-ffffffff836f0fb8: update_note_header_size_elf64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int update_note_header_size_elf64(const Elf64_Ehdr *ehdr_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (ffffffff83923e90)
Location: fs/proc/vmcore.c:723
Inline: False
```
**Symbols:**

```
ffffffff83923e90-ffffffff83924058: update_note_header_size_elf64 (STB_LOCAL)
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
In fs/proc/vmcore.c (ffff800011461518)
Location: fs/proc/vmcore.c:703
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (c00000000138cffc)
Location: fs/proc/vmcore.c:703
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf64_headers
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
In fs/proc/vmcore.c (ffffffff828d07fc)
Location: fs/proc/vmcore.c:703
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf64_headers
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
In fs/proc/vmcore.c (ffffffff828c8f18)
Location: fs/proc/vmcore.c:703
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf64_headers
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
In fs/proc/vmcore.c (ffffffff828e357c)
Location: fs/proc/vmcore.c:703
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf64_headers
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
In fs/proc/vmcore.c (ffffffff828e8992)
Location: fs/proc/vmcore.c:703
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf64_headers
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
