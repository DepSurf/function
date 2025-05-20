# Function: <code>__stack_map_get</code>

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
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811d8b00)
Location: kernel/bpf/queue_stack_maps.c:144
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff811d8b00-ffffffff811d8bb1: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811ed640)
Location: kernel/bpf/queue_stack_maps.c:143
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff811ed640-ffffffff811ed6f1: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811f9d50)
Location: kernel/bpf/queue_stack_maps.c:143
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff811f9d50-ffffffff811f9e01: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff8121dbb0)
Location: kernel/bpf/queue_stack_maps.c:143
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff8121dbb0-ffffffff8121dc66: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff812209e0)
Location: kernel/bpf/queue_stack_maps.c:128
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff812209e0-ffffffff81220a96: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff81224470)
Location: kernel/bpf/queue_stack_maps.c:128
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff81224470-ffffffff81224526: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff8125c3b0)
Location: kernel/bpf/queue_stack_maps.c:128
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff8125c3b0-ffffffff8125c466: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff812a6060)
Location: kernel/bpf/queue_stack_maps.c:129
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff812a6060-ffffffff812a611c: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff813042e0)
Location: kernel/bpf/queue_stack_maps.c:127
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff813042e0-ffffffff8130439a: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff81332c70)
Location: kernel/bpf/queue_stack_maps.c:123
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff81332c70-ffffffff81332d2d: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff81357300)
Location: kernel/bpf/queue_stack_maps.c:128
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff81357300-ffffffff8135741c: __stack_map_get (STB_LOCAL)
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
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffff80001027f9d0)
Location: kernel/bpf/queue_stack_maps.c:143
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffff80001027f9d0-ffff80001027fae0: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (c04b0b0c)
Location: kernel/bpf/queue_stack_maps.c:143
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
c04b0b0c-c04b0ba8: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (c000000000329a80)
Location: kernel/bpf/queue_stack_maps.c:143
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
c000000000329a80-c000000000329bc8: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffe0001b6378)
Location: kernel/bpf/queue_stack_maps.c:143
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffe0001b6378-ffffffe0001b6426: __stack_map_get (STB_LOCAL)
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
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811f2370)
Location: kernel/bpf/queue_stack_maps.c:143
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff811f2370-ffffffff811f2421: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811e50c0)
Location: kernel/bpf/queue_stack_maps.c:143
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff811e50c0-ffffffff811e5171: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811f0140)
Location: kernel/bpf/queue_stack_maps.c:143
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff811f0140-ffffffff811f01f1: __stack_map_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __stack_map_get(struct bpf_map *map, void *value, bool delete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/queue_stack_maps.c (ffffffff811fe650)
Location: kernel/bpf/queue_stack_maps.c:143
Inline: False
Direct callers:
  - kernel/bpf/queue_stack_maps.c:stack_map_pop_elem
  - kernel/bpf/queue_stack_maps.c:stack_map_peek_elem
```
**Symbols:**

```
ffffffff811fe650-ffffffff811fe701: __stack_map_get (STB_LOCAL)
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
