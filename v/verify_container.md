# Function: <code>verify_container</code>

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
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054c40)
Location: arch/x86/kernel/cpu/microcode/amd.c:91
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
```
**Symbols:**

```
ffffffff81054c40-ffffffff81054cae: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057e80)
Location: arch/x86/kernel/cpu/microcode/amd.c:89
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
```
**Symbols:**

```
ffffffff81057e80-ffffffff81057eee: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058750)
Location: arch/x86/kernel/cpu/microcode/amd.c:89
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
```
**Symbols:**

```
ffffffff81058750-ffffffff810587be: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105d7d0)
Location: arch/x86/kernel/cpu/microcode/amd.c:89
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/microcode/amd.c:parse_container
```
**Symbols:**

```
ffffffff8105d7d0-ffffffff8105d841: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105be70)
Location: arch/x86/kernel/cpu/microcode/amd.c:89
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table
  - arch/x86/kernel/cpu/microcode/amd.c:parse_container
```
**Symbols:**

```
ffffffff8105be70-ffffffff8105bee1: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c840)
Location: arch/x86/kernel/cpu/microcode/amd.c:89
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff8105c840-ffffffff8105c8b1: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81065ef0)
Location: arch/x86/kernel/cpu/microcode/amd.c:89
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff81065ef0-ffffffff81065f5b: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81072630)
Location: arch/x86/kernel/cpu/microcode/amd.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:verify_equivalence_table
```
**Symbols:**

```
ffffffff81072630-ffffffff8107269c: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81082600)
Location: arch/x86/kernel/cpu/microcode/amd.c:91
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:verify_equivalence_table
```
**Symbols:**

```
ffffffff81082600-ffffffff8108266e: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81085135)
Location: arch/x86/kernel/cpu/microcode/amd.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:verify_equivalence_table
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
```
**Symbols:**

```
ffffffff81084a70-ffffffff81084ade: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c3d5)
Location: arch/x86/kernel/cpu/microcode/amd.c:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:verify_equivalence_table
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
```
**Symbols:**

```
ffffffff8108be60-ffffffff8108bec2: verify_container (STB_LOCAL)
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
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810582d0)
Location: arch/x86/kernel/cpu/microcode/amd.c:89
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
```
**Symbols:**

```
ffffffff810582d0-ffffffff8105833e: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048450)
Location: arch/x86/kernel/cpu/microcode/amd.c:89
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
```
**Symbols:**

```
ffffffff81048450-ffffffff810484be: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058700)
Location: arch/x86/kernel/cpu/microcode/amd.c:89
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
```
**Symbols:**

```
ffffffff81058700-ffffffff8105876e: verify_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool verify_container(const u8 *buf, size_t buf_size, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059ba0)
Location: arch/x86/kernel/cpu/microcode/amd.c:89
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
```
**Symbols:**

```
ffffffff81059ba0-ffffffff81059c0e: verify_container (STB_LOCAL)
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
