# Function: <code>mem_cgroup_size</code>

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
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c67b0)
Location: mm/memcontrol.c:1583
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff812c67b0-ffffffff812c67c2: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fc220)
Location: mm/memcontrol.c:1548
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff812fc220-ffffffff812fc232: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81308430)
Location: mm/memcontrol.c:1731
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff81308430-ffffffff81308442: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130ebb0)
Location: mm/memcontrol.c:1554
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff8130ebb0-ffffffff8130ebc2: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81359a20)
Location: mm/memcontrol.c:1606
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff81359a20-ffffffff81359a32: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d1a70)
Location: mm/memcontrol.c:1623
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff813d1a70-ffffffff813d1a88: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814570d0)
Location: mm/memcontrol.c:1683
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff814570d0-ffffffff814570e8: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148c9a0)
Location: mm/memcontrol.c:1717
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff8148c9a0-ffffffff8148c9b8: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bc2e0)
Location: mm/memcontrol.c:1789
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff814bc2e0-ffffffff814bc2f8: mem_cgroup_size (STB_GLOBAL)
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
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103695d8)
Location: mm/memcontrol.c:1583
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffff8000103695d8-ffff800010369600: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055aad4)
Location: mm/memcontrol.c:1583
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
c055aad4-c055aaf0: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000457e30)
Location: mm/memcontrol.c:1583
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
c000000000457e30-c000000000457e40: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002470a4)
Location: mm/memcontrol.c:1583
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffe0002470a4-ffffffe0002470c6: mem_cgroup_size (STB_GLOBAL)
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
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bed90)
Location: mm/memcontrol.c:1583
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff812bed90-ffffffff812beda2: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812afe80)
Location: mm/memcontrol.c:1583
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff812afe80-ffffffff812afe92: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bcba0)
Location: mm/memcontrol.c:1583
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff812bcba0-ffffffff812bcbb2: mem_cgroup_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int mem_cgroup_size(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cd390)
Location: mm/memcontrol.c:1583
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
```
**Symbols:**

```
ffffffff812cd390-ffffffff812cd3a2: mem_cgroup_size (STB_GLOBAL)
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
