# Function: <code>read_from_oldmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81287550)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff81287550-ffffffff8128767e: read_from_oldmem.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812b4a81)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff812b4830-ffffffff812b4953: read_from_oldmem.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812ca311)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff812ca0c0-ffffffff812ca1e3: read_from_oldmem.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812d77b4)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff812d75d0-ffffffff812d7704: read_from_oldmem.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff812fbe94)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff812fbcb0-ffffffff812fbde7: read_from_oldmem.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813297bf)
Location: fs/proc/vmcore.c:100
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffffffff813295e0-ffffffff8132970e: read_from_oldmem.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813411ad)
Location: fs/proc/vmcore.c:102
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
**Symbols:**

```
ffffffff81340da0-ffffffff81340edf: read_from_oldmem.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8136957d)
Location: fs/proc/vmcore.c:107
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
```
**Symbols:**

```
ffffffff81369160-ffffffff813692a3: read_from_oldmem.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(char *buf, size_t count, u64 *ppos, int userbuf, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813817cd)
Location: fs/proc/vmcore.c:107
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
**Symbols:**

```
ffffffff813813c0-ffffffff81381503: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff81381510-ffffffff8138152c: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(char *buf, size_t count, u64 *ppos, int userbuf, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813cbae5)
Location: fs/proc/vmcore.c:106
Inline: True
Inline callers:
  - fs/proc/vmcore.c:elfcorehdr_read_notes
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
**Symbols:**

```
ffffffff813cb950-ffffffff813cba93: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff813cbaa0-ffffffff813cbabc: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(char *buf, size_t count, u64 *ppos, int userbuf, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813dd775)
Location: fs/proc/vmcore.c:106
Inline: True
Inline callers:
  - fs/proc/vmcore.c:elfcorehdr_read_notes
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
**Symbols:**

```
ffffffff813dd5e0-ffffffff813dd723: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff813dd730-ffffffff813dd74c: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(char *buf, size_t count, u64 *ppos, int userbuf, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff813e4655)
Location: fs/proc/vmcore.c:106
Inline: True
Inline callers:
  - fs/proc/vmcore.c:elfcorehdr_read_notes
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
**Symbols:**

```
ffffffff813e44c0-ffffffff813e4603: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff813e4610-ffffffff813e462c: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(char *buf, size_t count, u64 *ppos, int userbuf, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81436225)
Location: fs/proc/vmcore.c:106
Inline: True
Inline callers:
  - fs/proc/vmcore.c:elfcorehdr_read_notes
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
**Symbols:**

```
ffffffff81436070-ffffffff814361dc: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff814361e0-ffffffff814361fc: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(struct iov_iter *iter, size_t count, u64 *ppos, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff814b0aaf)
Location: fs/proc/vmcore.c:132
Inline: True
Inline callers:
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
```
**Symbols:**

```
ffffffff814b05c0-ffffffff814b0708: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff814b0710-ffffffff814b0743: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(struct iov_iter *iter, size_t count, u64 *ppos, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff815473af)
Location: fs/proc/vmcore.c:131
Inline: True
Inline callers:
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
```
**Symbols:**

```
ffffffff81546e80-ffffffff81546fc8: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff81546fe0-ffffffff81547013: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(struct iov_iter *iter, size_t count, u64 *ppos, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8157efcf)
Location: fs/proc/vmcore.c:131
Inline: True
Inline callers:
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
```
**Symbols:**

```
ffffffff8157ea80-ffffffff8157ebe2: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff8157ec00-ffffffff8157ec33: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(struct iov_iter *iter, size_t count, u64 *ppos, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff815b7a0f)
Location: fs/proc/vmcore.c:131
Inline: True
Inline callers:
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:__read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
  - fs/proc/vmcore.c:elfcorehdr_read
```
**Symbols:**

```
ffffffff815b74c0-ffffffff815b7622: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff815b7640-ffffffff815b7673: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(char *buf, size_t count, u64 *ppos, int userbuf, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffff80001044f67c)
Location: fs/proc/vmcore.c:107
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
ffff80001044f298-ffff80001044f39c: read_from_oldmem.part.0 (STB_LOCAL)
ffff80001044f3a0-ffff80001044f404: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(char *buf, size_t count, u64 *ppos, int userbuf, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (c0612960)
Location: fs/proc/vmcore.c:107
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
```
**Symbols:**

```
c061269c-c06127a0: read_from_oldmem.part.0 (STB_LOCAL)
c06127a0-c06127d8: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(char *buf, size_t count, u64 *ppos, int userbuf, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (c00000000056730c)
Location: fs/proc/vmcore.c:107
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
Direct callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
**Symbols:**

```
c000000000566fd0-c000000000567150: read_from_oldmem.part.0 (STB_LOCAL)
c000000000567150-c000000000567178: read_from_oldmem (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(char *buf, size_t count, u64 *ppos, int userbuf, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff81379dad)
Location: fs/proc/vmcore.c:107
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
**Symbols:**

```
ffffffff813799a0-ffffffff81379ae3: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff81379af0-ffffffff81379b0c: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(char *buf, size_t count, u64 *ppos, int userbuf, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8136a87d)
Location: fs/proc/vmcore.c:107
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
**Symbols:**

```
ffffffff8136a470-ffffffff8136a5b3: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff8136a5c0-ffffffff8136a5dc: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(char *buf, size_t count, u64 *ppos, int userbuf, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8137787d)
Location: fs/proc/vmcore.c:107
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
**Symbols:**

```
ffffffff81377470-ffffffff813775b3: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff813775c0-ffffffff813775dc: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t read_from_oldmem(char *buf, size_t count, u64 *ppos, int userbuf, bool encrypted);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (ffffffff8138b32d)
Location: fs/proc/vmcore.c:107
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
Direct callers:
  - arch/x86/kernel/crash_dump_64.c:elfcorehdr_read
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
**Symbols:**

```
ffffffff8138af20-ffffffff8138b063: read_from_oldmem.part.0 (STB_LOCAL)
ffffffff8138b070-ffffffff8138b08c: read_from_oldmem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iov_iter *iter</code>
</li>
<li>
<b>Param removed. </b>
<code>char *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>int userbuf</code>
</li>
<li>
<b>Param reordered. </b>
<code>buf, count, ppos, userbuf, encrypted</code> ➡️ <code>iter, count, ppos, encrypted</code>
</li>
</ul>
</details>
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
