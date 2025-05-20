# Function: <code>hugetlb_handle_userfault</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812da180)
Location: mm/hugetlb.c:4535
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff812da180-ffffffff812da23a: hugetlb_handle_userfault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81320f40)
Location: mm/hugetlb.c:4840
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff81320f40-ffffffff81320ffa: hugetlb_handle_userfault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int addr, long unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138dcf0)
Location: mm/hugetlb.c:5456
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff8138dcf0-ffffffff8138ddc2: hugetlb_handle_userfault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int addr, long unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8140ca60)
Location: mm/hugetlb.c:5696
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff8140ca60-ffffffff8140cb1e: hugetlb_handle_userfault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int addr, long unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8143fe80)
Location: mm/hugetlb.c:5795
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff8143fe80-ffffffff8143ff3e: hugetlb_handle_userfault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t hugetlb_handle_userfault(struct vm_area_struct *vma, struct address_space *mapping, long unsigned int idx, unsigned int flags, long unsigned int haddr, long unsigned int addr, long unsigned int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81479d30)
Location: mm/hugetlb.c:6063
Inline: False
Direct callers:
  - mm/hugetlb.c:hugetlb_no_page
```
**Symbols:**

```
ffffffff81479d30-ffffffff81479dda: hugetlb_handle_userfault (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, mapping, idx, flags, haddr, reason</code> ➡️ <code>vma, mapping, idx, flags, haddr, addr, reason</code>
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
