# Function: <code>bpf_map_get</code>

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
struct bpf_map *bpf_map_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fefa0)
Location: kernel/bpf/syscall.c:924
Inline: False
```
**Symbols:**

```
ffffffff811fefa0-ffffffff811ff012: bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe2e0)
Location: kernel/bpf/syscall.c:937
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
```
**Symbols:**

```
ffffffff811fe2e0-ffffffff811fe352: bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fed70)
Location: kernel/bpf/syscall.c:938
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
```
**Symbols:**

```
ffffffff811fed70-ffffffff811fede2: bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812309c0)
Location: kernel/bpf/syscall.c:965
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
```
**Symbols:**

```
ffffffff812309c0-ffffffff81230a32: bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81270d00)
Location: kernel/bpf/syscall.c:1199
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
```
**Symbols:**

```
ffffffff81270d00-ffffffff81270d8d: bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c6d30)
Location: kernel/bpf/syscall.c:1242
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
```
**Symbols:**

```
ffffffff812c6d30-ffffffff812c6dbd: bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812eded0)
Location: kernel/bpf/syscall.c:1317
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create
```
**Symbols:**

```
ffffffff812eded0-ffffffff812edf60: bpf_map_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_map *bpf_map_get(u32 ufd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130cc70)
Location: kernel/bpf/syscall.c:1348
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create
```
**Symbols:**

```
ffffffff8130cc70-ffffffff8130cd00: bpf_map_get (STB_GLOBAL)
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
