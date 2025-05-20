# Function: <code>bpf_map_get_curr_or_next</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201c50)
Location: kernel/bpf/syscall.c:3017
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/map_iter.c:bpf_map_seq_start
```
**Symbols:**

```
ffffffff81201c50-ffffffff81201cb0: bpf_map_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201640)
Location: kernel/bpf/syscall.c:3161
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/map_iter.c:bpf_map_seq_start
```
**Symbols:**

```
ffffffff81201640-ffffffff812016a0: bpf_map_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81202500)
Location: kernel/bpf/syscall.c:3184
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/map_iter.c:bpf_map_seq_start
```
**Symbols:**

```
ffffffff81202500-ffffffff81202560: bpf_map_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81234520)
Location: kernel/bpf/syscall.c:3367
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/map_iter.c:bpf_map_seq_start
```
**Symbols:**

```
ffffffff81234520-ffffffff81234580: bpf_map_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81277b20)
Location: kernel/bpf/syscall.c:3625
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/map_iter.c:bpf_map_seq_start
```
**Symbols:**

```
ffffffff81277b20-ffffffff81277b8a: bpf_map_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cdf00)
Location: kernel/bpf/syscall.c:3668
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/map_iter.c:bpf_map_seq_start
```
**Symbols:**

```
ffffffff812cdf00-ffffffff812cdf6a: bpf_map_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f5490)
Location: kernel/bpf/syscall.c:3804
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/map_iter.c:bpf_map_seq_start
```
**Symbols:**

```
ffffffff812f5490-ffffffff812f54fa: bpf_map_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81314290)
Location: kernel/bpf/syscall.c:4141
Inline: False
Direct callers:
  - kernel/bpf/map_iter.c:bpf_map_seq_next
  - kernel/bpf/map_iter.c:bpf_map_seq_start
```
**Symbols:**

```
ffffffff81314290-ffffffff813142fa: bpf_map_get_curr_or_next (STB_GLOBAL)
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
