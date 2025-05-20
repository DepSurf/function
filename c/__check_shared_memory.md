# Function: <code>__check_shared_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff816ad09e)
Location: drivers/md/dm-stats.c:80
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff8170e0a4)
Location: drivers/md/dm-stats.c:80
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff8173f66e)
Location: drivers/md/dm-stats.c:80
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81759438)
Location: drivers/md/dm-stats.c:80
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff817cb698)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81814472)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81840472)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81883333)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm-stats.c (ffffffff818b51d3)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __check_shared_memory(size_t alloc_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81984f20)
Location: drivers/md/dm-stats.c:81
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
**Symbols:**

```
ffffffff81984f20-ffffffff81984f84: __check_shared_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __check_shared_memory(size_t alloc_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81988fc0)
Location: drivers/md/dm-stats.c:81
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
**Symbols:**

```
ffffffff81988fc0-ffffffff81989024: __check_shared_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __check_shared_memory(size_t alloc_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff8196d6a0)
Location: drivers/md/dm-stats.c:81
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
**Symbols:**

```
ffffffff8196d6a0-ffffffff8196d704: __check_shared_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __check_shared_memory(size_t alloc_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81a15c70)
Location: drivers/md/dm-stats.c:81
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
**Symbols:**

```
ffffffff81a15c70-ffffffff81a15cd4: __check_shared_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __check_shared_memory(size_t alloc_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81b7e670)
Location: drivers/md/dm-stats.c:81
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
**Symbols:**

```
ffffffff81b7e670-ffffffff81b7e6ce: __check_shared_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __check_shared_memory(size_t alloc_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81d1c780)
Location: drivers/md/dm-stats.c:81
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
**Symbols:**

```
ffffffff81d1c780-ffffffff81d1c7f0: __check_shared_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __check_shared_memory(size_t alloc_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81d85960)
Location: drivers/md/dm-stats.c:81
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
**Symbols:**

```
ffffffff81d85960-ffffffff81d859d0: __check_shared_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __check_shared_memory(size_t alloc_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81e3d0a0)
Location: drivers/md/dm-stats.c:84
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
**Symbols:**

```
ffffffff81e3d0a0-ffffffff81e3d110: __check_shared_memory (STB_LOCAL)
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
In drivers/md/dm-stats.c (ffff800010b0cfbc)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm-stats.c (c0bea5cc)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm-stats.c (c000000000bff7e4)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm-stats.c (ffffffe0006fa67e)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm-stats.c (ffffffff8185b053)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm-stats.c (ffffffff81822633)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm-stats.c (ffffffff818aa683)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
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
In drivers/md/dm-stats.c (ffffffff818c5ea3)
Location: drivers/md/dm-stats.c:81
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_kvzalloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
