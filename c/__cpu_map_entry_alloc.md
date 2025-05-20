# Function: <code>__cpu_map_entry_alloc</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_entry_alloc(u32 qsize, u32 cpu, int map_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811aff00)
Location: kernel/bpf/cpumap.c:340
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff811aff00-ffffffff811b00ab: __cpu_map_entry_alloc (STB_GLOBAL)
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
In kernel/bpf/cpumap.c (ffffffff811ca716)
Location: kernel/bpf/cpumap.c:302
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
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
In kernel/bpf/cpumap.c (ffffffff811de048)
Location: kernel/bpf/cpumap.c:302
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
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
In kernel/bpf/cpumap.c (ffffffff811f3706)
Location: kernel/bpf/cpumap.c:334
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
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
In kernel/bpf/cpumap.c (ffffffff812004a6)
Location: kernel/bpf/cpumap.c:334
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_entry_alloc(u32 qsize, u32 cpu, int map_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81227ee0)
Location: kernel/bpf/cpumap.c:310
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff81227ee0-ffffffff812280ce: __cpu_map_entry_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_entry_alloc(struct bpf_map *map, struct bpf_cpumap_val *value, u32 cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8122e710)
Location: kernel/bpf/cpumap.c:401
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff8122e710-ffffffff8122e96b: __cpu_map_entry_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_entry_alloc(struct bpf_map *map, struct bpf_cpumap_val *value, u32 cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812335f0)
Location: kernel/bpf/cpumap.c:359
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff812335f0-ffffffff8123384a: __cpu_map_entry_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_entry_alloc(struct bpf_map *map, struct bpf_cpumap_val *value, u32 cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8126d250)
Location: kernel/bpf/cpumap.c:420
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff8126d250-ffffffff8126d50c: __cpu_map_entry_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_entry_alloc(struct bpf_map *map, struct bpf_cpumap_val *value, u32 cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812bc390)
Location: kernel/bpf/cpumap.c:423
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff812bc390-ffffffff812bc667: __cpu_map_entry_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_entry_alloc(struct bpf_map *map, struct bpf_cpumap_val *value, u32 cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8131f890)
Location: kernel/bpf/cpumap.c:422
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff8131f890-ffffffff8131fb7e: __cpu_map_entry_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_entry_alloc(struct bpf_map *map, struct bpf_cpumap_val *value, u32 cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8134f890)
Location: kernel/bpf/cpumap.c:426
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff8134f890-ffffffff8134fb9f: __cpu_map_entry_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_cpu_map_entry *__cpu_map_entry_alloc(struct bpf_map *map, struct bpf_cpumap_val *value, u32 cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81376da0)
Location: kernel/bpf/cpumap.c:386
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff81376da0-ffffffff813770a4: __cpu_map_entry_alloc (STB_LOCAL)
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
In kernel/bpf/cpumap.c (ffff80001028879c)
Location: kernel/bpf/cpumap.c:334
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
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
In kernel/bpf/cpumap.c (c04b7d30)
Location: kernel/bpf/cpumap.c:334
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
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
In kernel/bpf/cpumap.c (c000000000333c74)
Location: kernel/bpf/cpumap.c:334
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
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
In kernel/bpf/cpumap.c (ffffffe0001bc912)
Location: kernel/bpf/cpumap.c:334
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
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
In kernel/bpf/cpumap.c (ffffffff811f8ac6)
Location: kernel/bpf/cpumap.c:334
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
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
In kernel/bpf/cpumap.c (ffffffff811eb816)
Location: kernel/bpf/cpumap.c:334
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
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
In kernel/bpf/cpumap.c (ffffffff811f6896)
Location: kernel/bpf/cpumap.c:334
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
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
In kernel/bpf/cpumap.c (ffffffff812054c6)
Location: kernel/bpf/cpumap.c:334
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_map *map</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_cpumap_val *value</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 qsize</code>
</li>
<li>
<b>Param removed. </b>
<code>int map_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>qsize, cpu, map_id</code> ➡️ <code>map, value, cpu</code>
</li>
</ul>
</details>
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
