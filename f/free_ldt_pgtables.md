# Function: <code>free_ldt_pgtables</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_ldt_pgtables(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81031be0)
Location: arch/x86/kernel/ldt.c:200
Inline: True
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81031be0-ffffffff81031c7e: free_ldt_pgtables.part.3 (STB_LOCAL)
ffffffff81031c80-ffffffff81031c95: free_ldt_pgtables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_ldt_pgtables(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81033200)
Location: arch/x86/kernel/ldt.c:204
Inline: True
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81033200-ffffffff8103329e: free_ldt_pgtables.part.3 (STB_LOCAL)
ffffffff810332a0-ffffffff810332b5: free_ldt_pgtables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void free_ldt_pgtables(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81034240)
Location: arch/x86/kernel/ldt.c:307
Inline: True
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81034240-ffffffff810342de: free_ldt_pgtables.part.2 (STB_LOCAL)
ffffffff810342e0-ffffffff810342f5: free_ldt_pgtables (STB_LOCAL)
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
In arch/x86/kernel/ldt.c (ffffffff810367ec)
Location: arch/x86/kernel/ldt.c:307
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81036360-ffffffff810363fe: free_ldt_pgtables.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103701c)
Location: arch/x86/kernel/ldt.c:307
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81036900-ffffffff8103699e: free_ldt_pgtables.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_ldt_pgtables(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81038630)
Location: arch/x86/kernel/ldt.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81038630-ffffffff810386db: free_ldt_pgtables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_ldt_pgtables(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81038fe0)
Location: arch/x86/kernel/ldt.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81038fe0-ffffffff8103908b: free_ldt_pgtables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_ldt_pgtables(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103aad0)
Location: arch/x86/kernel/ldt.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff8103aad0-ffffffff8103ab6d: free_ldt_pgtables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void free_ldt_pgtables(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff810404d0-ffffffff81040589: free_ldt_pgtables (STB_LOCAL)
ffffffff81c98cdb-ffffffff81c98d40: free_ldt_pgtables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void free_ldt_pgtables(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81047e10-ffffffff81047ee8: free_ldt_pgtables (STB_LOCAL)
ffffffff81e48297-ffffffff81e48301: free_ldt_pgtables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void free_ldt_pgtables(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81052af0-ffffffff81052bc8: free_ldt_pgtables (STB_LOCAL)
ffffffff8205217f-ffffffff820521e9: free_ldt_pgtables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void free_ldt_pgtables(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81053ae0-ffffffff81053bb8: free_ldt_pgtables (STB_LOCAL)
ffffffff820d0695-ffffffff820d0701: free_ldt_pgtables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void free_ldt_pgtables(struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/kernel/ldt.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff8105ad00-ffffffff8105add8: free_ldt_pgtables (STB_LOCAL)
ffffffff821ab1aa-ffffffff821ab216: free_ldt_pgtables.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8103717c)
Location: arch/x86/kernel/ldt.c:307
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81036a60-ffffffff81036afe: free_ldt_pgtables.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81026a4e)
Location: arch/x86/kernel/ldt.c:307
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff810263a0-ffffffff8102643e: free_ldt_pgtables.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81036fdc)
Location: arch/x86/kernel/ldt.c:307
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff810368c0-ffffffff8103695e: free_ldt_pgtables.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81037fda)
Location: arch/x86/kernel/ldt.c:307
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:ldt_arch_exit_mmap
  - arch/x86/kernel/ldt.c:ldt_dup_context
```
**Symbols:**

```
ffffffff81037b50-ffffffff81037bee: free_ldt_pgtables.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
