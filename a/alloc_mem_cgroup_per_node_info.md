# Function: <code>alloc_mem_cgroup_per_node_info</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8189492d)
Location: mm/memcontrol.c:4131
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
In mm/memcontrol.c (ffffffff818c901f)
Location: mm/memcontrol.c:4106
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
In mm/memcontrol.c (ffffffff819005a8)
Location: mm/memcontrol.c:4126
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
In mm/memcontrol.c (ffffffff8198a59a)
Location: mm/memcontrol.c:4153
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
In mm/memcontrol.c (ffffffff819e6f20)
Location: mm/memcontrol.c:4087
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
In mm/memcontrol.c (ffffffff81a22320)
Location: mm/memcontrol.c:4360
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b2320)
Location: mm/memcontrol.c:4700
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c3cd0)
Location: mm/memcontrol.c:5020
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int alloc_mem_cgroup_per_node_info(struct mem_cgroup *memcg, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f5ee0)
Location: mm/memcontrol.c:4902
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
**Symbols:**

```
ffffffff812f5ee0-ffffffff812f5fbf: alloc_mem_cgroup_per_node_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int alloc_mem_cgroup_per_node_info(struct mem_cgroup *memcg, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81301510)
Location: mm/memcontrol.c:5164
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
**Symbols:**

```
ffffffff81301510-ffffffff813015f9: alloc_mem_cgroup_per_node_info (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff8130840c)
Location: mm/memcontrol.c:4932
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
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
In mm/memcontrol.c (ffffffff813524f3)
Location: mm/memcontrol.c:5099
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cabac)
Location: mm/memcontrol.c:5063
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8144f66f)
Location: mm/memcontrol.c:5207
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148519f)
Location: mm/memcontrol.c:5234
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b7376)
Location: mm/memcontrol.c:5431
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103626d0)
Location: mm/memcontrol.c:5020
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
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
In mm/memcontrol.c (c0e98c74)
Location: mm/memcontrol.c:5020
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
In mm/memcontrol.c (c00000000045bab4)
Location: mm/memcontrol.c:5020
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
In mm/memcontrol.c (ffffffe0008c4770)
Location: mm/memcontrol.c:5020
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bc2b0)
Location: mm/memcontrol.c:5020
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ad410)
Location: mm/memcontrol.c:5020
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ba0c0)
Location: mm/memcontrol.c:5020
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ca780)
Location: mm/memcontrol.c:5020
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
