# Function: <code>KSTK_ESP</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102e0b0)
Location: arch/x86/kernel/process_64.c:594
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_task
  - mm/util.c:vma_is_stack_for_task
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8102e0b0-ffffffff8102e0c6: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102cfe0)
Location: arch/x86/kernel/process_64.c:593
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_task
  - mm/util.c:vma_is_stack_for_task
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8102cfe0-ffffffff8102cff6: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102ce80)
Location: arch/x86/kernel/process_64.c:627
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
```
**Symbols:**

```
ffffffff8102ce80-ffffffff8102ce96: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102b0e0)
Location: arch/x86/kernel/process_64.c:696
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
```
**Symbols:**

```
ffffffff8102b0e0-ffffffff8102b0f6: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102be10)
Location: arch/x86/kernel/process_64.c:697
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8102be10-ffffffff8102be26: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102ce50)
Location: arch/x86/kernel/process_64.c:721
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8102ce50-ffffffff8102ce66: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102e0a0)
Location: arch/x86/kernel/process_64.c:826
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8102e0a0-ffffffff8102e0b6: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8102fe00)
Location: arch/x86/kernel/process_64.c:817
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8102fe00-ffffffff8102fe16: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030760)
Location: arch/x86/kernel/process_64.c:817
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81030760-ffffffff81030776: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032d80)
Location: arch/x86/kernel/process_64.c:728
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81032d80-ffffffff81032d96: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81033a40)
Location: arch/x86/kernel/process_64.c:834
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81033a40-ffffffff81033a56: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81035580)
Location: arch/x86/kernel/process_64.c:834
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81035580-ffffffff81035596: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8103a860)
Location: arch/x86/kernel/process_64.c:860
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8103a860-ffffffff8103a876: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81041960)
Location: arch/x86/kernel/process_64.c:859
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81041960-ffffffff8104197c: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104b0f0)
Location: arch/x86/kernel/process_64.c:860
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8104b0f0-ffffffff8104b10c: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff8104b990)
Location: arch/x86/kernel/process_64.c:923
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8104b990-ffffffff8104b9ac: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81052c10)
Location: arch/x86/kernel/process_64.c:931
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81052c10-ffffffff81052c2c: KSTK_ESP (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810308c0)
Location: arch/x86/kernel/process_64.c:817
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810308c0-ffffffff810308d6: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81020350)
Location: arch/x86/kernel/process_64.c:817
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81020350-ffffffff81020366: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81030720)
Location: arch/x86/kernel/process_64.c:817
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81030720-ffffffff81030736: KSTK_ESP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int KSTK_ESP(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff810315b0)
Location: arch/x86/kernel/process_64.c:817
Inline: False
Direct callers:
  - mm/util.c:vma_is_stack_for_current
  - mm/util.c:vma_is_stack_for_current
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810315b0-ffffffff810315c6: KSTK_ESP (STB_GLOBAL)
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
