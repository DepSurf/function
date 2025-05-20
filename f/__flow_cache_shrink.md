# Function: <code>__flow_cache_shrink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __flow_cache_shrink(struct flow_cache *fc, struct flow_cache_percpu *fcp, int shrink_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow.c (ffffffff817345f0)
Location: net/core/flow.c:112
Inline: False
Direct callers:
  - net/core/flow.c:flow_cache_lookup
  - net/core/flow.c:flow_cache_lookup
  - net/core/flow.c:flow_cache_cpu
```
**Symbols:**

```
ffffffff817345f0-ffffffff8173474a: __flow_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __flow_cache_shrink(struct flow_cache *fc, struct flow_cache_percpu *fcp, int shrink_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow.c (ffffffff817a06d0)
Location: net/core/flow.c:116
Inline: False
Direct callers:
  - net/core/flow.c:flow_cache_cpu
  - net/core/flow.c:flow_cache_lookup
  - net/core/flow.c:flow_cache_lookup
```
**Symbols:**

```
ffffffff817a06d0-ffffffff817a0833: __flow_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __flow_cache_shrink(struct flow_cache *fc, struct flow_cache_percpu *fcp, int shrink_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow.c (ffffffff817cf2d0)
Location: net/core/flow.c:115
Inline: False
Direct callers:
  - net/core/flow.c:flow_cache_cpu_dead
  - net/core/flow.c:flow_cache_lookup
  - net/core/flow.c:flow_cache_lookup
```
**Symbols:**

```
ffffffff817cf2d0-ffffffff817cf433: __flow_cache_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __flow_cache_shrink(struct flow_cache *fc, struct flow_cache_percpu *fcp, unsigned int shrink_to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow.c (ffffffff817ee660)
Location: net/core/flow.c:116
Inline: False
Direct callers:
  - net/core/flow.c:flow_cache_cpu_dead
  - net/core/flow.c:flow_cache_lookup
  - net/core/flow.c:flow_cache_lookup
```
**Symbols:**

```
ffffffff817ee660-ffffffff817ee7c4: __flow_cache_shrink (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int shrink_to</code> ➡️ <code>unsigned int shrink_to</code>
</li>
</ul>
</details>
</li>
</ul>
