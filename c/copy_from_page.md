# Function: <code>copy_from_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81186ff0)
Location: kernel/events/uprobes.c:233
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81186ff0-ffffffff8118706c: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81199510)
Location: kernel/events/uprobes.c:235
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81199510-ffffffff81199585: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811a8f00)
Location: kernel/events/uprobes.c:235
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff811a8f00-ffffffff811a8f72: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b0430)
Location: kernel/events/uprobes.c:243
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff811b0430-ffffffff811b04d9: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811c3f30)
Location: kernel/events/uprobes.c:243
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff811c3f30-ffffffff811c3fd9: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811e43a0)
Location: kernel/events/uprobes.c:243
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff811e43a0-ffffffff811e4449: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f4890)
Location: kernel/events/uprobes.c:253
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff811f4890-ffffffff811f4939: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120c5d0)
Location: kernel/events/uprobes.c:241
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff8120c5d0-ffffffff8120c621: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812198c0)
Location: kernel/events/uprobes.c:250
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff812198c0-ffffffff81219911: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81245d10)
Location: kernel/events/uprobes.c:244
Inline: False
Direct callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:copy_insn
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81245d10-ffffffff81245db9: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81250380)
Location: kernel/events/uprobes.c:244
Inline: False
Direct callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:copy_insn
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81250380-ffffffff81250429: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81254a30)
Location: kernel/events/uprobes.c:244
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81254a30-ffffffff81254adc: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81290470)
Location: kernel/events/uprobes.c:244
Inline: False
Direct callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81290470-ffffffff8129051c: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e5650)
Location: kernel/events/uprobes.c:238
Inline: False
Direct callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff812e5650-ffffffff812e572e: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8134f1a0)
Location: kernel/events/uprobes.c:240
Inline: False
Direct callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff8134f1a0-ffffffff8134f27e: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81380370)
Location: kernel/events/uprobes.c:239
Inline: False
Direct callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81380370-ffffffff8138044e: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813a9690)
Location: kernel/events/uprobes.c:239
Inline: False
Direct callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff813a9690-ffffffff813a976e: copy_from_page (STB_LOCAL)
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
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a4a40)
Location: kernel/events/uprobes.c:250
Inline: False
Direct callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffff8000102a4a40-ffff8000102a4ac8: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d411c)
Location: kernel/events/uprobes.c:250
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
c04d411c-c04d4168: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c0000000003573f0)
Location: kernel/events/uprobes.c:250
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
c0000000003573f0-c000000000357478: copy_from_page (STB_LOCAL)
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
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81211f10)
Location: kernel/events/uprobes.c:250
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81211f10-ffffffff81211f61: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81204ca0)
Location: kernel/events/uprobes.c:250
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff81204ca0-ffffffff81204cf1: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120fcb0)
Location: kernel/events/uprobes.c:250
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff8120fcb0-ffffffff8120fd01: copy_from_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void copy_from_page(struct page *page, long unsigned int vaddr, void *dst, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121ec60)
Location: kernel/events/uprobes.c:250
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
**Symbols:**

```
ffffffff8121ec60-ffffffff8121ecc9: copy_from_page (STB_LOCAL)
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
