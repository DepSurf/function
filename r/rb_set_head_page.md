# Function: <code>rb_set_head_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81146560)
Location: kernel/trace/ring_buffer.c:950
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81146560-ffffffff81146611: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114edb0)
Location: kernel/trace/ring_buffer.c:950
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff8114edb0-ffffffff8114ee61: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81158f50)
Location: kernel/trace/ring_buffer.c:948
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81158f50-ffffffff81159001: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115beb0)
Location: kernel/trace/ring_buffer.c:950
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff8115beb0-ffffffff8115bf36: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81168f70)
Location: kernel/trace/ring_buffer.c:953
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81168f70-ffffffff81168ff6: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81177c10)
Location: kernel/trace/ring_buffer.c:982
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81177c10-ffffffff81177c94: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811851b0)
Location: kernel/trace/ring_buffer.c:1029
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff811851b0-ffffffff81185234: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81192790)
Location: kernel/trace/ring_buffer.c:1006
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81192790-ffffffff81192838: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119e250)
Location: kernel/trace/ring_buffer.c:1007
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff8119e250-ffffffff8119e2cc: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4b70)
Location: kernel/trace/ring_buffer.c:1009
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_insert_pages
```
**Symbols:**

```
ffffffff811b4b70-ffffffff811b4bec: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2420)
Location: kernel/trace/ring_buffer.c:1253
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_insert_pages
```
**Symbols:**

```
ffffffff811b2420-ffffffff811b249c: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2f20)
Location: kernel/trace/ring_buffer.c:1336
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
```
**Symbols:**

```
ffffffff811b2f20-ffffffff811b2f9c: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dce50)
Location: kernel/trace/ring_buffer.c:1336
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
```
**Symbols:**

```
ffffffff811dce50-ffffffff811dcecc: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81213380)
Location: kernel/trace/ring_buffer.c:1372
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
```
**Symbols:**

```
ffffffff81213380-ffffffff81213428: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125cc10)
Location: kernel/trace/ring_buffer.c:1456
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
```
**Symbols:**

```
ffffffff8125cc10-ffffffff8125ccb8: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81273c00)
Location: kernel/trace/ring_buffer.c:1455
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
```
**Symbols:**

```
ffffffff81273c00-ffffffff81273ca8: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128e200)
Location: kernel/trace/ring_buffer.c:1287
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
```
**Symbols:**

```
ffffffff8128e200-ffffffff8128e2a8: rb_set_head_page (STB_LOCAL)
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
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff8000102180b8)
Location: kernel/trace/ring_buffer.c:1007
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffff8000102180b8-ffff8000102181b0: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c04560a8)
Location: kernel/trace/ring_buffer.c:1007
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
c04560a8-c04561e0: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0000000002996c0)
Location: kernel/trace/ring_buffer.c:1007
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
c0000000002996c0-c0000000002997b4: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000176a18)
Location: kernel/trace/ring_buffer.c:1007
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffe000176a18-ffffffe000176a92: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196870)
Location: kernel/trace/ring_buffer.c:1007
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81196870-ffffffff811968ec: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81189980)
Location: kernel/trace/ring_buffer.c:1007
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81189980-ffffffff811899fc: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81194640)
Location: kernel/trace/ring_buffer.c:1007
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81194640-ffffffff811946bc: rb_set_head_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_page *rb_set_head_page(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2250)
Location: kernel/trace/ring_buffer.c:1007
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_get_reader_page
  - kernel/trace/ring_buffer.c:rb_per_cpu_empty
  - kernel/trace/ring_buffer.c:rb_inc_iter
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff811a2250-ffffffff811a22cc: rb_set_head_page (STB_LOCAL)
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
