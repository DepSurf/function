# Function: <code>attach_nobh_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81244010)
Location: fs/buffer.c:2479
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff81244010-ffffffff81244094: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126bd30)
Location: fs/buffer.c:2535
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff8126bd30-ffffffff8126bde4: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127f0a0)
Location: fs/buffer.c:2576
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff8127f0a0-ffffffff8127f154: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128c6e0)
Location: fs/buffer.c:2570
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff8128c6e0-ffffffff8128c77b: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812af500)
Location: fs/buffer.c:2530
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff812af500-ffffffff812af59e: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d7290)
Location: fs/buffer.c:2501
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff812d7290-ffffffff812d733b: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ec6c0)
Location: fs/buffer.c:2513
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff812ec6c0-ffffffff812ec76e: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130de40)
Location: fs/buffer.c:2510
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff8130de40-ffffffff8130deee: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81320e40)
Location: fs/buffer.c:2510
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff81320e40-ffffffff81320eee: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8135a510)
Location: fs/buffer.c:2554
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff8135a510-ffffffff8135a586: attach_nobh_buffers.part.0 (STB_LOCAL)
ffffffff8135a590-ffffffff8135a5dc: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff81368640)
Location: fs/buffer.c:2553
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff81368640-ffffffff813686b6: attach_nobh_buffers.part.0 (STB_LOCAL)
ffffffff813686c0-ffffffff8136870c: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136fad0)
Location: fs/buffer.c:2574
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff8136fad0-ffffffff8136fb78: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813be650)
Location: fs/buffer.c:2553
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff813be650-ffffffff813be6fe: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814448e0)
Location: fs/buffer.c:2552
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff814448e0-ffffffff81444a64: attach_nobh_buffers (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d83b0)
Location: fs/buffer.c:2510
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffff8000103d83b0-ffff8000103d8518: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b26b4)
Location: fs/buffer.c:2510
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
c05b26b4-c05b27b4: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dbaa0)
Location: fs/buffer.c:2510
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
c0000000004dbaa0-c0000000004dbc5c: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe0002925c8)
Location: fs/buffer.c:2510
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffe0002925c8-ffffffe0002926b4: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81319420)
Location: fs/buffer.c:2510
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff81319420-ffffffff813194ce: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81309fe0)
Location: fs/buffer.c:2510
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff81309fe0-ffffffff8130a08e: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81316ef0)
Location: fs/buffer.c:2510
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff81316ef0-ffffffff81316f9e: attach_nobh_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void attach_nobh_buffers(struct page *page, struct buffer_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81328b80)
Location: fs/buffer.c:2510
Inline: True
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
```
**Symbols:**

```
ffffffff81328b80-ffffffff81328c2c: attach_nobh_buffers (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
