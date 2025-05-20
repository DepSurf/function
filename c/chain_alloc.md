# Function: <code>chain_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d0610)
Location: kernel/power/snapshot.c:204
Inline: False
Direct callers:
  - kernel/power/snapshot.c:alloc_rtree_node
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff810d0610-ffffffff810d066d: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d5410)
Location: kernel/power/snapshot.c:273
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
ffffffff810d5410-ffffffff810d547b: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810dbfb0)
Location: kernel/power/snapshot.c:273
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
ffffffff810dbfb0-ffffffff810dc01b: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810db120)
Location: kernel/power/snapshot.c:275
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
ffffffff810db120-ffffffff810db186: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810e3190)
Location: kernel/power/snapshot.c:277
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
ffffffff810e3190-ffffffff810e31f6: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810eb650)
Location: kernel/power/snapshot.c:277
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
ffffffff810eb650-ffffffff810eb6b6: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f6cd0)
Location: kernel/power/snapshot.c:277
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
ffffffff810f6cd0-ffffffff810f6d32: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810ff210)
Location: kernel/power/snapshot.c:275
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
ffffffff810ff210-ffffffff810ff272: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110b670)
Location: kernel/power/snapshot.c:275
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
ffffffff8110b670-ffffffff8110b6d2: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811166c0)
Location: kernel/power/snapshot.c:274
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:add_rtree_block
  - kernel/power/snapshot.c:add_rtree_block
  - kernel/power/snapshot.c:add_rtree_block
```
**Symbols:**

```
ffffffff811166c0-ffffffff81116722: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81112b40)
Location: kernel/power/snapshot.c:308
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:add_rtree_block
  - kernel/power/snapshot.c:add_rtree_block
  - kernel/power/snapshot.c:add_rtree_block
```
**Symbols:**

```
ffffffff81112b40-ffffffff81112ba2: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81113590)
Location: kernel/power/snapshot.c:308
Inline: False
Direct callers:
  - kernel/power/snapshot.c:create_zone_bm_rtree
  - kernel/power/snapshot.c:create_zone_bm_rtree
  - kernel/power/snapshot.c:create_zone_bm_rtree
  - kernel/power/snapshot.c:create_zone_bm_rtree
```
**Symbols:**

```
ffffffff81113590-ffffffff811135f2: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81133730)
Location: kernel/power/snapshot.c:308
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff81133730-ffffffff81133792: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811555d0)
Location: kernel/power/snapshot.c:308
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff811555d0-ffffffff8115563e: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811855c0)
Location: kernel/power/snapshot.c:308
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff811855c0-ffffffff8118562e: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81196330)
Location: kernel/power/snapshot.c:308
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff81196330-ffffffff8119639e: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811a4d50)
Location: kernel/power/snapshot.c:308
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:memory_bm_create
```
**Symbols:**

```
ffffffff811a4d50-ffffffff811a4dbe: chain_alloc (STB_LOCAL)
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
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03bdf4c)
Location: kernel/power/snapshot.c:275
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
c03bdf4c-c03bdfd0: chain_alloc (STB_LOCAL)
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
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81103890)
Location: kernel/power/snapshot.c:274
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
ffffffff81103890-ffffffff811038f2: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f4b30)
Location: kernel/power/snapshot.c:275
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
ffffffff810f4b30-ffffffff810f4b92: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81101b40)
Location: kernel/power/snapshot.c:275
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
ffffffff81101b40-ffffffff81101ba2: chain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *chain_alloc(struct chain_allocator *ca, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110cf10)
Location: kernel/power/snapshot.c:275
Inline: False
Direct callers:
  - kernel/power/snapshot.c:memory_bm_create
  - kernel/power/snapshot.c:alloc_rtree_node
```
**Symbols:**

```
ffffffff8110cf10-ffffffff8110cf72: chain_alloc (STB_LOCAL)
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
