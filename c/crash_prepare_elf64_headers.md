# Function: <code>crash_prepare_elf64_headers</code>

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
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8113a020)
Location: kernel/kexec_file.c:1132
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff8113a020-ffffffff8113a28c: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811458f0)
Location: kernel/kexec_file.c:1190
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff811458f0-ffffffff81145b5c: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81150c90)
Location: kernel/kexec_file.c:1235
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff81150c90-ffffffff81150eee: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115c920)
Location: kernel/kexec_file.c:1240
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff8115c920-ffffffff8115cb7e: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116d660)
Location: kernel/kexec_file.c:1227
Inline: False
```
**Symbols:**

```
ffffffff8116d660-ffffffff8116d8be: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81169d00)
Location: kernel/kexec_file.c:1256
Inline: False
```
**Symbols:**

```
ffffffff81169d00-ffffffff81169f5d: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116a9e0)
Location: kernel/kexec_file.c:1258
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff8116a9e0-ffffffff8116ac3d: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81190610)
Location: kernel/kexec_file.c:1258
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff81190610-ffffffff81190896: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int need_kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811bfed0)
Location: kernel/kexec_file.c:1217
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff811bfed0-ffffffff811c0179: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int need_kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81202240)
Location: kernel/kexec_file.c:1221
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff81202240-ffffffff812024e9: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int need_kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81217620)
Location: kernel/kexec_file.c:1237
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff81217620-ffffffff812178c9: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int need_kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/crash_core.c (0)
Location: kernel/crash_core.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:prepare_elf_headers
```
**Symbols:**

```
ffffffff821b62fa-ffffffff821b6335: crash_prepare_elf64_headers.cold (STB_LOCAL)
ffffffff8122a510-ffffffff8122a7df: crash_prepare_elf64_headers (STB_GLOBAL)
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
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffff8000101cb4c8)
Location: kernel/kexec_file.c:1240
Inline: False
```
**Symbols:**

```
ffff8000101cb4c8-ffff8000101cb758: crash_prepare_elf64_headers (STB_GLOBAL)
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
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (c000000000235370)
Location: kernel/kexec_file.c:1240
Inline: False
```
**Symbols:**

```
c000000000235370-c0000000002356bc: crash_prepare_elf64_headers (STB_GLOBAL)
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
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81154f40)
Location: kernel/kexec_file.c:1240
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff81154f40-ffffffff8115519e: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81148260)
Location: kernel/kexec_file.c:1240
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff81148260-ffffffff811484be: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81152d20)
Location: kernel/kexec_file.c:1240
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff81152d20-ffffffff81152f7e: crash_prepare_elf64_headers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crash_prepare_elf64_headers(struct crash_mem *mem, int kernel_map, void **addr, long unsigned int *sz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115fc10)
Location: kernel/kexec_file.c:1240
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff8115fc10-ffffffff8115fe6e: crash_prepare_elf64_headers (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int need_kernel_map</code>
</li>
<li>
<b>Param removed. </b>
<code>int kernel_map</code>
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
