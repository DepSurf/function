# Function: <code>mem_cgroup_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8181a9e6)
Location: mm/memcontrol.c:4157
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81894896)
Location: mm/memcontrol.c:4174
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff818c8f86)
Location: mm/memcontrol.c:4154
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81900515)
Location: mm/memcontrol.c:4183
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8198a4e6)
Location: mm/memcontrol.c:4210
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff819e6e15)
Location: mm/memcontrol.c:4147
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81a22275)
Location: mm/memcontrol.c:4420
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b21b0)
Location: mm/memcontrol.c:4775
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812b21b0-ffffffff812b24ae: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c3b60)
Location: mm/memcontrol.c:5095
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812c3b60-ffffffff812c3ee1: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f6510)
Location: mm/memcontrol.c:4977
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812f6510-ffffffff812f67f4: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813018d0)
Location: mm/memcontrol.c:5241
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff813018d0-ffffffff81301bd6: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813082a0)
Location: mm/memcontrol.c:5010
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff813082a0-ffffffff81308625: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813523b0)
Location: mm/memcontrol.c:5160
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff813523b0-ffffffff813526fc: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cab10)
Location: mm/memcontrol.c:5112
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff813cab10-ffffffff813cae4e: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8144f5b0)
Location: mm/memcontrol.c:5258
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff8144f5b0-ffffffff8144f90b: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814850e0)
Location: mm/memcontrol.c:5285
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff814850e0-ffffffff8148543b: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc(struct mem_cgroup *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b71c0)
Location: mm/memcontrol.c:5485
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff814b71c0-ffffffff814b76aa: mem_cgroup_alloc (STB_LOCAL)
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
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103625a8)
Location: mm/memcontrol.c:5095
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffff8000103625a8-ffff80001036289c: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0e98bf8)
Location: mm/memcontrol.c:5095
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045b904)
Location: mm/memcontrol.c:5095
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0008c46fc)
Location: mm/memcontrol.c:5095
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bc140)
Location: mm/memcontrol.c:5095
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812bc140-ffffffff812bc4c1: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ad2a0)
Location: mm/memcontrol.c:5095
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812ad2a0-ffffffff812ad621: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b9f50)
Location: mm/memcontrol.c:5095
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812b9f50-ffffffff812ba2d1: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ca610)
Location: mm/memcontrol.c:5095
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812ca610-ffffffff812ca991: mem_cgroup_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mem_cgroup *parent</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
