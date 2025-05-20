# Function: <code>memory_bm_next_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d01d0)
Location: kernel/power/snapshot.c:802
Inline: False
Direct callers:
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff810d01d0-ffffffff810d02c9: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d4d60)
Location: kernel/power/snapshot.c:873
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
```
**Symbols:**

```
ffffffff810d4d60-ffffffff810d4e59: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810db910)
Location: kernel/power/snapshot.c:873
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
```
**Symbols:**

```
ffffffff810db910-ffffffff810dba09: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810daa60)
Location: kernel/power/snapshot.c:875
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
```
**Symbols:**

```
ffffffff810daa60-ffffffff810dab5d: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810e2c70)
Location: kernel/power/snapshot.c:877
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
```
**Symbols:**

```
ffffffff810e2c70-ffffffff810e2d6d: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810eb1a0)
Location: kernel/power/snapshot.c:877
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:clear_free_pages
```
**Symbols:**

```
ffffffff810eb1a0-ffffffff810eb29d: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f6820)
Location: kernel/power/snapshot.c:877
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:clear_free_pages
```
**Symbols:**

```
ffffffff810f6820-ffffffff810f691d: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810fedc0)
Location: kernel/power/snapshot.c:875
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:clear_free_pages
```
**Symbols:**

```
ffffffff810fedc0-ffffffff810feebd: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110b220)
Location: kernel/power/snapshot.c:882
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:clear_free_pages
```
**Symbols:**

```
ffffffff8110b220-ffffffff8110b31d: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81115de0)
Location: kernel/power/snapshot.c:881
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:free_unnecessary_pages
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:clear_free_pages
```
**Symbols:**

```
ffffffff81115de0-ffffffff81115edd: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81112260)
Location: kernel/power/snapshot.c:915
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:free_unnecessary_pages
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
**Symbols:**

```
ffffffff81112260-ffffffff8111235d: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81112d50)
Location: kernel/power/snapshot.c:915
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
**Symbols:**

```
ffffffff81112d50-ffffffff81112e32: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81132de0)
Location: kernel/power/snapshot.c:915
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
**Symbols:**

```
ffffffff81132de0-ffffffff81132ec2: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81154dc0)
Location: kernel/power/snapshot.c:919
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
**Symbols:**

```
ffffffff81154dc0-ffffffff81154ecf: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81184c70)
Location: kernel/power/snapshot.c:919
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
**Symbols:**

```
ffffffff81184c70-ffffffff81184d64: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811959d0)
Location: kernel/power/snapshot.c:919
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
**Symbols:**

```
ffffffff811959d0-ffffffff81195ac4: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811a43b0)
Location: kernel/power/snapshot.c:927
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
```
**Symbols:**

```
ffffffff811a43b0-ffffffff811a44b2: memory_bm_next_pfn (STB_LOCAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03bd91c)
Location: kernel/power/snapshot.c:882
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:clear_free_pages
```
**Symbols:**

```
c03bd91c-c03bda04: memory_bm_next_pfn (STB_LOCAL)
```
</details>
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
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81103440)
Location: kernel/power/snapshot.c:881
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:clear_free_pages
```
**Symbols:**

```
ffffffff81103440-ffffffff8110353d: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f46e0)
Location: kernel/power/snapshot.c:882
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:clear_free_pages
```
**Symbols:**

```
ffffffff810f46e0-ffffffff810f47dd: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811016f0)
Location: kernel/power/snapshot.c:882
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:clear_free_pages
```
**Symbols:**

```
ffffffff811016f0-ffffffff811017ed: memory_bm_next_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int memory_bm_next_pfn(struct memory_bitmap *bm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110cac0)
Location: kernel/power/snapshot.c:882
Inline: False
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:hibernate_preallocate_memory
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:clear_free_pages
```
**Symbols:**

```
ffffffff8110cac0-ffffffff8110cbbd: memory_bm_next_pfn (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
