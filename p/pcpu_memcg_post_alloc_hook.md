# Function: <code>pcpu_memcg_post_alloc_hook</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff81285b84)
Location: mm/percpu.c:1603
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
Direct callers:
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81284420-ffffffff8128447e: pcpu_memcg_post_alloc_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff8128a759)
Location: mm/percpu.c:1604
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
Direct callers:
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8128a4e0-ffffffff8128a54e: pcpu_memcg_post_alloc_hook.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcpu_memcg_post_alloc_hook(struct obj_cgroup *objcg, struct pcpu_chunk *chunk, int off, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812ca8a0)
Location: mm/percpu.c:1647
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff812ca8a0-ffffffff812ca966: pcpu_memcg_post_alloc_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcpu_memcg_post_alloc_hook(struct obj_cgroup *objcg, struct pcpu_chunk *chunk, int off, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81327e40)
Location: mm/percpu.c:1647
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81327e40-ffffffff81327f1d: pcpu_memcg_post_alloc_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcpu_memcg_post_alloc_hook(struct obj_cgroup *objcg, struct pcpu_chunk *chunk, int off, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139d280)
Location: mm/percpu.c:1644
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8139d280-ffffffff8139d35d: pcpu_memcg_post_alloc_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcpu_memcg_post_alloc_hook(struct obj_cgroup *objcg, struct pcpu_chunk *chunk, int off, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813d0380)
Location: mm/percpu.c:1644
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff813d0380-ffffffff813d0488: pcpu_memcg_post_alloc_hook (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pcpu_memcg_post_alloc_hook(struct obj_cgroup *objcg, struct pcpu_chunk *chunk, int off, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813fa0a0)
Location: mm/percpu.c:1642
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff813fa0a0-ffffffff813fa1b7: pcpu_memcg_post_alloc_hook (STB_LOCAL)
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
