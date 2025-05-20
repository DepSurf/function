# Function: <code>memcg_reparent_list_lrus</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void memcg_reparent_list_lrus(struct mem_cgroup *memcg, struct mem_cgroup *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:430
Inline: False
```
**Symbols:**

```
ffffffff81e6d95c-ffffffff81e6d99a: memcg_reparent_list_lrus.cold (STB_LOCAL)
ffffffff813355f0-ffffffff8133589a: memcg_reparent_list_lrus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void memcg_reparent_list_lrus(struct mem_cgroup *memcg, struct mem_cgroup *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:430
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffff82063c77-ffffffff82063cb5: memcg_reparent_list_lrus.cold (STB_LOCAL)
ffffffff813ac3b0-ffffffff813ac64f: memcg_reparent_list_lrus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void memcg_reparent_list_lrus(struct mem_cgroup *memcg, struct mem_cgroup *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:430
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffff820e336e-ffffffff820e33ac: memcg_reparent_list_lrus.cold (STB_LOCAL)
ffffffff813e0750-ffffffff813e09e4: memcg_reparent_list_lrus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void memcg_reparent_list_lrus(struct mem_cgroup *memcg, struct mem_cgroup *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (0)
Location: mm/list_lru.c:431
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
```
**Symbols:**

```
ffffffff821bfdce-ffffffff821bfe0c: memcg_reparent_list_lrus.cold (STB_LOCAL)
ffffffff8140b020-ffffffff8140b2b4: memcg_reparent_list_lrus (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
