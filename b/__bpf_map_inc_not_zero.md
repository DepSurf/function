# Function: <code>__bpf_map_inc_not_zero</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e0860)
Location: kernel/bpf/syscall.c:689
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffffffff811e0860-ffffffff811e08ba: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb430)
Location: kernel/bpf/syscall.c:955
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffffffff811fb430-ffffffff811fb47b: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fa590)
Location: kernel/bpf/syscall.c:968
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffffffff811fa590-ffffffff811fa5db: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb4f0)
Location: kernel/bpf/syscall.c:969
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffffffff811fb4f0-ffffffff811fb53b: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122cc60)
Location: kernel/bpf/syscall.c:996
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffffffff8122cc60-ffffffff8122ccab: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126ef90)
Location: kernel/bpf/syscall.c:1231
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffffffff8126ef90-ffffffff8126eff3: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c47d0)
Location: kernel/bpf/syscall.c:1274
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffffffff812c47d0-ffffffff812c4833: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f2470)
Location: kernel/bpf/syscall.c:1351
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
**Symbols:**

```
ffffffff812f2470-ffffffff812f24d3: __bpf_map_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81311310)
Location: kernel/bpf/syscall.c:1382
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_curr_or_next
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_get
```
**Symbols:**

```
ffffffff81311310-ffffffff81311373: __bpf_map_inc_not_zero (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010262d48)
Location: kernel/bpf/syscall.c:689
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffff800010262d48-ffff800010262e20: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (c0495a2c)
Location: kernel/bpf/syscall.c:689
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
c0493288-c04932bc: __bpf_map_inc_not_zero.part.0 (STB_LOCAL)
c0495a2c-c0495aac: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000307ec0)
Location: kernel/bpf/syscall.c:689
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
c000000000307ec0-c000000000307f68: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f76a)
Location: kernel/bpf/syscall.c:689
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffffffe00019f76a-ffffffe00019f7ec: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8e80)
Location: kernel/bpf/syscall.c:689
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffffffff811d8e80-ffffffff811d8eda: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cbc40)
Location: kernel/bpf/syscall.c:689
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffffffff811cbc40-ffffffff811cbc9a: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6c50)
Location: kernel/bpf/syscall.c:689
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffffffff811d6c50-ffffffff811d6caa: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *__bpf_map_inc_not_zero(struct bpf_map *map, bool uref);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e4fc0)
Location: kernel/bpf/syscall.c:689
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_inc_not_zero
```
**Symbols:**

```
ffffffff811e4fc0-ffffffff811e501a: __bpf_map_inc_not_zero (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
