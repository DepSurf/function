# Function: <code>walk_system_ram_res</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(u64, u64, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086e20)
Location: kernel/resource.c:424
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff81086e20-ffffffff81086ed1: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(u64, u64, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81089e50)
Location: kernel/resource.c:450
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff81089e50-ffffffff81089efc: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(u64, u64, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108eda0)
Location: kernel/resource.c:450
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff8108eda0-ffffffff8108ee4c: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(u64, u64, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108bd60)
Location: kernel/resource.c:450
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff8108bd60-ffffffff8108be0c: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092a90)
Location: kernel/resource.c:459
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff81092a90-ffffffff81092ae9: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810964b0)
Location: kernel/resource.c:427
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff810964b0-ffffffff81096509: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e820)
Location: kernel/resource.c:429
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff8109e820-ffffffff8109e841: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2e70)
Location: kernel/resource.c:445
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff810a2e70-ffffffff810a2e91: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a94b0)
Location: kernel/resource.c:445
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff810a94b0-ffffffff810a94d1: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0fa0)
Location: kernel/resource.c:445
Inline: False
```
**Symbols:**

```
ffffffff810b0fa0-ffffffff810b1042: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac700)
Location: kernel/resource.c:452
Inline: False
Direct callers:
  - kernel/kexec_file.c:arch_kexec_locate_mem_hole
```
**Symbols:**

```
ffffffff810ac700-ffffffff810ac7a2: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad910)
Location: kernel/resource.c:438
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/kexec_file.c:arch_kexec_locate_mem_hole
```
**Symbols:**

```
ffffffff810ad910-ffffffff810ad9ac: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bf490)
Location: kernel/resource.c:438
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/kexec_file.c:arch_kexec_locate_mem_hole
```
**Symbols:**

```
ffffffff810bf490-ffffffff810bf52c: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d6840)
Location: kernel/resource.c:425
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/kexec_file.c:kexec_locate_mem_hole
```
**Symbols:**

```
ffffffff810d6840-ffffffff810d6904: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f6240)
Location: kernel/resource.c:425
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/kexec_file.c:kexec_locate_mem_hole
```
**Symbols:**

```
ffffffff810f6240-ffffffff810f6304: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81102690)
Location: kernel/resource.c:425
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - kernel/kexec_file.c:kexec_locate_mem_hole
```
**Symbols:**

```
ffffffff81102690-ffffffff81102754: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110be20)
Location: kernel/resource.c:425
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:prepare_elf_headers
  - arch/x86/kernel/crash.c:prepare_elf_headers
  - kernel/kexec_file.c:kexec_locate_mem_hole
```
**Symbols:**

```
ffffffff8110be20-ffffffff8110bee4: walk_system_ram_res (STB_GLOBAL)
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
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010101230)
Location: kernel/resource.c:445
Inline: False
```
**Symbols:**

```
ffff800010101230-ffff80001010128c: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035d88c)
Location: kernel/resource.c:445
Inline: False
```
**Symbols:**

```
c035d88c-c035d8d8: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000148990)
Location: kernel/resource.c:445
Inline: False
```
**Symbols:**

```
c000000000148990-c0000000001489c0: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c85e8)
Location: kernel/resource.c:445
Inline: False
```
**Symbols:**

```
ffffffe0000c85e8-ffffffe0000c8638: walk_system_ram_res (STB_GLOBAL)
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
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2dd0)
Location: kernel/resource.c:445
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff810a2dd0-ffffffff810a2df1: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810917b0)
Location: kernel/resource.c:445
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff810917b0-ffffffff810917d1: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2d80)
Location: kernel/resource.c:445
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff810a2d80-ffffffff810a2da1: walk_system_ram_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int walk_system_ram_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aae20)
Location: kernel/resource.c:445
Inline: False
Direct callers:
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
  - arch/x86/kernel/crash.c:crash_load_segments
```
**Symbols:**

```
ffffffff810aae20-ffffffff810aae41: walk_system_ram_res (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*func)(u64, u64, void *)</code> ➡️ <code>int (*func)(struct resource *, void *)</code>
</li>
</ul>
</details>
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
