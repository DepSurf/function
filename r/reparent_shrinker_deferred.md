# Function: <code>reparent_shrinker_deferred</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void reparent_shrinker_deferred(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812768c0)
Location: mm/vmscan.c:403
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff812768c0-ffffffff812769ac: reparent_shrinker_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reparent_shrinker_deferred(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b40d0)
Location: mm/vmscan.c:407
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff812b40d0-ffffffff812b41bc: reparent_shrinker_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void reparent_shrinker_deferred(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81310090)
Location: mm/vmscan.c:409
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff81310090-ffffffff81310179: reparent_shrinker_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reparent_shrinker_deferred(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813836b0)
Location: mm/vmscan.c:423
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff813836b0-ffffffff81383789: reparent_shrinker_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reparent_shrinker_deferred(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b50c0)
Location: mm/vmscan.c:408
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff813b50c0-ffffffff813b5195: reparent_shrinker_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reparent_shrinker_deferred(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shrinker.c (ffffffff813e4b90)
Location: mm/shrinker.c:283
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
```
**Symbols:**

```
ffffffff813e4b90-ffffffff813e4d23: reparent_shrinker_deferred (STB_GLOBAL)
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
