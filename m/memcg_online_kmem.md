# Function: <code>memcg_online_kmem</code>

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
In mm/memcontrol.c (ffffffff81894be7)
Location: mm/memcontrol.c:2847
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
In mm/memcontrol.c (ffffffff818c930a)
Location: mm/memcontrol.c:2820
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
In mm/memcontrol.c (ffffffff81900887)
Location: mm/memcontrol.c:2825
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
In mm/memcontrol.c (ffffffff8198a894)
Location: mm/memcontrol.c:2852
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
In mm/memcontrol.c (ffffffff819e7190)
Location: mm/memcontrol.c:2783
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
In mm/memcontrol.c (ffffffff81a225ff)
Location: mm/memcontrol.c:3062
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
In mm/memcontrol.c (ffffffff81a92647)
Location: mm/memcontrol.c:3328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (ffffffff81ac9df7)
Location: mm/memcontrol.c:3522
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81bc23ae)
Location: mm/memcontrol.c:3405
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memcg_online_kmem(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813012e0)
Location: mm/memcontrol.c:3677
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff813012e0-ffffffff81301480: memcg_online_kmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int memcg_online_kmem(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81307910)
Location: mm/memcontrol.c:3464
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff81307910-ffffffff81307aae: memcg_online_kmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int memcg_online_kmem(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3631
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff81351360-ffffffff8135150d: memcg_online_kmem (STB_LOCAL)
ffffffff81cc2781-ffffffff81cc2796: memcg_online_kmem.cold (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff813cb647)
Location: mm/memcontrol.c:3624
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (ffffffff81450317)
Location: mm/memcontrol.c:3725
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (ffffffff81485e07)
Location: mm/memcontrol.c:3752
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (ffffffff814b4d37)
Location: mm/memcontrol.c:3944
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
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
In mm/memcontrol.c (ffff800010d9d6d8)
Location: mm/memcontrol.c:3522
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (c0e98e60)
Location: mm/memcontrol.c:3522
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
In mm/memcontrol.c (c00000000045bd58)
Location: mm/memcontrol.c:3522
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
In mm/memcontrol.c (ffffffe0008c494c)
Location: mm/memcontrol.c:3522
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
In mm/memcontrol.c (ffffffff81a68c67)
Location: mm/memcontrol.c:3522
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (ffffffff81a25727)
Location: mm/memcontrol.c:3522
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (ffffffff81ad5077)
Location: mm/memcontrol.c:3522
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
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
In mm/memcontrol.c (ffffffff81ae1547)
Location: mm/memcontrol.c:3522
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
