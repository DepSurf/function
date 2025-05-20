# Function: <code>get_task_io_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff813bf180)
Location: block/blk-ioc.c:287
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - block/ioprio.c:set_task_ioprio
```
**Symbols:**

```
ffffffff813bf180-ffffffff813bf205: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814030d0)
Location: block/blk-ioc.c:287
Inline: False
Direct callers:
  - block/ioprio.c:set_task_ioprio
```
**Symbols:**

```
ffffffff814030d0-ffffffff81403153: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8141ce00)
Location: block/blk-ioc.c:287
Inline: False
Direct callers:
  - block/ioprio.c:set_task_ioprio
```
**Symbols:**

```
ffffffff8141ce00-ffffffff8141ce83: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8142ae60)
Location: block/blk-ioc.c:318
Inline: False
```
**Symbols:**

```
ffffffff8142ae60-ffffffff8142aee3: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81456050)
Location: block/blk-ioc.c:319
Inline: False
```
**Symbols:**

```
ffffffff81456050-ffffffff814560d3: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81489490)
Location: block/blk-ioc.c:319
Inline: True
```
**Symbols:**

```
ffffffff81489490-ffffffff81489513: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814a32e0)
Location: block/blk-ioc.c:296
Inline: False
```
**Symbols:**

```
ffffffff814a32e0-ffffffff814a3363: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814d13b0)
Location: block/blk-ioc.c:296
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff814d13b0-ffffffff814d1433: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814ea760)
Location: block/blk-ioc.c:296
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff814ea760-ffffffff814ea7e3: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81549700)
Location: block/blk-ioc.c:303
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - block/ioprio.c:set_task_ioprio
```
**Symbols:**

```
ffffffff81549700-ffffffff81549783: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81565530)
Location: block/blk-ioc.c:303
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - block/ioprio.c:set_task_ioprio
```
**Symbols:**

```
ffffffff81565530-ffffffff815655b3: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8156dba0)
Location: block/blk-ioc.c:303
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - block/ioprio.c:set_task_ioprio
```
**Symbols:**

```
ffffffff8156dba0-ffffffff8156dc23: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff815d2190)
Location: block/blk-ioc.c:303
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - block/ioprio.c:set_task_ioprio
```
**Symbols:**

```
ffffffff815d2190-ffffffff815d221b: get_task_io_context (STB_GLOBAL)
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
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffff8000105e8e58)
Location: block/blk-ioc.c:296
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffff8000105e8e58-ffff8000105e8f34: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (c0795584)
Location: block/blk-ioc.c:296
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c0795584-c0795628: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (c00000000077da50)
Location: block/blk-ioc.c:296
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
c00000000077da50-c00000000077db9c: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffe00042973c)
Location: block/blk-ioc.c:296
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffe00042973c-ffffffe000429846: get_task_io_context (STB_GLOBAL)
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
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814e2d40)
Location: block/blk-ioc.c:296
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff814e2d40-ffffffff814e2dc3: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814d36d0)
Location: block/blk-ioc.c:296
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff814d36d0-ffffffff814d3753: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814dedd0)
Location: block/blk-ioc.c:296
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff814dedd0-ffffffff814dee53: get_task_io_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct io_context *get_task_io_context(struct task_struct *task, gfp_t gfp_flags, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814f7c40)
Location: block/blk-ioc.c:296
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff814f7c40-ffffffff814f7cb0: get_task_io_context (STB_GLOBAL)
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
