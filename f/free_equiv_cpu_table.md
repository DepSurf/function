# Function: <code>free_equiv_cpu_table</code>

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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff820af263)
Location: arch/x86/kernel/cpu/microcode/amd.c:735
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff820e6f2f)
Location: arch/x86/kernel/cpu/microcode/amd.c:747
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050f67)
Location: arch/x86/kernel/cpu/microcode/amd.c:748
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff822c1f2a)
Location: arch/x86/kernel/cpu/microcode/amd.c:560
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff828d50aa)
Location: arch/x86/kernel/cpu/microcode/amd.c:567
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff82906900)
Location: arch/x86/kernel/cpu/microcode/amd.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_equiv_cpu_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054ac0)
Location: arch/x86/kernel/cpu/microcode/amd.c:745
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
**Symbols:**

```
ffffffff81054ac0-ffffffff81054aed: free_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_equiv_cpu_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057d00)
Location: arch/x86/kernel/cpu/microcode/amd.c:743
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
**Symbols:**

```
ffffffff81057d00-ffffffff81057d2d: free_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_equiv_cpu_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810585d0)
Location: arch/x86/kernel/cpu/microcode/amd.c:743
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
**Symbols:**

```
ffffffff810585d0-ffffffff810585fd: free_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_equiv_cpu_table();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105d650)
Location: arch/x86/kernel/cpu/microcode/amd.c:743
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
**Symbols:**

```
ffffffff8105d650-ffffffff8105d67d: free_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_equiv_cpu_table();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105bcf0)
Location: arch/x86/kernel/cpu/microcode/amd.c:742
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
**Symbols:**

```
ffffffff8105bcf0-ffffffff8105bd1d: free_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_equiv_cpu_table();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c6c0)
Location: arch/x86/kernel/cpu/microcode/amd.c:742
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
**Symbols:**

```
ffffffff8105c6c0-ffffffff8105c6ed: free_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_equiv_cpu_table();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81065d70)
Location: arch/x86/kernel/cpu/microcode/amd.c:742
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
**Symbols:**

```
ffffffff81065d70-ffffffff81065d9d: free_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_equiv_cpu_table();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810731f5)
Location: arch/x86/kernel/cpu/microcode/amd.c:748
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
**Symbols:**

```
ffffffff81072730-ffffffff81072763: free_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810832f5)
Location: arch/x86/kernel/cpu/microcode/amd.c:759
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810857a5)
Location: arch/x86/kernel/cpu/microcode/amd.c:754
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff83d4dc00)
Location: arch/x86/kernel/cpu/microcode/amd.c:727
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
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
<summary>In <code>aws</code>: ✅</summary>

```c
void free_equiv_cpu_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058150)
Location: arch/x86/kernel/cpu/microcode/amd.c:743
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
**Symbols:**

```
ffffffff81058150-ffffffff8105817d: free_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_equiv_cpu_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048270)
Location: arch/x86/kernel/cpu/microcode/amd.c:743
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
**Symbols:**

```
ffffffff81048270-ffffffff8104829d: free_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_equiv_cpu_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058580)
Location: arch/x86/kernel/cpu/microcode/amd.c:743
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
**Symbols:**

```
ffffffff81058580-ffffffff810585ad: free_equiv_cpu_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_equiv_cpu_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059a20)
Location: arch/x86/kernel/cpu/microcode/amd.c:743
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - arch/x86/kernel/cpu/microcode/amd.c:exit_amd_microcode
```
**Symbols:**

```
ffffffff81059a20-ffffffff81059a4d: free_equiv_cpu_table (STB_LOCAL)
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
