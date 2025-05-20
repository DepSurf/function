# Function: <code>shrink_slab_memcg</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81218f4e)
Location: mm/vmscan.c:583
Inline: True
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
In mm/vmscan.c (ffffffff81228fe9)
Location: mm/vmscan.c:595
Inline: True
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
In mm/vmscan.c (ffffffff81236d89)
Location: mm/vmscan.c:593
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81266970)
Location: mm/vmscan.c:550
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
```
**Symbols:**

```
ffffffff81266970-ffffffff81266b39: shrink_slab_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812713c0)
Location: mm/vmscan.c:543
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
```
**Symbols:**

```
ffffffff812713c0-ffffffff8127158f: shrink_slab_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812765c0)
Location: mm/vmscan.c:744
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
```
**Symbols:**

```
ffffffff812765c0-ffffffff81276798: shrink_slab_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b3de0)
Location: mm/vmscan.c:790
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
```
**Symbols:**

```
ffffffff812b3de0-ffffffff812b3fb5: shrink_slab_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130fd80)
Location: mm/vmscan.c:802
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
```
**Symbols:**

```
ffffffff8130fd80-ffffffff8130ff63: shrink_slab_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813833a0)
Location: mm/vmscan.c:879
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
```
**Symbols:**

```
ffffffff813833a0-ffffffff8138356f: shrink_slab_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b4bd0)
Location: mm/vmscan.c:932
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
```
**Symbols:**

```
ffffffff813b4bd0-ffffffff813b4d99: shrink_slab_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int shrink_slab_memcg(gfp_t gfp_mask, int nid, struct mem_cgroup *memcg, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shrinker.c (ffffffff813e48d0)
Location: mm/shrinker.c:467
Inline: False
Direct callers:
  - mm/shrinker.c:shrink_slab
```
**Symbols:**

```
ffffffff813e48d0-ffffffff813e4b78: shrink_slab_memcg (STB_LOCAL)
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
In mm/vmscan.c (ffff8000102c83b4)
Location: mm/vmscan.c:593
Inline: True
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
In mm/vmscan.c (c04f1b68)
Location: mm/vmscan.c:593
Inline: True
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
In mm/vmscan.c (c000000000382d30)
Location: mm/vmscan.c:593
Inline: True
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
In mm/vmscan.c (ffffffe0001e6e16)
Location: mm/vmscan.c:593
Inline: True
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
In mm/vmscan.c (ffffffff8122f3d9)
Location: mm/vmscan.c:593
Inline: True
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
In mm/vmscan.c (ffffffff81222499)
Location: mm/vmscan.c:593
Inline: True
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
In mm/vmscan.c (ffffffff8122d179)
Location: mm/vmscan.c:593
Inline: True
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
In mm/vmscan.c (ffffffff8123c591)
Location: mm/vmscan.c:593
Inline: True
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
