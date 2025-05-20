# Function: <code>copy_to_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81187070)
Location: kernel/events/uprobes.c:240
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
```
**Symbols:**

```
ffffffff81187070-ffffffff811870ef: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81199590)
Location: kernel/events/uprobes.c:242
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81199590-ffffffff81199608: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811a8f80)
Location: kernel/events/uprobes.c:242
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff811a8f80-ffffffff811a8ff5: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b04e0)
Location: kernel/events/uprobes.c:250
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff811b04e0-ffffffff811b0537: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811c3fe0)
Location: kernel/events/uprobes.c:250
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff811c3fe0-ffffffff811c4037: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811e4450)
Location: kernel/events/uprobes.c:250
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff811e4450-ffffffff811e44a7: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f4940)
Location: kernel/events/uprobes.c:260
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff811f4940-ffffffff811f4997: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120c630)
Location: kernel/events/uprobes.c:248
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff8120c630-ffffffff8120c685: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81219920)
Location: kernel/events/uprobes.c:257
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81219920-ffffffff81219975: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81245dc0)
Location: kernel/events/uprobes.c:251
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81245dc0-ffffffff81245e18: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81250430)
Location: kernel/events/uprobes.c:251
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81250430-ffffffff81250488: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812549d0)
Location: kernel/events/uprobes.c:251
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff812549d0-ffffffff81254a24: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81290410)
Location: kernel/events/uprobes.c:251
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81290410-ffffffff81290464: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e55c0)
Location: kernel/events/uprobes.c:245
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff812e55c0-ffffffff812e564b: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8134f110)
Location: kernel/events/uprobes.c:247
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff8134f110-ffffffff8134f189: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813802e0)
Location: kernel/events/uprobes.c:246
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff813802e0-ffffffff81380359: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813a91c0)
Location: kernel/events/uprobes.c:246
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff813a91c0-ffffffff813a9239: copy_to_page (STB_LOCAL)
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
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a4ac8)
Location: kernel/events/uprobes.c:257
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffff8000102a4ac8-ffff8000102a4b50: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d4168)
Location: kernel/events/uprobes.c:257
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
c04d4168-c04d41b0: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c000000000357480)
Location: kernel/events/uprobes.c:257
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
c000000000357480-c000000000357508: copy_to_page (STB_LOCAL)
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
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81211f70)
Location: kernel/events/uprobes.c:257
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81211f70-ffffffff81211fc5: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81204d00)
Location: kernel/events/uprobes.c:257
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81204d00-ffffffff81204d55: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120fd10)
Location: kernel/events/uprobes.c:257
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff8120fd10-ffffffff8120fd65: copy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void copy_to_page(struct page *page, long unsigned int vaddr, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121ecd0)
Location: kernel/events/uprobes.c:257
Inline: False
Direct callers:
  - kernel/events/uprobes.c:arch_uprobe_copy_ixol
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff8121ecd0-ffffffff8121ed3d: copy_to_page (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
