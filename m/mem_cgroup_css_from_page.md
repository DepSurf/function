# Function: <code>mem_cgroup_css_from_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fc780)
Location: mm/memcontrol.c:430
Inline: False
Direct callers:
  - fs/fs-writeback.c:wbc_account_io
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff811fc780-ffffffff811fc7a2: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81220380)
Location: mm/memcontrol.c:333
Inline: False
Direct callers:
  - fs/fs-writeback.c:wbc_account_io
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff81220380-ffffffff812203a2: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81232a10)
Location: mm/memcontrol.c:333
Inline: False
Direct callers:
  - fs/fs-writeback.c:wbc_account_io
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff81232a10-ffffffff81232a32: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123e220)
Location: mm/memcontrol.c:320
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff8123e220-ffffffff8123e242: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125ddc0)
Location: mm/memcontrol.c:321
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff8125ddc0-ffffffff8125ddea: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81282050)
Location: mm/memcontrol.c:321
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff81282050-ffffffff8128207a: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81296230)
Location: mm/memcontrol.c:459
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff81296230-ffffffff8129625a: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b2570)
Location: mm/memcontrol.c:458
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff812b2570-ffffffff812b2592: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c3fb0)
Location: mm/memcontrol.c:458
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff812c3fb0-ffffffff812c3fd2: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fa140)
Location: mm/memcontrol.c:449
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff812fa140-ffffffff812fa162: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81305f70)
Location: mm/memcontrol.c:535
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff81305f70-ffffffff81305f93: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130c400)
Location: mm/memcontrol.c:414
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff8130c400-ffffffff8130c432: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813562e0)
Location: mm/memcontrol.c:413
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff813562e0-ffffffff8135630f: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cee70)
Location: mm/memcontrol.c:370
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff813cee70-ffffffff813ceee1: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81453fb0)
Location: mm/memcontrol.c:363
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff81453fb0-ffffffff81454021: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
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
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010366a68)
Location: mm/memcontrol.c:458
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffff800010366a68-ffff800010366aac: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0558254)
Location: mm/memcontrol.c:458
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
c0558254-c0558298: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000453de0)
Location: mm/memcontrol.c:458
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
c000000000453de0-c000000000453e1c: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000244dc2)
Location: mm/memcontrol.c:458
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffe000244dc2-ffffffe000244e04: mem_cgroup_css_from_page (STB_GLOBAL)
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
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bc590)
Location: mm/memcontrol.c:458
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff812bc590-ffffffff812bc5b2: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ad6f0)
Location: mm/memcontrol.c:458
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff812ad6f0-ffffffff812ad712: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ba3a0)
Location: mm/memcontrol.c:458
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff812ba3a0-ffffffff812ba3c2: mem_cgroup_css_from_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cgroup_subsys_state *mem_cgroup_css_from_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812caa80)
Location: mm/memcontrol.c:458
Inline: False
Direct callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
**Symbols:**

```
ffffffff812caa80-ffffffff812caaa2: mem_cgroup_css_from_page (STB_GLOBAL)
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
