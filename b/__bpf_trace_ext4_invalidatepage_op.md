# Function: <code>__bpf_trace_ext4_invalidatepage_op</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137d390)
Location: include/trace/events/ext4.h:548
Inline: False
```
**Symbols:**

```
ffffffff8137d390-ffffffff8137d39f: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81395af0)
Location: include/trace/events/ext4.h:569
Inline: False
```
**Symbols:**

```
ffffffff81395af0-ffffffff81395aff: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813bfa50)
Location: include/trace/events/ext4.h:569
Inline: False
```
**Symbols:**

```
ffffffff813bfa50-ffffffff813bfa5f: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8d20)
Location: include/trace/events/ext4.h:569
Inline: False
```
**Symbols:**

```
ffffffff813d8d20-ffffffff813d8d2f: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81425280)
Location: include/trace/events/ext4.h:589
Inline: True
```
**Symbols:**

```
ffffffff81425280-ffffffff8142528f: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cc20)
Location: include/trace/events/ext4.h:600
Inline: True
```
**Symbols:**

```
ffffffff8143cc20-ffffffff8143cc2f: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442ae0)
Location: include/trace/events/ext4.h:600
Inline: True
```
**Symbols:**

```
ffffffff81442ae0-ffffffff81442aef: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81496780)
Location: include/trace/events/ext4.h:600
Inline: True
```
**Symbols:**

```
ffffffff81496780-ffffffff8149678f: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
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
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ac298)
Location: include/trace/events/ext4.h:569
Inline: False
```
**Symbols:**

```
ffff8000104ac298-ffff8000104ac2b4: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0674318)
Location: include/trace/events/ext4.h:569
Inline: False
```
**Symbols:**

```
c0674318-c0674350: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e3d40)
Location: include/trace/events/ext4.h:569
Inline: False
```
**Symbols:**

```
c0000000005e3d40-c0000000005e3d6c: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
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
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d1300)
Location: include/trace/events/ext4.h:569
Inline: False
```
**Symbols:**

```
ffffffff813d1300-ffffffff813d130f: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c1d80)
Location: include/trace/events/ext4.h:569
Inline: False
```
**Symbols:**

```
ffffffff813c1d80-ffffffff813c1d8f: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ce790)
Location: include/trace/events/ext4.h:569
Inline: False
```
**Symbols:**

```
ffffffff813ce790-ffffffff813ce79f: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_ext4_invalidatepage_op(void *__data, struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e39e0)
Location: include/trace/events/ext4.h:569
Inline: False
```
**Symbols:**

```
ffffffff813e39e0-ffffffff813e39ef: __bpf_trace_ext4_invalidatepage_op (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
