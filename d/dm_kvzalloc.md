# Function: <code>dm_kvzalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff816ad080)
Location: drivers/md/dm-stats.c:142
Inline: True
Direct callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
**Symbols:**

```
ffffffff816ad080-ffffffff816ad142: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff8170d5e0)
Location: drivers/md/dm-stats.c:142
Inline: True
Direct callers:
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
  - drivers/md/dm-stats.c:dm_stats_message
```
**Symbols:**

```
ffffffff8170d5e0-ffffffff8170d6c2: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff8173f640)
Location: drivers/md/dm-stats.c:142
Inline: True
```
**Symbols:**

```
ffffffff8173f640-ffffffff8173f722: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81759400)
Location: drivers/md/dm-stats.c:142
Inline: False
```
**Symbols:**

```
ffffffff81759400-ffffffff817594b8: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff817cb660)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff817cb660-ffffffff817cb718: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81814450)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff81814450-ffffffff81814507: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81840450)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff81840450-ffffffff81840507: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81883310)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff81883310-ffffffff818833ca: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff818b51b0)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff818b51b0-ffffffff818b526a: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81985f70)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff81985f70-ffffffff8198600e: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81989fd0)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff81989fd0-ffffffff8198a06e: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff8196e5a0)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff8196e5a0-ffffffff8196e63e: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81a16e10)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff81a16e10-ffffffff81a16eae: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81b7e8b0)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff81b7e8b0-ffffffff81b7e92d: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81d1ca10)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff81d1ca10-ffffffff81d1ca8d: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81d85bf0)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff81d85bf0-ffffffff81d85c8c: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81e3d330)
Location: drivers/md/dm-stats.c:146
Inline: False
```
**Symbols:**

```
ffffffff81e3d330-ffffffff81e3d3cc: dm_kvzalloc (STB_LOCAL)
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
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffff800010b0cf68)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffff800010b0cf68-ffff800010b0d09c: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (c0bea5a0)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
c0bea5a0-c0bea694: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (c000000000bff7a0)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
c000000000bff7a0-c000000000bff940: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffe0006fa654)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffe0006fa654-ffffffe0006fa77c: dm_kvzalloc (STB_LOCAL)
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
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff8185b030)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff8185b030-ffffffff8185b0ea: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81822610)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff81822610-ffffffff818226be: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff818aa660)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff818aa660-ffffffff818aa71a: dm_kvzalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *dm_kvzalloc(size_t alloc_size, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff818c5e80)
Location: drivers/md/dm-stats.c:143
Inline: False
```
**Symbols:**

```
ffffffff818c5e80-ffffffff818c5f39: dm_kvzalloc (STB_LOCAL)
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
