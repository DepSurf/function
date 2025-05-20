# Function: <code>__queue_map_get</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811d8920)
Location: kernel/bpf/queue_stack_maps.c:115
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff811d8920-ffffffff811d89c7: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811ed440)
Location: kernel/bpf/queue_stack_maps.c:114
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff811ed440-ffffffff811ed4f1: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811f9b50)
Location: kernel/bpf/queue_stack_maps.c:114
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff811f9b50-ffffffff811f9c01: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff8121d9c0)
Location: kernel/bpf/queue_stack_maps.c:114
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff8121d9c0-ffffffff8121da71: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff812207f0)
Location: kernel/bpf/queue_stack_maps.c:99
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff812207f0-ffffffff812208a1: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff81224280)
Location: kernel/bpf/queue_stack_maps.c:99
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff81224280-ffffffff81224331: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff8125c1c0)
Location: kernel/bpf/queue_stack_maps.c:99
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff8125c1c0-ffffffff8125c271: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff812a5e60)
Location: kernel/bpf/queue_stack_maps.c:100
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff812a5e60-ffffffff812a5f19: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff813040a0)
Location: kernel/bpf/queue_stack_maps.c:98
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff813040a0-ffffffff8130415b: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff81332a30)
Location: kernel/bpf/queue_stack_maps.c:94
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff81332a30-ffffffff81332aee: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff81357000)
Location: kernel/bpf/queue_stack_maps.c:94
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff81357000-ffffffff81357120: __queue_map_get (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffff80001027fb50)
Location: kernel/bpf/queue_stack_maps.c:114
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffff80001027fb50-ffff80001027fc60: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (c04b0938)
Location: kernel/bpf/queue_stack_maps.c:114
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
c04b0938-c04b09e4: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (c0000000003297d0)
Location: kernel/bpf/queue_stack_maps.c:114
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
c0000000003297d0-c0000000003298dc: __queue_map_get (STB_LOCAL)
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
In kernel/bpf/queue_stack_maps.c (ffffffe0001b620c)
Location: kernel/bpf/queue_stack_maps.c:114
Inline: True
Inline callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
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
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811f2170)
Location: kernel/bpf/queue_stack_maps.c:114
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff811f2170-ffffffff811f2221: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811e4ec0)
Location: kernel/bpf/queue_stack_maps.c:114
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff811e4ec0-ffffffff811e4f71: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811eff40)
Location: kernel/bpf/queue_stack_maps.c:114
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff811eff40-ffffffff811efff1: __queue_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __queue_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811fe450)
Location: kernel/bpf/queue_stack_maps.c:114
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:queue_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:queue_map_peek_elem
```
**Symbols:**

```
ffffffff811fe450-ffffffff811fe501: __queue_map_get (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
