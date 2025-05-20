# Function: <code>mem_cgroup_resize_max</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812808b0)
Location: mm/memcontrol.c:2449
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff812808b0-ffffffff81280a3a: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81295450)
Location: mm/memcontrol.c:2723
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff81295450-ffffffff812955da: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b1400)
Location: mm/memcontrol.c:2958
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff812b1400-ffffffff812b157a: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c2de0)
Location: mm/memcontrol.c:3167
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff812c2de0-ffffffff812c2f5a: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f8880)
Location: mm/memcontrol.c:3050
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff812f8880-ffffffff812f8a02: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81304710)
Location: mm/memcontrol.c:3355
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff81304710-ffffffff813048b9: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130b710)
Location: mm/memcontrol.c:3191
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff8130b710-ffffffff8130b8b9: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813569c0)
Location: mm/memcontrol.c:3359
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff813569c0-ffffffff81356b69: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cf8a0)
Location: mm/memcontrol.c:3364
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff813cf8a0-ffffffff813cfa7c: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81454d30)
Location: mm/memcontrol.c:3464
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff81454d30-ffffffff81454edc: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148ab40)
Location: mm/memcontrol.c:3475
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff8148ab40-ffffffff8148acec: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814ba410)
Location: mm/memcontrol.c:3667
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff814ba410-ffffffff814ba5bc: mem_cgroup_resize_max (STB_LOCAL)
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
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103657f0)
Location: mm/memcontrol.c:3167
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffff8000103657f0-ffff8000103659b0: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055725c)
Location: mm/memcontrol.c:3167
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
c055725c-c0557400: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000452370)
Location: mm/memcontrol.c:3167
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
c000000000452370-c0000000004525a8: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000243f36)
Location: mm/memcontrol.c:3167
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffe000243f36-ffffffe000244084: mem_cgroup_resize_max (STB_LOCAL)
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
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bb3c0)
Location: mm/memcontrol.c:3167
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff812bb3c0-ffffffff812bb53a: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ac530)
Location: mm/memcontrol.c:3167
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff812ac530-ffffffff812ac6aa: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b91d0)
Location: mm/memcontrol.c:3167
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff812b91d0-ffffffff812b934a: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mem_cgroup_resize_max(struct mem_cgroup *memcg, long unsigned int max, bool memsw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c9850)
Location: mm/memcontrol.c:3167
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
```
**Symbols:**

```
ffffffff812c9850-ffffffff812c99ca: mem_cgroup_resize_max (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
