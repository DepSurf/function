# Function: <code>fuse_free_dax_mem_ranges</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_free_dax_mem_ranges(struct list_head *mem_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149c270)
Location: fs/fuse/dax.c:1213
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_conn_free
```
**Symbols:**

```
ffffffff8149c270-ffffffff8149c308: fuse_free_dax_mem_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_free_dax_mem_ranges(struct list_head *mem_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a22a0)
Location: fs/fuse/dax.c:1213
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_conn_free
```
**Symbols:**

```
ffffffff814a22a0-ffffffff814a2338: fuse_free_dax_mem_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_free_dax_mem_ranges(struct list_head *mem_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fa340)
Location: fs/fuse/dax.c:1212
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_conn_free
```
**Symbols:**

```
ffffffff814fa340-ffffffff814fa3d8: fuse_free_dax_mem_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_free_dax_mem_ranges(struct list_head *mem_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158a620)
Location: fs/fuse/dax.c:1209
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_conn_free
```
**Symbols:**

```
ffffffff8158a620-ffffffff8158a6c4: fuse_free_dax_mem_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_free_dax_mem_ranges(struct list_head *mem_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81630d40)
Location: fs/fuse/dax.c:1209
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_conn_free
```
**Symbols:**

```
ffffffff81630d40-ffffffff81630de4: fuse_free_dax_mem_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_free_dax_mem_ranges(struct list_head *mem_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81668f70)
Location: fs/fuse/dax.c:1209
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_conn_free
```
**Symbols:**

```
ffffffff81668f70-ffffffff81669014: fuse_free_dax_mem_ranges (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_free_dax_mem_ranges(struct list_head *mem_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a3270)
Location: fs/fuse/dax.c:1207
Inline: False
Direct callers:
  - fs/fuse/dax.c:fuse_dax_conn_free
```
**Symbols:**

```
ffffffff816a3270-ffffffff816a3314: fuse_free_dax_mem_ranges (STB_LOCAL)
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
