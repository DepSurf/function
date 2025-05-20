# Function: <code>mmio_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff81158a00)
Location: kernel/trace/trace_mmiotrace.c:136
Inline: False
```
**Symbols:**

```
ffffffff81158a00-ffffffff81158bf6: mmio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff811632a0)
Location: kernel/trace/trace_mmiotrace.c:132
Inline: False
```
**Symbols:**

```
ffffffff811632a0-ffffffff811634a4: mmio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff8116e5d0)
Location: kernel/trace/trace_mmiotrace.c:132
Inline: False
```
**Symbols:**

```
ffffffff8116e5d0-ffffffff8116e7d4: mmio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff81171810)
Location: kernel/trace/trace_mmiotrace.c:132
Inline: False
```
**Symbols:**

```
ffffffff81171810-ffffffff811719fa: mmio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (ffffffff8117e9a0)
Location: kernel/trace/trace_mmiotrace.c:133
Inline: False
```
**Symbols:**

```
ffffffff8117e9a0-ffffffff8117eb8a: mmio_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:133
Inline: False
```
**Symbols:**

```
ffffffff8118dab0-ffffffff8118dc83: mmio_read (STB_LOCAL)
ffffffff8118dee3-ffffffff8118def4: mmio_read.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:133
Inline: False
```
**Symbols:**

```
ffffffff8119b490-ffffffff8119b663: mmio_read (STB_LOCAL)
ffffffff8119b863-ffffffff8119b874: mmio_read.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:133
Inline: False
```
**Symbols:**

```
ffffffff811a9050-ffffffff811a922f: mmio_read (STB_LOCAL)
ffffffff811a9469-ffffffff811a947a: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:133
Inline: False
```
**Symbols:**

```
ffffffff811b4880-ffffffff811b4a5f: mmio_read (STB_LOCAL)
ffffffff811b4c53-ffffffff811b4c64: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:133
Inline: False
```
**Symbols:**

```
ffffffff811cd280-ffffffff811cd37b: mmio_read (STB_LOCAL)
ffffffff811cd613-ffffffff811cd624: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:133
Inline: False
```
**Symbols:**

```
ffffffff811ca770-ffffffff811ca86b: mmio_read (STB_LOCAL)
ffffffff81be5d25-ffffffff81be5d36: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:131
Inline: False
```
**Symbols:**

```
ffffffff811cba10-ffffffff811cbbfb: mmio_read (STB_LOCAL)
ffffffff81bd7b3e-ffffffff81bd7b4f: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:131
Inline: False
```
**Symbols:**

```
ffffffff811f7ea0-ffffffff811f8192: mmio_read (STB_LOCAL)
ffffffff81cb603c-ffffffff81cb6061: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
bool mmio_read(int size, long unsigned int addr, long unsigned int *val);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff810033a1)
Location: arch/x86/coco/tdx/tdx.c:320
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:131
Inline: False
```
**Symbols:**

```
ffffffff81231b50-ffffffff81231e43: mmio_read (STB_LOCAL)
ffffffff81e67058-ffffffff81e6707d: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
bool mmio_read(int size, long unsigned int addr, long unsigned int *val);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81003ba1)
Location: arch/x86/coco/tdx/tdx.c:362
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:131
Inline: False
```
**Symbols:**

```
ffffffff8127e160-ffffffff8127e45d: mmio_read (STB_LOCAL)
ffffffff8205debc-ffffffff8205ded0: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
bool mmio_read(int size, long unsigned int addr, long unsigned int *val);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81002d30)
Location: arch/x86/coco/tdx/tdx.c:356
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:131
Inline: False
```
**Symbols:**

```
ffffffff81002d30-ffffffff81002dbe: mmio_read (STB_LOCAL)
ffffffff8129abe0-ffffffff8129aedd: mmio_read (STB_LOCAL)
ffffffff820dc95b-ffffffff820dc96f: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
bool mmio_read(int size, long unsigned int addr, long unsigned int *val);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81002f10)
Location: arch/x86/coco/tdx/tdx.c:380
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
```
```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:131
Inline: False
```
**Symbols:**

```
ffffffff81002f10-ffffffff81002f9e: mmio_read (STB_LOCAL)
ffffffff812b6260-ffffffff812b655c: mmio_read (STB_LOCAL)
ffffffff821b875d-ffffffff821b8771: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:133
Inline: False
```
**Symbols:**

```
ffffffff811acea0-ffffffff811ad07f: mmio_read (STB_LOCAL)
ffffffff811ad273-ffffffff811ad284: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:133
Inline: False
```
**Symbols:**

```
ffffffff8119fd30-ffffffff8119ff0f: mmio_read (STB_LOCAL)
ffffffff811a0103-ffffffff811a0114: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:133
Inline: False
```
**Symbols:**

```
ffffffff811aac70-ffffffff811aae4f: mmio_read (STB_LOCAL)
ffffffff811ab043-ffffffff811ab054: mmio_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t mmio_read(struct trace_iterator *iter, struct file *filp, char *ubuf, size_t cnt, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_mmiotrace.c (0)
Location: kernel/trace/trace_mmiotrace.c:133
Inline: False
```
**Symbols:**

```
ffffffff811b8ad0-ffffffff811b8caf: mmio_read (STB_LOCAL)
ffffffff811b8eb3-ffffffff811b8ec4: mmio_read.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int size</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int *val</code>
</li>
<li>
<b>Param removed. </b>
<code>struct trace_iterator *iter</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *filp</code>
</li>
<li>
<b>Param removed. </b>
<code>char *ubuf</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t cnt</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t *ppos</code>
</li>
<li>
<b>Return type changed. </b>
<code>ssize_t</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
