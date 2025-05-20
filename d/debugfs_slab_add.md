# Function: <code>debugfs_slab_add</code>

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
void debugfs_slab_add(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81332f40)
Location: mm/slub.c:6180
Inline: False
Direct callers:
  - mm/slub.c:slab_debugfs_init
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff81332f40-ffffffff81332fab: debugfs_slab_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void debugfs_slab_add(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a4660)
Location: mm/slub.c:6261
Inline: False
Direct callers:
  - mm/slub.c:slab_debugfs_init
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff813a4660-ffffffff813a46eb: debugfs_slab_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void debugfs_slab_add(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81424730)
Location: mm/slub.c:6434
Inline: False
Direct callers:
  - mm/slub.c:slab_debugfs_init
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff81424730-ffffffff814247bb: debugfs_slab_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void debugfs_slab_add(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814599d0)
Location: mm/slub.c:6448
Inline: False
Direct callers:
  - mm/slub.c:slab_debugfs_init
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff814599d0-ffffffff81459a5b: debugfs_slab_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void debugfs_slab_add(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81454950)
Location: mm/slub.c:7059
Inline: False
Direct callers:
  - mm/slub.c:slab_debugfs_init
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff81454950-ffffffff814549db: debugfs_slab_add (STB_LOCAL)
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
