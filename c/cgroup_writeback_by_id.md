# Function: <code>cgroup_writeback_by_id</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813149f0)
Location: fs/fs-writeback.c:918
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff813149f0-ffffffff81314c07: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134e3d0)
Location: fs/fs-writeback.c:919
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff8134e3d0-ffffffff8134e5d9: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135b280)
Location: fs/fs-writeback.c:919
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff8135b280-ffffffff8135b4d4: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81361e80)
Location: fs/fs-writeback.c:925
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff81361e80-ffffffff813620d4: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813b06f0)
Location: fs/fs-writeback.c:1048
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff813b06f0-ffffffff813b08e1: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814354e0)
Location: fs/fs-writeback.c:1014
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff814354e0-ffffffff814356e5: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c3550)
Location: fs/fs-writeback.c:1016
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff814c3550-ffffffff814c3752: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f8930)
Location: fs/fs-writeback.c:1021
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff814f8930-ffffffff814f8b35: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152d160)
Location: fs/fs-writeback.c:1038
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff8152d160-ffffffff8152d394: cgroup_writeback_by_id (STB_GLOBAL)
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103ca8e0)
Location: fs/fs-writeback.c:918
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffff8000103ca8e0-ffff8000103caba0: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a6e4c)
Location: fs/fs-writeback.c:918
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
c05a6e4c-c05a7130: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004cc320)
Location: fs/fs-writeback.c:918
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
c0000000004cc320-c0000000004cc6a8: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000288aa4)
Location: fs/fs-writeback.c:918
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffe000288aa4-ffffffe000288cac: cgroup_writeback_by_id (STB_GLOBAL)
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
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130cfd0)
Location: fs/fs-writeback.c:918
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff8130cfd0-ffffffff8130d1e7: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fdbe0)
Location: fs/fs-writeback.c:918
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff812fdbe0-ffffffff812fddf7: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130adc0)
Location: fs/fs-writeback.c:918
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff8130adc0-ffffffff8130afd7: cgroup_writeback_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_writeback_by_id(u64 bdi_id, int memcg_id, long unsigned int nr, enum wb_reason reason, struct wb_completion *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131c4e0)
Location: fs/fs-writeback.c:918
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
```
**Symbols:**

```
ffffffff8131c4e0-ffffffff8131c766: cgroup_writeback_by_id (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int nr</code>
</li>
<li>
<b>Param reordered. </b>
<code>bdi_id, memcg_id, nr, reason, done</code> ➡️ <code>bdi_id, memcg_id, reason, done</code>
</li>
</ul>
</details>
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
