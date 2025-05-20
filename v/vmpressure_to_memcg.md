# Function: <code>vmpressure_to_memcg</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mem_cgroup *vmpressure_to_memcg(struct vmpressure *vmpr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81356260)
Location: mm/memcontrol.c:251
Inline: False
Direct callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
**Symbols:**

```
ffffffff81356260-ffffffff81356272: vmpressure_to_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mem_cgroup *vmpressure_to_memcg(struct vmpressure *vmpr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cee20)
Location: mm/memcontrol.c:250
Inline: False
Direct callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
**Symbols:**

```
ffffffff813cee20-ffffffff813cee38: vmpressure_to_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mem_cgroup *vmpressure_to_memcg(struct vmpressure *vmpr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81453f40)
Location: mm/memcontrol.c:243
Inline: False
Direct callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
**Symbols:**

```
ffffffff81453f40-ffffffff81453f58: vmpressure_to_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mem_cgroup *vmpressure_to_memcg(struct vmpressure *vmpr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81489ce0)
Location: mm/memcontrol.c:247
Inline: False
Direct callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
**Symbols:**

```
ffffffff81489ce0-ffffffff81489cf8: vmpressure_to_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mem_cgroup *vmpressure_to_memcg(struct vmpressure *vmpr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b94c0)
Location: mm/memcontrol.c:248
Inline: False
Direct callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
**Symbols:**

```
ffffffff814b94c0-ffffffff814b94d8: vmpressure_to_memcg (STB_GLOBAL)
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
