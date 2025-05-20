# Function: <code>split_huge_pages_pid</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81300550)
Location: mm/huge_memory.c:2970
Inline: False
```
**Symbols:**

```
ffffffff81300550-ffffffff81300871: split_huge_pages_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8134a1f0)
Location: mm/huge_memory.c:2913
Inline: False
```
**Symbols:**

```
ffffffff8134a1f0-ffffffff8134a50e: split_huge_pages_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813c0d90)
Location: mm/huge_memory.c:2883
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_write
```
**Symbols:**

```
ffffffff813c0d90-ffffffff813c11f0: split_huge_pages_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81442c60)
Location: mm/huge_memory.c:2983
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_write
```
**Symbols:**

```
ffffffff81442c60-ffffffff814430b1: split_huge_pages_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81478520)
Location: mm/huge_memory.c:2992
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_write
```
**Symbols:**

```
ffffffff81478520-ffffffff81478982: split_huge_pages_pid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a7c50)
Location: mm/huge_memory.c:3318
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_pages_write
```
**Symbols:**

```
ffffffff814a7c50-ffffffff814a7f79: split_huge_pages_pid (STB_LOCAL)
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
