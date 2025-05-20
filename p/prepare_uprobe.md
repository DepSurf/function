# Function: <code>prepare_uprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int prepare_uprobe(struct uprobe *uprobe, struct file *file, struct mm_struct *mm, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81187380)
Location: kernel/events/uprobes.c:579
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff81187380-ffffffff8118752e: prepare_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int prepare_uprobe(struct uprobe *uprobe, struct file *file, struct mm_struct *mm, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811998d0)
Location: kernel/events/uprobes.c:581
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff811998d0-ffffffff81199ac2: prepare_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int prepare_uprobe(struct uprobe *uprobe, struct file *file, struct mm_struct *mm, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811a9030)
Location: kernel/events/uprobes.c:582
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff811a9030-ffffffff811a921c: prepare_uprobe (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff811b0cf3)
Location: kernel/events/uprobes.c:590
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
In kernel/events/uprobes.c (ffffffff811c4883)
Location: kernel/events/uprobes.c:590
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
In kernel/events/uprobes.c (ffffffff811e4da5)
Location: kernel/events/uprobes.c:589
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int prepare_uprobe(struct uprobe *uprobe, struct file *file, struct mm_struct *mm, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f5420)
Location: kernel/events/uprobes.c:805
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff811f5420-ffffffff811f55fc: prepare_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int prepare_uprobe(struct uprobe *uprobe, struct file *file, struct mm_struct *mm, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120d160)
Location: kernel/events/uprobes.c:793
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff8120d160-ffffffff8120d36d: prepare_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int prepare_uprobe(struct uprobe *uprobe, struct file *file, struct mm_struct *mm, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121a4f0)
Location: kernel/events/uprobes.c:845
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff8121a4f0-ffffffff8121a6fd: prepare_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81247725)
Location: kernel/events/uprobes.c:839
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81251dab)
Location: kernel/events/uprobes.c:839
Inline: True
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
In kernel/events/uprobes.c (ffffffff81255bfb)
Location: kernel/events/uprobes.c:837
Inline: True
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
In kernel/events/uprobes.c (ffffffff812918ab)
Location: kernel/events/uprobes.c:838
Inline: True
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
In kernel/events/uprobes.c (ffffffff812e6ff9)
Location: kernel/events/uprobes.c:832
Inline: True
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
In kernel/events/uprobes.c (ffffffff81350af9)
Location: kernel/events/uprobes.c:835
Inline: True
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
In kernel/events/uprobes.c (ffffffff81381d59)
Location: kernel/events/uprobes.c:832
Inline: True
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
In kernel/events/uprobes.c (ffffffff813ab139)
Location: kernel/events/uprobes.c:832
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a60c8)
Location: kernel/events/uprobes.c:845
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d5254)
Location: kernel/events/uprobes.c:845
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int prepare_uprobe(struct uprobe *uprobe, struct file *file, struct mm_struct *mm, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c000000000358760)
Location: kernel/events/uprobes.c:845
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
c000000000358760-c000000000358a58: prepare_uprobe (STB_LOCAL)
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
int prepare_uprobe(struct uprobe *uprobe, struct file *file, struct mm_struct *mm, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81212b40)
Location: kernel/events/uprobes.c:845
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff81212b40-ffffffff81212d4d: prepare_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int prepare_uprobe(struct uprobe *uprobe, struct file *file, struct mm_struct *mm, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812058b0)
Location: kernel/events/uprobes.c:845
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff812058b0-ffffffff81205abd: prepare_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int prepare_uprobe(struct uprobe *uprobe, struct file *file, struct mm_struct *mm, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812108e0)
Location: kernel/events/uprobes.c:845
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff812108e0-ffffffff81210aed: prepare_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int prepare_uprobe(struct uprobe *uprobe, struct file *file, struct mm_struct *mm, long unsigned int vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121f7f0)
Location: kernel/events/uprobes.c:845
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff8121f7f0-ffffffff8121f9fd: prepare_uprobe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
