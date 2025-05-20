# Function: <code>verify_equivalence_table</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool verify_equivalence_table(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054cb0)
Location: arch/x86/kernel/cpu/microcode/amd.c:118
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81054cb0-ffffffff81054d46: verify_equivalence_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool verify_equivalence_table(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057ef0)
Location: arch/x86/kernel/cpu/microcode/amd.c:116
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81057ef0-ffffffff81057f86: verify_equivalence_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool verify_equivalence_table(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810587c0)
Location: arch/x86/kernel/cpu/microcode/amd.c:116
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff810587c0-ffffffff81058856: verify_equivalence_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105dd05)
Location: arch/x86/kernel/cpu/microcode/amd.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/microcode/amd.c:parse_container
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/microcode/amd.c:parse_container
```
**Symbols:**

```
ffffffff8105d850-ffffffff8105d8d9: verify_equivalence_table.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c486)
Location: arch/x86/kernel/cpu/microcode/amd.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/microcode/amd.c:parse_container
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/microcode/amd.c:parse_container
```
**Symbols:**

```
ffffffff8105bef0-ffffffff8105bf79: verify_equivalence_table.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c986)
Location: arch/x86/kernel/cpu/microcode/amd.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff8105c8c0-ffffffff8105c949: verify_equivalence_table.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81066026)
Location: arch/x86/kernel/cpu/microcode/amd.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81065f60-ffffffff81065fe3: verify_equivalence_table.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool verify_equivalence_table(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810726a0)
Location: arch/x86/kernel/cpu/microcode/amd.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff810726a0-ffffffff8107272e: verify_equivalence_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool verify_equivalence_table(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81082680)
Location: arch/x86/kernel/cpu/microcode/amd.c:118
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81082680-ffffffff81082710: verify_equivalence_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool verify_equivalence_table(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81085130)
Location: arch/x86/kernel/cpu/microcode/amd.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81085130-ffffffff81085204: verify_equivalence_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool verify_equivalence_table(const u8 *buf, size_t buf_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c3d0)
Location: arch/x86/kernel/cpu/microcode/amd.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff8108c3d0-ffffffff8108c48c: verify_equivalence_table (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool verify_equivalence_table(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058340)
Location: arch/x86/kernel/cpu/microcode/amd.c:116
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81058340-ffffffff810583d6: verify_equivalence_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool verify_equivalence_table(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810484c0)
Location: arch/x86/kernel/cpu/microcode/amd.c:116
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff810484c0-ffffffff81048556: verify_equivalence_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool verify_equivalence_table(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058770)
Location: arch/x86/kernel/cpu/microcode/amd.c:116
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81058770-ffffffff81058806: verify_equivalence_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool verify_equivalence_table(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059c10)
Location: arch/x86/kernel/cpu/microcode/amd.c:116
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81059c10-ffffffff81059ca6: verify_equivalence_table (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool early</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
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
