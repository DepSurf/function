# Function: <code>add_to_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81201990)
Location: mm/memory-failure.c:280
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81201990-ffffffff81201a54: add_to_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812260d0)
Location: mm/memory-failure.c:279
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812260d0-ffffffff81226196: add_to_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812386a0)
Location: mm/memory-failure.c:279
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812386a0-ffffffff81238763: add_to_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81244170)
Location: mm/memory-failure.c:282
Inline: False
```
**Symbols:**

```
ffffffff81244170-ffffffff81244231: add_to_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81263ff0)
Location: mm/memory-failure.c:282
Inline: False
```
**Symbols:**

```
ffffffff81263ff0-ffffffff812640b1: add_to_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:311
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff812888e0-ffffffff81288c51: add_to_kill (STB_LOCAL)
ffffffff8128aa24-ffffffff8128aa35: add_to_kill.cold.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:312
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff8129d5e0-ffffffff8129d954: add_to_kill (STB_LOCAL)
ffffffff8129f93e-ffffffff8129f94f: add_to_kill.cold.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:309
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff812b8c10-ffffffff812b8d11: add_to_kill (STB_LOCAL)
ffffffff812babcf-ffffffff812bac0a: add_to_kill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:308
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff812caaf0-ffffffff812cac06: add_to_kill (STB_LOCAL)
ffffffff812ccaab-ffffffff812ccae2: add_to_kill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:308
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
```
**Symbols:**

```
ffffffff81300930-ffffffff81300a58: add_to_kill (STB_LOCAL)
ffffffff81302cc6-ffffffff81302cfd: add_to_kill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:332
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
```
**Symbols:**

```
ffffffff8130cad0-ffffffff8130cbf8: add_to_kill (STB_LOCAL)
ffffffff81bea001-ffffffff81bea038: add_to_kill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:336
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff81313230-ffffffff81313355: add_to_kill (STB_LOCAL)
ffffffff81bdc01d-ffffffff81bdc054: add_to_kill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:348
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff8135fcf0-ffffffff8135fe15: add_to_kill (STB_LOCAL)
ffffffff81cc30ec-ffffffff81cc3123: add_to_kill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:344
Inline: False
```
**Symbols:**

```
ffffffff813da940-ffffffff813dab25: add_to_kill (STB_LOCAL)
ffffffff81e75606-ffffffff81e7563d: add_to_kill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, long unsigned int fsdax_pgoff, struct vm_area_struct *vma, struct list_head *to_kill);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81460b20)
Location: mm/memory-failure.c:373
Inline: False
Direct callers:
  - mm/memory-failure.c:mf_dax_kill_procs
```
**Symbols:**

```
ffffffff81460b20-ffffffff81460d44: add_to_kill (STB_LOCAL)
```
</details>
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
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffff80001036dae8)
Location: mm/memory-failure.c:308
Inline: False
```
**Symbols:**

```
ffff80001036dae8-ffff80001036dbe8: add_to_kill (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c00000000045e840)
Location: mm/memory-failure.c:308
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
c00000000045e840-c00000000045ecd8: add_to_kill (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:308
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff812c30d0-ffffffff812c31e6: add_to_kill (STB_LOCAL)
ffffffff812c508b-ffffffff812c50c2: add_to_kill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:308
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff812b3ed0-ffffffff812b422a: add_to_kill (STB_LOCAL)
ffffffff812b60cb-ffffffff812b6102: add_to_kill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:308
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff812c0ee0-ffffffff812c0ff6: add_to_kill (STB_LOCAL)
ffffffff812c2e9b-ffffffff812c2ed2: add_to_kill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void add_to_kill(struct task_struct *tsk, struct page *p, struct vm_area_struct *vma, struct list_head *to_kill, struct to_kill **tkc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:308
Inline: False
Direct callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
```
**Symbols:**

```
ffffffff812d19a0-ffffffff812d1ab6: add_to_kill (STB_LOCAL)
ffffffff812d393b-ffffffff812d3972: add_to_kill.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct to_kill **tkc</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int fsdax_pgoff</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, p, vma, to_kill</code> ➡️ <code>tsk, p, fsdax_pgoff, vma, to_kill</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
