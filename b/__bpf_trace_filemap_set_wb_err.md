# Function: <code>__bpf_trace_filemap_set_wb_err</code>

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
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eb210)
Location: include/trace/events/filemap.h:57
Inline: False
```
**Symbols:**

```
ffffffff811eb210-ffffffff811eb21d: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fbd80)
Location: include/trace/events/filemap.h:57
Inline: False
```
**Symbols:**

```
ffffffff811fbd80-ffffffff811fbd8d: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213460)
Location: include/trace/events/filemap.h:57
Inline: False
```
**Symbols:**

```
ffffffff81213460-ffffffff8121346d: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81220c20)
Location: include/trace/events/filemap.h:57
Inline: False
```
**Symbols:**

```
ffffffff81220c20-ffffffff81220c2d: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124dfc0)
Location: include/trace/events/filemap.h:57
Inline: True
```
**Symbols:**

```
ffffffff8124dfc0-ffffffff8124dfcd: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81258510)
Location: include/trace/events/filemap.h:57
Inline: True
```
**Symbols:**

```
ffffffff81258510-ffffffff8125851d: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125caf0)
Location: include/trace/events/filemap.h:57
Inline: True
```
**Symbols:**

```
ffffffff8125caf0-ffffffff8125cafd: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812989b0)
Location: include/trace/events/filemap.h:57
Inline: True
```
**Symbols:**

```
ffffffff812989b0-ffffffff812989bd: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812eefd0)
Location: include/trace/events/filemap.h:59
Inline: True
```
**Symbols:**

```
ffffffff812eefd0-ffffffff812eefe7: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81359870)
Location: include/trace/events/filemap.h:59
Inline: True
```
**Symbols:**

```
ffffffff81359870-ffffffff81359887: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138b1c0)
Location: include/trace/events/filemap.h:59
Inline: True
```
**Symbols:**

```
ffffffff8138b1c0-ffffffff8138b1d7: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b4ce0)
Location: include/trace/events/filemap.h:59
Inline: True
```
**Symbols:**

```
ffffffff813b4ce0-ffffffff813b4cf7: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
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
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102adc08)
Location: include/trace/events/filemap.h:57
Inline: False
```
**Symbols:**

```
ffff8000102adc08-ffff8000102adc20: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04da8a0)
Location: include/trace/events/filemap.h:57
Inline: False
```
**Symbols:**

```
c04da8a0-c04da8c8: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c0000000003620b0)
Location: include/trace/events/filemap.h:57
Inline: False
```
**Symbols:**

```
c0000000003620b0-c0000000003620dc: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
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
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219270)
Location: include/trace/events/filemap.h:57
Inline: False
```
**Symbols:**

```
ffffffff81219270-ffffffff8121927d: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120c480)
Location: include/trace/events/filemap.h:57
Inline: False
```
**Symbols:**

```
ffffffff8120c480-ffffffff8120c48d: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81217010)
Location: include/trace/events/filemap.h:57
Inline: False
```
**Symbols:**

```
ffffffff81217010-ffffffff8121701d: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_filemap_set_wb_err(void *__data, struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226090)
Location: include/trace/events/filemap.h:57
Inline: False
```
**Symbols:**

```
ffffffff81226090-ffffffff8122609d: __bpf_trace_filemap_set_wb_err (STB_LOCAL)
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
