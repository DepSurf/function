# Function: <code>kill_accessing_process</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kill_accessing_process(struct task_struct *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81cc2efc)
Location: mm/memory-failure.c:694
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_hugetlb
```
**Symbols:**

```
ffffffff81cc2efc-ffffffff81cc3021: kill_accessing_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kill_accessing_process(struct task_struct *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81e75400)
Location: mm/memory-failure.c:691
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
**Symbols:**

```
ffffffff81e75400-ffffffff81e7553e: kill_accessing_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kill_accessing_process(struct task_struct *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8145eb50)
Location: mm/memory-failure.c:753
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
**Symbols:**

```
ffffffff8145eb50-ffffffff8145ecc8: kill_accessing_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kill_accessing_process(struct task_struct *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814949a0)
Location: mm/memory-failure.c:850
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
**Symbols:**

```
ffffffff814949a0-ffffffff81494b1e: kill_accessing_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kill_accessing_process(struct task_struct *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c42b0)
Location: mm/memory-failure.c:852
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
**Symbols:**

```
ffffffff814c42b0-ffffffff814c442e: kill_accessing_process (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
