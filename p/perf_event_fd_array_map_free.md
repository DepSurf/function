# Function: <code>perf_event_fd_array_map_free</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_fd_array_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121d700)
Location: kernel/bpf/arraymap.c:1143
Inline: False
```
**Symbols:**

```
ffffffff8121d700-ffffffff8121d796: perf_event_fd_array_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_fd_array_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81221220)
Location: kernel/bpf/arraymap.c:1185
Inline: False
```
**Symbols:**

```
ffffffff81221220-ffffffff812212b6: perf_event_fd_array_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_fd_array_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81258b40)
Location: kernel/bpf/arraymap.c:1207
Inline: False
```
**Symbols:**

```
ffffffff81258b40-ffffffff81258bd6: perf_event_fd_array_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_fd_array_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812a19e0)
Location: kernel/bpf/arraymap.c:1235
Inline: False
```
**Symbols:**

```
ffffffff812a19e0-ffffffff812a1a89: perf_event_fd_array_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_fd_array_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812fef40)
Location: kernel/bpf/arraymap.c:1241
Inline: False
```
**Symbols:**

```
ffffffff812fef40-ffffffff812fefe9: perf_event_fd_array_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_fd_array_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8132db30)
Location: kernel/bpf/arraymap.c:1266
Inline: False
```
**Symbols:**

```
ffffffff8132db30-ffffffff8132dbd9: perf_event_fd_array_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_fd_array_map_free(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81351ee0)
Location: kernel/bpf/arraymap.c:1235
Inline: False
```
**Symbols:**

```
ffffffff81351ee0-ffffffff81351f8b: perf_event_fd_array_map_free (STB_LOCAL)
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
