# Function: <code>memcg_flush_percpu_vmstats</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memcg_flush_percpu_vmstats(struct mem_cgroup *memcg, bool slab_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812adcd0)
Location: mm/memcontrol.c:3261
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_free
```
**Symbols:**

```
ffffffff812adcd0-ffffffff812ae04a: memcg_flush_percpu_vmstats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memcg_flush_percpu_vmstats(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf820)
Location: mm/memcontrol.c:3470
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffffffff812bf820-ffffffff812bfa4a: memcg_flush_percpu_vmstats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memcg_flush_percpu_vmstats(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f4950)
Location: mm/memcontrol.c:3353
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812f4950-ffffffff812f4b6f: memcg_flush_percpu_vmstats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memcg_flush_percpu_vmstats(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81300210)
Location: mm/memcontrol.c:3625
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff81300210-ffffffff8130042f: memcg_flush_percpu_vmstats (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
void memcg_flush_percpu_vmstats(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103637b8)
Location: mm/memcontrol.c:3470
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffff8000103637b8-ffff800010363a30: memcg_flush_percpu_vmstats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memcg_flush_percpu_vmstats(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0553cb0)
Location: mm/memcontrol.c:3470
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
c0553cb0-c0553e98: memcg_flush_percpu_vmstats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memcg_flush_percpu_vmstats(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000044c980)
Location: mm/memcontrol.c:3470
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
c00000000044c980-c00000000044ccd4: memcg_flush_percpu_vmstats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memcg_flush_percpu_vmstats(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000240d48)
Location: mm/memcontrol.c:3470
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffffffe000240d48-ffffffe000240ee6: memcg_flush_percpu_vmstats (STB_LOCAL)
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
void memcg_flush_percpu_vmstats(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b7e00)
Location: mm/memcontrol.c:3470
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffffffff812b7e00-ffffffff812b802a: memcg_flush_percpu_vmstats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memcg_flush_percpu_vmstats(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812a8fd0)
Location: mm/memcontrol.c:3470
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffffffff812a8fd0-ffffffff812a91fa: memcg_flush_percpu_vmstats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memcg_flush_percpu_vmstats(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5c10)
Location: mm/memcontrol.c:3470
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffffffff812b5c10-ffffffff812b5e3a: memcg_flush_percpu_vmstats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memcg_flush_percpu_vmstats(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6130)
Location: mm/memcontrol.c:3470
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffffffff812c6130-ffffffff812c635a: memcg_flush_percpu_vmstats (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool slab_only</code>
</li>
</ul>
</details>
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
