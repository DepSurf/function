# Function: <code>drop_mm_ref_this_cpu</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020110)
Location: arch/x86/xen/mmu_pv.c:978
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff81020110-ffffffff81020175: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020d90)
Location: arch/x86/xen/mmu_pv.c:952
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff81020d90-ffffffff81020df5: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021880)
Location: arch/x86/xen/mmu_pv.c:981
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff81021880-ffffffff810218e5: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810210f0)
Location: arch/x86/xen/mmu_pv.c:991
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff810210f0-ffffffff81021155: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81022bd0)
Location: arch/x86/xen/mmu_pv.c:991
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff81022bd0-ffffffff81022c35: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023510)
Location: arch/x86/xen/mmu_pv.c:991
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff81023510-ffffffff81023575: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025b90)
Location: arch/x86/xen/mmu_pv.c:991
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
**Symbols:**

```
ffffffff81025b90-ffffffff81025bfb: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810262b0)
Location: arch/x86/xen/mmu_pv.c:896
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
**Symbols:**

```
ffffffff810262b0-ffffffff8102631b: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810281d0)
Location: arch/x86/xen/mmu_pv.c:896
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
**Symbols:**

```
ffffffff810281d0-ffffffff8102823b: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102c830)
Location: arch/x86/xen/mmu_pv.c:896
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
**Symbols:**

```
ffffffff8102c830-ffffffff8102c89b: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81031630)
Location: arch/x86/xen/mmu_pv.c:902
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
**Symbols:**

```
ffffffff81031630-ffffffff810316b3: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81038e20)
Location: arch/x86/xen/mmu_pv.c:902
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
**Symbols:**

```
ffffffff81038e20-ffffffff81038ea3: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81038d50)
Location: arch/x86/xen/mmu_pv.c:911
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
**Symbols:**

```
ffffffff81038d50-ffffffff81038dd6: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103f190)
Location: arch/x86/xen/mmu_pv.c:911
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
```
**Symbols:**

```
ffffffff8103f190-ffffffff8103f216: drop_mm_ref_this_cpu (STB_LOCAL)
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
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023670)
Location: arch/x86/xen/mmu_pv.c:991
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff81023670-ffffffff810236d5: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810234d0)
Location: arch/x86/xen/mmu_pv.c:991
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff810234d0-ffffffff81023535: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void drop_mm_ref_this_cpu(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023980)
Location: arch/x86/xen/mmu_pv.c:991
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_exit_mmap
```
**Symbols:**

```
ffffffff81023980-ffffffff810239e5: drop_mm_ref_this_cpu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
