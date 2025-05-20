# Function: <code>install_equiv_cpu_table</code>

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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e91c)
Location: arch/x86/kernel/cpu/microcode/amd.c:711
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104eaab)
Location: arch/x86/kernel/cpu/microcode/amd.c:723
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050b06)
Location: arch/x86/kernel/cpu/microcode/amd.c:724
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050cfb)
Location: arch/x86/kernel/cpu/microcode/amd.c:536
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105483e)
Location: arch/x86/kernel/cpu/microcode/amd.c:543
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057601)
Location: arch/x86/kernel/cpu/microcode/amd.c:551
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810550e6)
Location: arch/x86/kernel/cpu/microcode/amd.c:721
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058316)
Location: arch/x86/kernel/cpu/microcode/amd.c:719
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058be6)
Location: arch/x86/kernel/cpu/microcode/amd.c:719
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
size_t install_equiv_cpu_table(const u8 *buf, size_t buf_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:719
Inline: False
```
**Symbols:**

```
ffffffff8105dd00-ffffffff8105dd7b: install_equiv_cpu_table (STB_LOCAL)
ffffffff8105e41c-ffffffff8105e42f: install_equiv_cpu_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
size_t install_equiv_cpu_table(const u8 *buf, size_t buf_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:718
Inline: False
```
**Symbols:**

```
ffffffff8105c470-ffffffff8105c4eb: install_equiv_cpu_table (STB_LOCAL)
ffffffff81bd6236-ffffffff81bd6249: install_equiv_cpu_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c986)
Location: arch/x86/kernel/cpu/microcode/amd.c:718
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81066026)
Location: arch/x86/kernel/cpu/microcode/amd.c:718
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81072ca6)
Location: arch/x86/kernel/cpu/microcode/amd.c:724
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t install_equiv_cpu_table(const u8 *buf, size_t buf_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81082bf0)
Location: arch/x86/kernel/cpu/microcode/amd.c:735
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
**Symbols:**

```
ffffffff81082bf0-ffffffff81082c68: install_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t install_equiv_cpu_table(const u8 *buf, size_t buf_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810854a0)
Location: arch/x86/kernel/cpu/microcode/amd.c:730
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
**Symbols:**

```
ffffffff810854a0-ffffffff81085518: install_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t install_equiv_cpu_table(const u8 *buf, size_t buf_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c620)
Location: arch/x86/kernel/cpu/microcode/amd.c:703
Inline: False
```
**Symbols:**

```
ffffffff8108c620-ffffffff8108c696: install_equiv_cpu_table (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058766)
Location: arch/x86/kernel/cpu/microcode/amd.c:719
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810488e6)
Location: arch/x86/kernel/cpu/microcode/amd.c:719
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058b96)
Location: arch/x86/kernel/cpu/microcode/amd.c:719
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105a036)
Location: arch/x86/kernel/cpu/microcode/amd.c:719
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
