# Function: <code>bpf_prog_array_update_at</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array *array, int index, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9e65)
Location: kernel/bpf/core.c:1998
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_delete_safe_at
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
**Symbols:**

```
ffffffff811f9eb0-ffffffff811f9efe: bpf_prog_array_update_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array *array, int index, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fadd5)
Location: kernel/bpf/core.c:2094
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_delete_safe_at
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
**Symbols:**

```
ffffffff811fae20-ffffffff811fae6b: bpf_prog_array_update_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array *array, int index, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122c4e5)
Location: kernel/bpf/core.c:2107
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_delete_safe_at
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
**Symbols:**

```
ffffffff8122c530-ffffffff8122c57b: bpf_prog_array_update_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array *array, int index, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126e135)
Location: kernel/bpf/core.c:2393
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_delete_safe_at
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
**Symbols:**

```
ffffffff8126e1a0-ffffffff8126e20f: bpf_prog_array_update_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array *array, int index, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c3765)
Location: kernel/bpf/core.c:2387
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_delete_safe_at
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
**Symbols:**

```
ffffffff812c37e0-ffffffff812c384f: bpf_prog_array_update_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array *array, int index, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812ea5b5)
Location: kernel/bpf/core.c:2404
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_delete_safe_at
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
**Symbols:**

```
ffffffff812ea630-ffffffff812ea69f: bpf_prog_array_update_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_prog_array_update_at(struct bpf_prog_array *array, int index, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff813088c5)
Location: kernel/bpf/core.c:2580
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_delete_safe_at
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_update_prog
```
**Symbols:**

```
ffffffff81308940-ffffffff813089af: bpf_prog_array_update_at (STB_GLOBAL)
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
