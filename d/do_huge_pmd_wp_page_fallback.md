# Function: <code>do_huge_pmd_wp_page_fallback</code>

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
In mm/huge_memory.c (ffffffff811f863d)
Location: mm/huge_memory.c:1042
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In mm/huge_memory.c (ffffffff81216af1)
Location: mm/huge_memory.c:829
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In mm/huge_memory.c (ffffffff812290b1)
Location: mm/huge_memory.c:909
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In mm/huge_memory.c (ffffffff81234df5)
Location: mm/huge_memory.c:1112
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
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
In mm/huge_memory.c (ffffffff81253729)
Location: mm/huge_memory.c:1124
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_huge_pmd_wp_page_fallback(struct vm_fault *vmf, pmd_t orig_pmd, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81273820)
Location: mm/huge_memory.c:1121
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81273820-ffffffff81273f00: do_huge_pmd_wp_page_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault *vmf, pmd_t orig_pmd, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81287db0)
Location: mm/huge_memory.c:1136
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff81287db0-ffffffff812884c2: do_huge_pmd_wp_page_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault *vmf, pmd_t orig_pmd, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a29d0)
Location: mm/huge_memory.c:1192
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812a29d0-ffffffff812a3112: do_huge_pmd_wp_page_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault *vmf, pmd_t orig_pmd, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b3ec0)
Location: mm/huge_memory.c:1198
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812b3ec0-ffffffff812b461f: do_huge_pmd_wp_page_fallback (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault *vmf, pmd_t orig_pmd, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010355570)
Location: mm/huge_memory.c:1198
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffff800010355570-ffff800010355bf0: do_huge_pmd_wp_page_fallback (STB_LOCAL)
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
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault *vmf, pmd_t orig_pmd, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043cb20)
Location: mm/huge_memory.c:1198
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
c00000000043cb20-c00000000043d510: do_huge_pmd_wp_page_fallback (STB_LOCAL)
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
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault *vmf, pmd_t orig_pmd, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ac4a0)
Location: mm/huge_memory.c:1198
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812ac4a0-ffffffff812acbff: do_huge_pmd_wp_page_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault *vmf, pmd_t orig_pmd, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129e550)
Location: mm/huge_memory.c:1198
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff8129e550-ffffffff8129ec48: do_huge_pmd_wp_page_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault *vmf, pmd_t orig_pmd, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812aa2b0)
Location: mm/huge_memory.c:1198
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812aa2b0-ffffffff812aaa0f: do_huge_pmd_wp_page_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t do_huge_pmd_wp_page_fallback(struct vm_fault *vmf, pmd_t orig_pmd, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ba5d0)
Location: mm/huge_memory.c:1198
Inline: False
Direct callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff812ba5d0-ffffffff812bad56: do_huge_pmd_wp_page_fallback (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
