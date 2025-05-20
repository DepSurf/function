# Function: <code>build_probe_list</code>

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
In kernel/events/uprobes.c (ffffffff8118843d)
Location: kernel/events/uprobes.c:1015
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff8119aadf)
Location: kernel/events/uprobes.c:1017
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff811aa24f)
Location: kernel/events/uprobes.c:1018
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff811b181f)
Location: kernel/events/uprobes.c:1026
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff811c53ff)
Location: kernel/events/uprobes.c:1026
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff811e596b)
Location: kernel/events/uprobes.c:1025
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff811f637b)
Location: kernel/events/uprobes.c:1254
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff8120e10b)
Location: kernel/events/uprobes.c:1242
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff8121b74b)
Location: kernel/events/uprobes.c:1294
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void build_probe_list(struct inode *inode, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81246290)
Location: kernel/events/uprobes.c:1293
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff81246290-ffffffff81246458: build_probe_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void build_probe_list(struct inode *inode, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81250900)
Location: kernel/events/uprobes.c:1293
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
**Symbols:**

```
ffffffff81250900-ffffffff81250ac8: build_probe_list (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff81256526)
Location: kernel/events/uprobes.c:1291
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff812921f8)
Location: kernel/events/uprobes.c:1292
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff812e7ac1)
Location: kernel/events/uprobes.c:1287
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff813517ae)
Location: kernel/events/uprobes.c:1291
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff81382a27)
Location: kernel/events/uprobes.c:1288
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff813abdf7)
Location: kernel/events/uprobes.c:1288
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffff8000102a6f50)
Location: kernel/events/uprobes.c:1294
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (c04d6074)
Location: kernel/events/uprobes.c:1294
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c00000000035a210)
Location: kernel/events/uprobes.c:1294
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81213d9b)
Location: kernel/events/uprobes.c:1294
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff81206b0b)
Location: kernel/events/uprobes.c:1294
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff81211b3b)
Location: kernel/events/uprobes.c:1294
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
In kernel/events/uprobes.c (ffffffff81220a8b)
Location: kernel/events/uprobes.c:1294
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_mmap
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
</ul>
