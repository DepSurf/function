# Function: <code>sgx_encl_test_and_clear_young</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young(struct mm_struct *mm, struct sgx_encl_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066950)
Location: arch/x86/kernel/cpu/sgx/encl.c:653
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
**Symbols:**

```
ffffffff81066950-ffffffff810669cc: sgx_encl_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young(struct mm_struct *mm, struct sgx_encl_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810668f0)
Location: arch/x86/kernel/cpu/sgx/encl.c:645
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
**Symbols:**

```
ffffffff810668f0-ffffffff8106696a: sgx_encl_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young(struct mm_struct *mm, struct sgx_encl_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070b70)
Location: arch/x86/kernel/cpu/sgx/encl.c:686
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
**Symbols:**

```
ffffffff81070b70-ffffffff81070bea: sgx_encl_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young(struct mm_struct *mm, struct sgx_encl_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107eaf0)
Location: arch/x86/kernel/cpu/sgx/encl.c:882
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
**Symbols:**

```
ffffffff8107eaf0-ffffffff8107eb82: sgx_encl_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young(struct mm_struct *mm, struct sgx_encl_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090130)
Location: arch/x86/kernel/cpu/sgx/encl.c:1113
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
**Symbols:**

```
ffffffff81090130-ffffffff810901ba: sgx_encl_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young(struct mm_struct *mm, struct sgx_encl_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093040)
Location: arch/x86/kernel/cpu/sgx/encl.c:1115
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
**Symbols:**

```
ffffffff81093040-ffffffff810930ce: sgx_encl_test_and_clear_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young(struct mm_struct *mm, struct sgx_encl_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a480)
Location: arch/x86/kernel/cpu/sgx/encl.c:1135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
**Symbols:**

```
ffffffff8109a480-ffffffff8109a50e: sgx_encl_test_and_clear_young (STB_GLOBAL)
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
