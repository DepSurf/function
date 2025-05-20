# Function: <code>perf_event_fd_array_release</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811875f0)
Location: kernel/bpf/arraymap.c:502
Inline: False
```
**Symbols:**

```
ffffffff811875f0-ffffffff8118765c: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811955b0)
Location: kernel/bpf/arraymap.c:498
Inline: False
```
**Symbols:**

```
ffffffff811955b0-ffffffff8119561c: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8119c960)
Location: kernel/bpf/arraymap.c:509
Inline: False
```
**Symbols:**

```
ffffffff8119c960-ffffffff8119c9cd: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ac2c0)
Location: kernel/bpf/arraymap.c:554
Inline: False
```
**Symbols:**

```
ffffffff811ac2c0-ffffffff811ac338: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811c3830)
Location: kernel/bpf/arraymap.c:611
Inline: False
```
**Symbols:**

```
ffffffff811c3830-ffffffff811c38a9: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811d5310)
Location: kernel/bpf/arraymap.c:654
Inline: False
```
**Symbols:**

```
ffffffff811d5310-ffffffff811d5389: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e9ad0)
Location: kernel/bpf/arraymap.c:702
Inline: False
```
**Symbols:**

```
ffffffff811e9ad0-ffffffff811e9b49: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811f6230)
Location: kernel/bpf/arraymap.c:702
Inline: False
```
**Symbols:**

```
ffffffff811f6230-ffffffff811f62a9: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81219f30)
Location: kernel/bpf/arraymap.c:948
Inline: False
```
**Symbols:**

```
ffffffff81219f30-ffffffff81219fbf: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121d070)
Location: kernel/bpf/arraymap.c:1124
Inline: True
```
**Symbols:**

```
ffffffff8121d070-ffffffff8121d10a: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81220b80)
Location: kernel/bpf/arraymap.c:1166
Inline: True
```
**Symbols:**

```
ffffffff81220b80-ffffffff81220c1a: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81258540)
Location: kernel/bpf/arraymap.c:1188
Inline: True
```
**Symbols:**

```
ffffffff81258540-ffffffff812585da: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812a12f0)
Location: kernel/bpf/arraymap.c:1216
Inline: True
```
**Symbols:**

```
ffffffff812a12f0-ffffffff812a13a5: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812fe0d0)
Location: kernel/bpf/arraymap.c:1222
Inline: True
```
**Symbols:**

```
ffffffff812fe0d0-ffffffff812fe185: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8132cce0)
Location: kernel/bpf/arraymap.c:1247
Inline: True
```
**Symbols:**

```
ffffffff8132cce0-ffffffff8132cd95: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81351030)
Location: kernel/bpf/arraymap.c:1216
Inline: True
```
**Symbols:**

```
ffffffff81351030-ffffffff813510f0: perf_event_fd_array_release (STB_LOCAL)
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
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffff80001027b778)
Location: kernel/bpf/arraymap.c:702
Inline: False
```
**Symbols:**

```
ffff80001027b778-ffff80001027b838: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c04ad7a0)
Location: kernel/bpf/arraymap.c:702
Inline: False
```
**Symbols:**

```
c04ad7a0-c04ad854: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c000000000323b20)
Location: kernel/bpf/arraymap.c:702
Inline: False
```
**Symbols:**

```
c000000000323b20-c000000000323c14: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffe0001b266a)
Location: kernel/bpf/arraymap.c:702
Inline: False
```
**Symbols:**

```
ffffffe0001b266a-ffffffe0001b26f2: perf_event_fd_array_release (STB_LOCAL)
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
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ee850)
Location: kernel/bpf/arraymap.c:702
Inline: False
```
**Symbols:**

```
ffffffff811ee850-ffffffff811ee8c9: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e15e0)
Location: kernel/bpf/arraymap.c:702
Inline: False
```
**Symbols:**

```
ffffffff811e15e0-ffffffff811e1659: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ec620)
Location: kernel/bpf/arraymap.c:702
Inline: False
```
**Symbols:**

```
ffffffff811ec620-ffffffff811ec699: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_event_fd_array_release(struct bpf_map *map, struct file *map_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811fab30)
Location: kernel/bpf/arraymap.c:702
Inline: False
```
**Symbols:**

```
ffffffff811fab30-ffffffff811fabb5: perf_event_fd_array_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
