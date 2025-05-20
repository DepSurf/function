# Function: <code>__xdp_map_lookup_elem</code>

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
void *__xdp_map_lookup_elem(struct bpf_map *map, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818648b0)
Location: net/core/filter.c:2587
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect_map
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff818648b0-ffffffff818648d8: __xdp_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__xdp_map_lookup_elem(struct bpf_map *map, u32 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b1a60)
Location: net/core/filter.c:3225
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff818b1a60-ffffffff818b1a94: __xdp_map_lookup_elem (STB_LOCAL)
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
In net/core/filter.c (ffffffff818d9c73)
Location: net/core/filter.c:3439
Inline: True
Inline callers:
  - net/core/filter.c:xdp_do_generic_redirect
  - net/core/filter.c:xdp_do_redirect
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
In net/core/filter.c (ffffffff81923ca1)
Location: net/core/filter.c:3572
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
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
In net/core/filter.c (ffffffff81955fa1)
Location: net/core/filter.c:3576
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a299d5)
Location: net/core/filter.c:3540
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2a335)
Location: net/core/filter.c:3947
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bff918)
Location: net/core/filter.c:3576
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
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
In net/core/filter.c (c0d114f8)
Location: net/core/filter.c:3576
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
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
In net/core/filter.c (c000000000cddde0)
Location: net/core/filter.c:3576
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
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
In net/core/filter.c (ffffffe0007796ee)
Location: net/core/filter.c:3576
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
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
In net/core/filter.c (ffffffff818f5f71)
Location: net/core/filter.c:3576
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
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
In net/core/filter.c (ffffffff818afda1)
Location: net/core/filter.c:3576
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
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
In net/core/filter.c (ffffffff81946fa1)
Location: net/core/filter.c:3576
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
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
In net/core/filter.c (ffffffff819688b1)
Location: net/core/filter.c:3576
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
