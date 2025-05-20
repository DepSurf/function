# Function: <code>trace_filemap_set_wb_err</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void trace_filemap_set_wb_err(struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b5870)
Location: include/trace/events/filemap.h:56
Inline: True
```
**Symbols:**

```
ffffffff811b5870-ffffffff811b58c8: trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void trace_filemap_set_wb_err(struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811c9960)
Location: include/trace/events/filemap.h:57
Inline: True
```
**Symbols:**

```
ffffffff811c9960-ffffffff811c99bf: trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void trace_filemap_set_wb_err(struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811eaac0)
Location: include/trace/events/filemap.h:57
Inline: True
```
**Symbols:**

```
ffffffff811eaac0-ffffffff811eab1f: trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void trace_filemap_set_wb_err(struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fb630)
Location: include/trace/events/filemap.h:57
Inline: True
```
**Symbols:**

```
ffffffff811fb630-ffffffff811fb68f: trace_filemap_set_wb_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void trace_filemap_set_wb_err(struct address_space *mapping, errseq_t eseq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81212e50)
Location: include/trace/events/filemap.h:57
Inline: True
```
**Symbols:**

```
ffffffff81212e50-ffffffff81212eaa: trace_filemap_set_wb_err (STB_LOCAL)
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
In mm/filemap.c (ffffffff81221467)
Location: include/trace/events/filemap.h:57
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124edba)
Location: include/trace/events/filemap.h:57
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_set_wb_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81258f77)
Location: include/trace/events/filemap.h:57
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_set_wb_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d267)
Location: include/trace/events/filemap.h:57
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_set_wb_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812991ba)
Location: include/trace/events/filemap.h:57
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_set_wb_err
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812ef9d9)
Location: include/trace/events/filemap.h:59
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_set_wb_err
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135a669)
Location: include/trace/events/filemap.h:59
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_set_wb_err
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138c0a9)
Location: include/trace/events/filemap.h:59
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_set_wb_err
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b5c19)
Location: include/trace/events/filemap.h:59
Inline: True
Inline callers:
  - mm/filemap.c:__filemap_set_wb_err
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
In mm/filemap.c (ffff8000102ae928)
Location: include/trace/events/filemap.h:57
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
In mm/filemap.c (c04db6ac)
Location: include/trace/events/filemap.h:57
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
In mm/filemap.c (c000000000363348)
Location: include/trace/events/filemap.h:57
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d4c46)
Location: include/trace/events/filemap.h:57
Inline: True
```
</details>
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
In mm/filemap.c (ffffffff81219ab7)
Location: include/trace/events/filemap.h:57
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
In mm/filemap.c (ffffffff8120ccc7)
Location: include/trace/events/filemap.h:57
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
In mm/filemap.c (ffffffff81217857)
Location: include/trace/events/filemap.h:57
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
In mm/filemap.c (ffffffff81226907)
Location: include/trace/events/filemap.h:57
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
