# Function: <code>alloc_uprobe</code>

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
In kernel/events/uprobes.c (ffffffff8118802c)
Location: kernel/events/uprobes.c:475
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
In kernel/events/uprobes.c (ffffffff8119a6cc)
Location: kernel/events/uprobes.c:477
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
In kernel/events/uprobes.c (ffffffff811a9e3c)
Location: kernel/events/uprobes.c:478
Inline: True
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
In kernel/events/uprobes.c (ffffffff811b1447)
Location: kernel/events/uprobes.c:486
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
In kernel/events/uprobes.c (ffffffff811c5027)
Location: kernel/events/uprobes.c:486
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
In kernel/events/uprobes.c (ffffffff811e5567)
Location: kernel/events/uprobes.c:486
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
In kernel/events/uprobes.c (ffffffff811f5f52)
Location: kernel/events/uprobes.c:694
Inline: True
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
In kernel/events/uprobes.c (ffffffff8120dcda)
Location: kernel/events/uprobes.c:682
Inline: True
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
In kernel/events/uprobes.c (ffffffff8121b30a)
Location: kernel/events/uprobes.c:734
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct uprobe *alloc_uprobe(struct inode *inode, loff_t offset, loff_t ref_ctr_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:728
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
```
**Symbols:**

```
ffffffff81246460-ffffffff81246625: alloc_uprobe (STB_LOCAL)
ffffffff812490e4-ffffffff8124911e: alloc_uprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct uprobe *alloc_uprobe(struct inode *inode, loff_t offset, loff_t ref_ctr_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:728
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
```
**Symbols:**

```
ffffffff81250ad0-ffffffff81250c95: alloc_uprobe (STB_LOCAL)
ffffffff81be681f-ffffffff81be6859: alloc_uprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct uprobe *alloc_uprobe(struct inode *inode, loff_t offset, loff_t ref_ctr_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:726
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
```
**Symbols:**

```
ffffffff81254f90-ffffffff81255140: alloc_uprobe (STB_LOCAL)
ffffffff81bd854d-ffffffff81bd8587: alloc_uprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct uprobe *alloc_uprobe(struct inode *inode, loff_t offset, loff_t ref_ctr_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:727
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
```
**Symbols:**

```
ffffffff812909d0-ffffffff81290b80: alloc_uprobe (STB_LOCAL)
ffffffff81cb9a74-ffffffff81cb9aae: alloc_uprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct uprobe *alloc_uprobe(struct inode *inode, loff_t offset, loff_t ref_ctr_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:721
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
```
**Symbols:**

```
ffffffff812e5800-ffffffff812e59f8: alloc_uprobe (STB_LOCAL)
ffffffff81e6b03f-ffffffff81e6b07b: alloc_uprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct uprobe *alloc_uprobe(struct inode *inode, loff_t offset, loff_t ref_ctr_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8134f370)
Location: kernel/events/uprobes.c:724
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
```
**Symbols:**

```
ffffffff8134f370-ffffffff8134f5c2: alloc_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct uprobe *alloc_uprobe(struct inode *inode, loff_t offset, loff_t ref_ctr_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81380540)
Location: kernel/events/uprobes.c:721
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
```
**Symbols:**

```
ffffffff81380540-ffffffff81380792: alloc_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct uprobe *alloc_uprobe(struct inode *inode, loff_t offset, loff_t ref_ctr_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813a98c0)
Location: kernel/events/uprobes.c:721
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
```
**Symbols:**

```
ffffffff813a98c0-ffffffff813a9b41: alloc_uprobe (STB_LOCAL)
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
In kernel/events/uprobes.c (ffff8000102a6a34)
Location: kernel/events/uprobes.c:734
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
In kernel/events/uprobes.c (c04d5bac)
Location: kernel/events/uprobes.c:734
Inline: True
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
In kernel/events/uprobes.c (c000000000359c20)
Location: kernel/events/uprobes.c:734
Inline: True
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
In kernel/events/uprobes.c (ffffffff8121395a)
Location: kernel/events/uprobes.c:734
Inline: True
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
In kernel/events/uprobes.c (ffffffff812066ca)
Location: kernel/events/uprobes.c:734
Inline: True
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
In kernel/events/uprobes.c (ffffffff812116fa)
Location: kernel/events/uprobes.c:734
Inline: True
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
In kernel/events/uprobes.c (ffffffff8122064c)
Location: kernel/events/uprobes.c:734
Inline: True
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
