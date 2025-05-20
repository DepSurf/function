# Function: <code>fd_array_map_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bpf_map *fd_array_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81178370)
Location: kernel/bpf/arraymap.c:160
Inline: False
```
**Symbols:**

```
ffffffff81178370-ffffffff8117838e: fd_array_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bpf_map *fd_array_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81187920)
Location: kernel/bpf/arraymap.c:304
Inline: False
```
**Symbols:**

```
ffffffff81187920-ffffffff8118793e: fd_array_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bpf_map *fd_array_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81195b40)
Location: kernel/bpf/arraymap.c:299
Inline: False
```
**Symbols:**

```
ffffffff81195b40-ffffffff81195b5e: fd_array_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *fd_array_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8119d066)
Location: kernel/bpf/arraymap.c:310
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff8119d020-ffffffff8119d03e: fd_array_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *fd_array_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811acc06)
Location: kernel/bpf/arraymap.c:355
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_alloc
```
**Symbols:**

```
ffffffff811acbc0-ffffffff811acbde: fd_array_map_alloc (STB_LOCAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
