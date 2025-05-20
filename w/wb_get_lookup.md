# Function: <code>wb_get_lookup</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff81249ca8)
Location: mm/backing-dev.c:644
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81248c00-ffffffff81248cc8: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff81249320-ffffffff8124933f: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff81278339)
Location: mm/backing-dev.c:643
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81276e10-ffffffff81276eda: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff81277610-ffffffff8127762f: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff81282ad9)
Location: mm/backing-dev.c:544
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff812816d0-ffffffff812817c2: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff81281cc0-ffffffff81281cdf: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff81287c09)
Location: mm/backing-dev.c:543
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81286580-ffffffff81286672: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff81286c80-ffffffff81286c9f: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff812c73a9)
Location: mm/backing-dev.c:566
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff812c5900-ffffffff812c59f2: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff812c6210-ffffffff812c622f: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff8132404a)
Location: mm/backing-dev.c:555
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81323e10-ffffffff81323f25: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff81323fc0-ffffffff81323fef: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff8139891a)
Location: mm/backing-dev.c:682
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff813984a0-ffffffff813985b5: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff81398880-ffffffff813988af: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff813cb87a)
Location: mm/backing-dev.c:695
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff813cb420-ffffffff813cb523: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff813cb7e0-ffffffff813cb80f: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff813f61ab)
Location: mm/backing-dev.c:693
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff813f5f70-ffffffff813f6073: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff813f6130-ffffffff813f615f: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffff8000102df424)
Location: mm/backing-dev.c:644
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffff8000102de3d0-ffff8000102de544: wb_get_lookup.part.0 (STB_LOCAL)
ffff8000102de8a8-ffff8000102de8f4: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (c05042b8)
Location: mm/backing-dev.c:644
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
c050360c-c050375c: wb_get_lookup.part.0 (STB_LOCAL)
c05039b8-c05039e8: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (c00000000039efa0)
Location: mm/backing-dev.c:644
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
c00000000039d6f0-c00000000039d8a0: wb_get_lookup.part.0 (STB_LOCAL)
c00000000039e1e0-c00000000039e208: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f7224)
Location: mm/backing-dev.c:644
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffe0001f610a-ffffffe0001f621c: wb_get_lookup.part.0 (STB_LOCAL)
ffffffe0001f686c-ffffffe0001f68a8: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff812422f8)
Location: mm/backing-dev.c:644
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81241250-ffffffff81241318: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff81241970-ffffffff8124198f: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff812352c8)
Location: mm/backing-dev.c:644
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81234250-ffffffff81234318: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff81234960-ffffffff8123497f: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff81240098)
Location: mm/backing-dev.c:644
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff8123eff0-ffffffff8123f0b8: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff8123f710-ffffffff8123f72f: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bdi_writeback *wb_get_lookup(struct backing_dev_info *bdi, struct cgroup_subsys_state *memcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff8124f7e9)
Location: mm/backing-dev.c:644
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff8124eaf0-ffffffff8124ebf3: wb_get_lookup.part.0 (STB_LOCAL)
ffffffff8124ee90-ffffffff8124eeaf: wb_get_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
