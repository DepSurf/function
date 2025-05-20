# Function: <code>__bpf_trace_writeback_page_template</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fcec0)
Location: include/trace/events/writeback.h:56
Inline: False
```
**Symbols:**

```
ffffffff812fcec0-ffffffff812fcecb: __bpf_trace_writeback_page_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130f370)
Location: include/trace/events/writeback.h:56
Inline: False
```
**Symbols:**

```
ffffffff8130f370-ffffffff8130f37b: __bpf_trace_writeback_page_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81348b70)
Location: include/trace/events/writeback.h:55
Inline: True
```
**Symbols:**

```
ffffffff81348b70-ffffffff81348b7b: __bpf_trace_writeback_page_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81355b00)
Location: include/trace/events/writeback.h:54
Inline: True
```
**Symbols:**

```
ffffffff81355b00-ffffffff81355b0b: __bpf_trace_writeback_page_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135c790)
Location: include/trace/events/writeback.h:54
Inline: True
```
**Symbols:**

```
ffffffff8135c790-ffffffff8135c79b: __bpf_trace_writeback_page_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813aac30)
Location: include/trace/events/writeback.h:55
Inline: True
```
**Symbols:**

```
ffffffff813aac30-ffffffff813aac3b: __bpf_trace_writeback_page_template (STB_LOCAL)
```
</details>
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
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c3050)
Location: include/trace/events/writeback.h:56
Inline: False
```
**Symbols:**

```
ffff8000103c3050-ffff8000103c3064: __bpf_trace_writeback_page_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a09b4)
Location: include/trace/events/writeback.h:56
Inline: False
```
**Symbols:**

```
c05a09b4-c05a09dc: __bpf_trace_writeback_page_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004c4280)
Location: include/trace/events/writeback.h:56
Inline: False
```
**Symbols:**

```
c0000000004c4280-c0000000004c42ac: __bpf_trace_writeback_page_template (STB_LOCAL)
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
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81307950)
Location: include/trace/events/writeback.h:56
Inline: False
```
**Symbols:**

```
ffffffff81307950-ffffffff8130795b: __bpf_trace_writeback_page_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812f8570)
Location: include/trace/events/writeback.h:56
Inline: False
```
**Symbols:**

```
ffffffff812f8570-ffffffff812f857b: __bpf_trace_writeback_page_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81305740)
Location: include/trace/events/writeback.h:56
Inline: False
```
**Symbols:**

```
ffffffff81305740-ffffffff8130574b: __bpf_trace_writeback_page_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_writeback_page_template(void *__data, struct page *page, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81316ab0)
Location: include/trace/events/writeback.h:56
Inline: False
```
**Symbols:**

```
ffffffff81316ab0-ffffffff81316abb: __bpf_trace_writeback_page_template (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
