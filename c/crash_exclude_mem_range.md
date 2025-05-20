# Function: <code>crash_exclude_mem_range</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81139e60)
Location: kernel/kexec_file.c:1061
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81139e60-ffffffff8113a019: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81145730)
Location: kernel/kexec_file.c:1119
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81145730-ffffffff811458e9: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81150b20)
Location: kernel/kexec_file.c:1164
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81150b20-ffffffff81150c84: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115c7b0)
Location: kernel/kexec_file.c:1169
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff8115c7b0-ffffffff8115c914: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116d4f0)
Location: kernel/kexec_file.c:1156
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff8116d4f0-ffffffff8116d652: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81169b70)
Location: kernel/kexec_file.c:1174
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81169b70-ffffffff81169cfe: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116a860)
Location: kernel/kexec_file.c:1176
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff8116a860-ffffffff8116a9e0: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81190490)
Location: kernel/kexec_file.c:1176
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81190490-ffffffff81190610: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811bfd10)
Location: kernel/kexec_file.c:1135
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff811bfd10-ffffffff811bfecd: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81202070)
Location: kernel/kexec_file.c:1139
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81202070-ffffffff8120222d: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81217450)
Location: kernel/kexec_file.c:1155
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81217450-ffffffff8121760d: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff8122a7f0)
Location: kernel/crash_core.c:576
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:prepare_elf_headers
  - arch/x86/kernel/crash.c:prepare_elf_headers
  - arch/x86/kernel/crash.c:prepare_elf_headers
```
**Symbols:**

```
ffffffff8122a7f0-ffffffff8122a9ae: crash_exclude_mem_range (STB_GLOBAL)
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
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffff8000101cb328)
Location: kernel/kexec_file.c:1169
Inline: False
```
**Symbols:**

```
ffff8000101cb328-ffff8000101cb4c4: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (c000000000235100)
Location: kernel/kexec_file.c:1169
Inline: False
```
**Symbols:**

```
c000000000235100-c00000000023536c: crash_exclude_mem_range (STB_GLOBAL)
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
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81154dd0)
Location: kernel/kexec_file.c:1169
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81154dd0-ffffffff81154f34: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811480f0)
Location: kernel/kexec_file.c:1169
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff811480f0-ffffffff81148254: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81152bb0)
Location: kernel/kexec_file.c:1169
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff81152bb0-ffffffff81152d14: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crash_exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115faa0)
Location: kernel/kexec_file.c:1169
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff8115faa0-ffffffff8115fc04: crash_exclude_mem_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
