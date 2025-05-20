# Function: <code>exclude_mem_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8105d280)
Location: arch/x86/kernel/crash.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:prepare_elf64_ram_headers_callback
  - arch/x86/kernel/crash.c:prepare_elf64_ram_headers_callback
  - arch/x86/kernel/crash.c:prepare_elf64_ram_headers_callback
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
```
**Symbols:**

```
ffffffff8105d280-ffffffff8105d414: exclude_mem_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8105d260)
Location: arch/x86/kernel/crash.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:prepare_elf64_ram_headers_callback
  - arch/x86/kernel/crash.c:prepare_elf64_ram_headers_callback
```
**Symbols:**

```
ffffffff8105d260-ffffffff8105d3ea: exclude_mem_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81060260)
Location: arch/x86/kernel/crash.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:prepare_elf64_ram_headers_callback
  - arch/x86/kernel/crash.c:prepare_elf64_ram_headers_callback
```
**Symbols:**

```
ffffffff81060260-ffffffff810603ea: exclude_mem_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8105f210)
Location: arch/x86/kernel/crash.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:prepare_elf64_ram_headers_callback
  - arch/x86/kernel/crash.c:prepare_elf64_ram_headers_callback
```
**Symbols:**

```
ffffffff8105f210-ffffffff8105f3ca: exclude_mem_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int exclude_mem_range(struct crash_mem *mem, long long unsigned int mstart, long long unsigned int mend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff81063220)
Location: arch/x86/kernel/crash.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:crash_setup_memmap_entries
  - arch/x86/kernel/crash.c:prepare_elf64_ram_headers_callback
  - arch/x86/kernel/crash.c:prepare_elf64_ram_headers_callback
```
**Symbols:**

```
ffffffff81063220-ffffffff810633da: exclude_mem_range (STB_LOCAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
