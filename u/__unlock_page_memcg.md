# Function: <code>__unlock_page_memcg</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123c0d9)
Location: mm/memcontrol.c:1672
Inline: True
Inline callers:
  - mm/memcontrol.c:unlock_page_memcg
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
**Symbols:**

```
ffffffff812413e0-ffffffff81241427: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125b929)
Location: mm/memcontrol.c:1686
Inline: True
Inline callers:
  - mm/memcontrol.c:unlock_page_memcg
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
**Symbols:**

```
ffffffff81261120-ffffffff8126116c: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8127f449)
Location: mm/memcontrol.c:1643
Inline: True
Inline callers:
  - mm/memcontrol.c:unlock_page_memcg
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
**Symbols:**

```
ffffffff81285140-ffffffff81285188: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81293d39)
Location: mm/memcontrol.c:1921
Inline: True
Inline callers:
  - mm/memcontrol.c:unlock_page_memcg
  - mm/memcontrol.c:unlock_page_memcg
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
**Symbols:**

```
ffffffff81299f50-ffffffff81299f98: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5210)
Location: mm/memcontrol.c:2122
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memcontrol.c:unlock_page_memcg
```
**Symbols:**

```
ffffffff812b5210-ffffffff812b5256: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6d00)
Location: mm/memcontrol.c:2138
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memcontrol.c:unlock_page_memcg
```
**Symbols:**

```
ffffffff812c6d00-ffffffff812c6d46: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fa45a)
Location: mm/memcontrol.c:2013
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:unlock_page_memcg
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
**Symbols:**

```
ffffffff812fc520-ffffffff812fc566: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81306380)
Location: mm/memcontrol.c:2208
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:unlock_page_memcg
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
**Symbols:**

```
ffffffff81308750-ffffffff813087a4: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130c84b)
Location: mm/memcontrol.c:2017
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:unlock_page_memcg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81357a4b)
Location: mm/memcontrol.c:2069
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:unlock_page_memcg
```
</details>
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
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010369ac0)
Location: mm/memcontrol.c:2138
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memcontrol.c:unlock_page_memcg
```
**Symbols:**

```
ffff800010369ac0-ffff800010369b20: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055ae28)
Location: mm/memcontrol.c:2138
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memcontrol.c:unlock_page_memcg
```
**Symbols:**

```
c055ae28-c055ae80: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000458580)
Location: mm/memcontrol.c:2138
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memcontrol.c:unlock_page_memcg
```
**Symbols:**

```
c000000000458580-c0000000004585e8: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000247368)
Location: mm/memcontrol.c:2138
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memcontrol.c:unlock_page_memcg
```
**Symbols:**

```
ffffffe000247368-ffffffe0002473b4: __unlock_page_memcg (STB_GLOBAL)
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
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf2e0)
Location: mm/memcontrol.c:2138
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memcontrol.c:unlock_page_memcg
```
**Symbols:**

```
ffffffff812bf2e0-ffffffff812bf326: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b03d0)
Location: mm/memcontrol.c:2138
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memcontrol.c:unlock_page_memcg
```
**Symbols:**

```
ffffffff812b03d0-ffffffff812b0416: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd0f0)
Location: mm/memcontrol.c:2138
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memcontrol.c:unlock_page_memcg
```
**Symbols:**

```
ffffffff812bd0f0-ffffffff812bd136: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __unlock_page_memcg(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cd930)
Location: mm/memcontrol.c:2138
Inline: False
Direct callers:
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/memcontrol.c:unlock_page_memcg
```
**Symbols:**

```
ffffffff812cd930-ffffffff812cd981: __unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
