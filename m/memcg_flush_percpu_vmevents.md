# Function: <code>memcg_flush_percpu_vmevents</code>

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
void memcg_flush_percpu_vmevents(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ad9a0)
Location: mm/memcontrol.c:3308
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_free
```
**Symbols:**

```
ffffffff812ad9a0-ffffffff812ada98: memcg_flush_percpu_vmevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memcg_flush_percpu_vmevents(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf4f0)
Location: mm/memcontrol.c:3502
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffffffff812bf4f0-ffffffff812bf5e8: memcg_flush_percpu_vmevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memcg_flush_percpu_vmevents(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f4810)
Location: mm/memcontrol.c:3385
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff812f4810-ffffffff812f48fe: memcg_flush_percpu_vmevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memcg_flush_percpu_vmevents(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813000f0)
Location: mm/memcontrol.c:3657
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
**Symbols:**

```
ffffffff813000f0-ffffffff813001de: memcg_flush_percpu_vmevents (STB_LOCAL)
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
void memcg_flush_percpu_vmevents(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010363470)
Location: mm/memcontrol.c:3502
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffff800010363470-ffff8000103635a8: memcg_flush_percpu_vmevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memcg_flush_percpu_vmevents(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0553e98)
Location: mm/memcontrol.c:3502
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
c0553e98-c0553fb8: memcg_flush_percpu_vmevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memcg_flush_percpu_vmevents(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000044c730)
Location: mm/memcontrol.c:3502
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
c00000000044c730-c00000000044c8a8: memcg_flush_percpu_vmevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memcg_flush_percpu_vmevents(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000240ee6)
Location: mm/memcontrol.c:3502
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffffffe000240ee6-ffffffe000240fe2: memcg_flush_percpu_vmevents (STB_LOCAL)
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
void memcg_flush_percpu_vmevents(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b7ad0)
Location: mm/memcontrol.c:3502
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffffffff812b7ad0-ffffffff812b7bc8: memcg_flush_percpu_vmevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memcg_flush_percpu_vmevents(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812a8ca0)
Location: mm/memcontrol.c:3502
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffffffff812a8ca0-ffffffff812a8d98: memcg_flush_percpu_vmevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memcg_flush_percpu_vmevents(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b58e0)
Location: mm/memcontrol.c:3502
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffffffff812b58e0-ffffffff812b59d8: memcg_flush_percpu_vmevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memcg_flush_percpu_vmevents(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c5e00)
Location: mm/memcontrol.c:3502
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_free
```
**Symbols:**

```
ffffffff812c5e00-ffffffff812c5ef8: memcg_flush_percpu_vmevents (STB_LOCAL)
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
