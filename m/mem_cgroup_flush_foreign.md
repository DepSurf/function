# Function: <code>mem_cgroup_flush_foreign</code>

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
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7a60)
Location: mm/memcontrol.c:4556
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812c7a60-ffffffff812c7b4d: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fd4f0)
Location: mm/memcontrol.c:4436
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812fd4f0-ffffffff812fd5d8: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309960)
Location: mm/memcontrol.c:4701
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff81309960-ffffffff81309a1b: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130ffb0)
Location: mm/memcontrol.c:4469
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff8130ffb0-ffffffff8131006b: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135b2e0)
Location: mm/memcontrol.c:4636
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff8135b2e0-ffffffff8135b3bb: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d49e0)
Location: mm/memcontrol.c:4587
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff813d49e0-ffffffff813d4ae7: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145a420)
Location: mm/memcontrol.c:4697
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff8145a420-ffffffff8145a537: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81490080)
Location: mm/memcontrol.c:4721
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff81490080-ffffffff81490197: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bf890)
Location: mm/memcontrol.c:4918
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff814bf890-ffffffff814bf9a7: mem_cgroup_flush_foreign (STB_GLOBAL)
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
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036a8d0)
Location: mm/memcontrol.c:4556
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffff80001036a8d0-ffff80001036aa08: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055be68)
Location: mm/memcontrol.c:4556
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
c055be68-c055c010: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000459bc0)
Location: mm/memcontrol.c:4556
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
c000000000459bc0-c000000000459d44: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002480e2)
Location: mm/memcontrol.c:4556
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffe0002480e2-ffffffe000248204: mem_cgroup_flush_foreign (STB_GLOBAL)
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
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0040)
Location: mm/memcontrol.c:4556
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812c0040-ffffffff812c012d: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b1110)
Location: mm/memcontrol.c:4556
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812b1110-ffffffff812b11fd: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bde50)
Location: mm/memcontrol.c:4556
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812bde50-ffffffff812bdf3d: mem_cgroup_flush_foreign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_flush_foreign(struct bdi_writeback *wb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ce7d0)
Location: mm/memcontrol.c:4556
Inline: False
Direct callers:
  - mm/page-writeback.c:balance_dirty_pages
```
**Symbols:**

```
ffffffff812ce7d0-ffffffff812ce8d4: mem_cgroup_flush_foreign (STB_GLOBAL)
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
