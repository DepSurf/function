# Function: <code>bpf_fd_array_map_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81178390)
Location: kernel/bpf/arraymap.c:252
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
  - kernel/bpf/arraymap.c:perf_event_array_map_free
```
**Symbols:**

```
ffffffff81178390-ffffffff811783d9: bpf_fd_array_map_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81187a73)
Location: kernel/bpf/arraymap.c:397
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
**Symbols:**

```
ffffffff81187df0-ffffffff81187e3d: bpf_fd_array_map_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81195873)
Location: kernel/bpf/arraymap.c:393
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
**Symbols:**

```
ffffffff81195db0-ffffffff81195dfd: bpf_fd_array_map_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8119cd4c)
Location: kernel/bpf/arraymap.c:429
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
**Symbols:**

```
ffffffff8119d320-ffffffff8119d36e: bpf_fd_array_map_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ac7ec)
Location: kernel/bpf/arraymap.c:474
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
**Symbols:**

```
ffffffff811aced0-ffffffff811acf26: bpf_fd_array_map_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811c3dd8)
Location: kernel/bpf/arraymap.c:529
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
```
**Symbols:**

```
ffffffff811c37d0-ffffffff811c3824: bpf_fd_array_map_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811d5a98)
Location: kernel/bpf/arraymap.c:548
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
```
**Symbols:**

```
ffffffff811d52b0-ffffffff811d5304: bpf_fd_array_map_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ea428)
Location: kernel/bpf/arraymap.c:596
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
```
**Symbols:**

```
ffffffff811e9a70-ffffffff811e9ac4: bpf_fd_array_map_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811f6b88)
Location: kernel/bpf/arraymap.c:596
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
```
**Symbols:**

```
ffffffff811f61d0-ffffffff811f6224: bpf_fd_array_map_clear (STB_LOCAL)
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
In kernel/bpf/arraymap.c (ffffffff8121a44a)
Location: kernel/bpf/arraymap.c:664
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
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
In kernel/bpf/arraymap.c (ffffffff8121d85a)
Location: kernel/bpf/arraymap.c:803
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8122137a)
Location: kernel/bpf/arraymap.c:845
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81258d0a)
Location: kernel/bpf/arraymap.c:866
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812a1b5b)
Location: kernel/bpf/arraymap.c:897
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812ff0db)
Location: kernel/bpf/arraymap.c:903
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8132dccb)
Location: kernel/bpf/arraymap.c:927
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8135208b)
Location: kernel/bpf/arraymap.c:933
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
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
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffff80001027b680)
Location: kernel/bpf/arraymap.c:596
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
```
**Symbols:**

```
ffff80001027b680-ffff80001027b700: bpf_fd_array_map_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c04ad6b8)
Location: kernel/bpf/arraymap.c:596
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
```
**Symbols:**

```
c04ad6b8-c04ad744: bpf_fd_array_map_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c000000000323a70)
Location: kernel/bpf/arraymap.c:596
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
```
**Symbols:**

```
c000000000323a70-c000000000323b20: bpf_fd_array_map_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffe0001b3046)
Location: kernel/bpf/arraymap.c:596
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
```
**Symbols:**

```
ffffffe0001b2610-ffffffe0001b266a: bpf_fd_array_map_clear (STB_LOCAL)
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
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ef1a8)
Location: kernel/bpf/arraymap.c:596
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
```
**Symbols:**

```
ffffffff811ee7f0-ffffffff811ee844: bpf_fd_array_map_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e1f38)
Location: kernel/bpf/arraymap.c:596
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
```
**Symbols:**

```
ffffffff811e1580-ffffffff811e15d4: bpf_fd_array_map_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ecf78)
Location: kernel/bpf/arraymap.c:596
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
```
**Symbols:**

```
ffffffff811ec5c0-ffffffff811ec614: bpf_fd_array_map_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bpf_fd_array_map_clear(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811fb418)
Location: kernel/bpf/arraymap.c:596
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
```
**Symbols:**

```
ffffffff811faa30-ffffffff811faa84: bpf_fd_array_map_clear (STB_LOCAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
