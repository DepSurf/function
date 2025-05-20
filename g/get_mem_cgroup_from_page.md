# Function: <code>get_mem_cgroup_from_page</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81294dc0)
Location: mm/memcontrol.c:861
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffffffff81294dc0-ffffffff81294e31: get_mem_cgroup_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0b90)
Location: mm/memcontrol.c:978
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffffffff812b0b90-ffffffff812b0bfd: get_mem_cgroup_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c25f0)
Location: mm/memcontrol.c:989
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffffffff812c25f0-ffffffff812c265d: get_mem_cgroup_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f7500)
Location: mm/memcontrol.c:950
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffffffff812f7500-ffffffff812f7566: get_mem_cgroup_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81302a40)
Location: mm/memcontrol.c:1053
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffffffff81302a40-ffffffff81302ac7: get_mem_cgroup_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010364b80)
Location: mm/memcontrol.c:989
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffff800010364b80-ffff800010364bec: get_mem_cgroup_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0556b10)
Location: mm/memcontrol.c:989
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
c0556b10-c0556be8: get_mem_cgroup_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000451990)
Location: mm/memcontrol.c:989
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
c000000000451990-c000000000451a94: get_mem_cgroup_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe00024393e)
Location: mm/memcontrol.c:989
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffffffe00024393e-ffffffe0002439e0: get_mem_cgroup_from_page (STB_GLOBAL)
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
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812babd0)
Location: mm/memcontrol.c:989
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffffffff812babd0-ffffffff812bac3d: get_mem_cgroup_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812abd80)
Location: mm/memcontrol.c:989
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffffffff812abd80-ffffffff812abded: get_mem_cgroup_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b89e0)
Location: mm/memcontrol.c:989
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffffffff812b89e0-ffffffff812b8a4d: get_mem_cgroup_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mem_cgroup *get_mem_cgroup_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c9210)
Location: mm/memcontrol.c:989
Inline: False
Direct callers:
  - fs/buffer.c:alloc_page_buffers
```
**Symbols:**

```
ffffffff812c9210-ffffffff812c92b3: get_mem_cgroup_from_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
