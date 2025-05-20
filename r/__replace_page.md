# Function: <code>__replace_page</code>

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
In kernel/events/uprobes.c (ffffffff8118753f)
Location: kernel/events/uprobes.c:152
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
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
In kernel/events/uprobes.c (ffffffff81199add)
Location: kernel/events/uprobes.c:152
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
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
In kernel/events/uprobes.c (ffffffff811a922f)
Location: kernel/events/uprobes.c:152
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
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
In kernel/events/uprobes.c (ffffffff811b079f)
Location: kernel/events/uprobes.c:154
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
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
In kernel/events/uprobes.c (ffffffff811c42af)
Location: kernel/events/uprobes.c:154
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
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
In kernel/events/uprobes.c (ffffffff811e4938)
Location: kernel/events/uprobes.c:154
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f5070)
Location: kernel/events/uprobes.c:164
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff811f5070-ffffffff811f53ec: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120cd60)
Location: kernel/events/uprobes.c:151
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff8120cd60-ffffffff8120d127: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121a050)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff8121a050-ffffffff8121a4b7: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812469e0)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff812469e0-ffffffff81246e64: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81251040)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81251040-ffffffff812514c3: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81255140)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81255140-ffffffff812555bf: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81290b80)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81290b80-ffffffff81291000: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e5d70)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff812e5d70-ffffffff812e64cd: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8134f9f0)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff8134f9f0-ffffffff8134ff88: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81380bc0)
Location: kernel/events/uprobes.c:153
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81380bc0-ffffffff81381153: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813a9fa0)
Location: kernel/events/uprobes.c:153
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff813a9fa0-ffffffff813aa502: __replace_page (STB_LOCAL)
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
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a5490)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffff8000102a5490-ffff8000102a5884: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d4864)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
c04d4864-c04d4cec: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c000000000358160)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
c000000000358160-c0000000003586f0: __replace_page (STB_LOCAL)
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
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812126a0)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff812126a0-ffffffff81212b07: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81205430)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81205430-ffffffff81205875: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81210440)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81210440-ffffffff812108a7: __replace_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __replace_page(struct vm_area_struct *vma, long unsigned int addr, struct page *old_page, struct page *new_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121f390)
Location: kernel/events/uprobes.c:154
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff8121f390-ffffffff8121f7b4: __replace_page (STB_LOCAL)
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
