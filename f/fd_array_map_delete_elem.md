# Function: <code>fd_array_map_delete_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81178050)
Location: kernel/bpf/arraymap.c:212
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:bpf_fd_array_map_clear
```
**Symbols:**

```
ffffffff81178050-ffffffff81178086: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81187a83)
Location: kernel/bpf/arraymap.c:356
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffff811875b0-ffffffff811875e6: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81195883)
Location: kernel/bpf/arraymap.c:352
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffff81195570-ffffffff811955a6: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8119cd5a)
Location: kernel/bpf/arraymap.c:383
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffff8119c900-ffffffff8119c936: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ac7fd)
Location: kernel/bpf/arraymap.c:428
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffff811ac260-ffffffff811ac29f: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811c3de0)
Location: kernel/bpf/arraymap.c:483
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffff811c3770-ffffffff811c37af: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811d5aa0)
Location: kernel/bpf/arraymap.c:502
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffff811d5250-ffffffff811d528f: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ea430)
Location: kernel/bpf/arraymap.c:550
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffff811e9a10-ffffffff811e9a4f: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811f6b90)
Location: kernel/bpf/arraymap.c:550
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffff811f6170-ffffffff811f61af: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81219e70)
Location: kernel/bpf/arraymap.c:610
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
**Symbols:**

```
ffffffff81219e70-ffffffff81219f22: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121cbd0)
Location: kernel/bpf/arraymap.c:749
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
**Symbols:**

```
ffffffff8121cbd0-ffffffff8121cc82: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812206f0)
Location: kernel/bpf/arraymap.c:791
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
**Symbols:**

```
ffffffff812206f0-ffffffff812207a2: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81257ef0)
Location: kernel/bpf/arraymap.c:812
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
**Symbols:**

```
ffffffff81257ef0-ffffffff81257fa2: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812a0b20)
Location: kernel/bpf/arraymap.c:844
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
**Symbols:**

```
ffffffff812a0b20-ffffffff812a0bde: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812fd630)
Location: kernel/bpf/arraymap.c:850
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
**Symbols:**

```
ffffffff812fd630-ffffffff812fd6ee: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8132c270)
Location: kernel/bpf/arraymap.c:874
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_map_free
  - kernel/bpf/arraymap.c:prog_array_map_clear_deferred
```
**Symbols:**

```
ffffffff8132c270-ffffffff8132c336: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81350860)
Location: kernel/bpf/arraymap.c:900
Inline: False
```
**Symbols:**

```
ffffffff81350860-ffffffff8135087f: fd_array_map_delete_elem (STB_LOCAL)
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
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffff80001027b600)
Location: kernel/bpf/arraymap.c:550
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
  - kernel/bpf/arraymap.c:bpf_fd_array_map_clear
```
**Symbols:**

```
ffff80001027b600-ffff80001027b67c: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c04ad63c)
Location: kernel/bpf/arraymap.c:550
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
  - kernel/bpf/arraymap.c:bpf_fd_array_map_clear
```
**Symbols:**

```
c04ad63c-c04ad6b8: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c0000000003239a0)
Location: kernel/bpf/arraymap.c:550
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
  - kernel/bpf/arraymap.c:bpf_fd_array_map_clear
```
**Symbols:**

```
c0000000003239a0-c000000000323a48: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffe0001b3054)
Location: kernel/bpf/arraymap.c:550
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffe0001b2596-ffffffe0001b25ec: fd_array_map_delete_elem (STB_LOCAL)
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
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ef1b0)
Location: kernel/bpf/arraymap.c:550
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffff811ee790-ffffffff811ee7cf: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e1f40)
Location: kernel/bpf/arraymap.c:550
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffff811e1520-ffffffff811e155f: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ecf80)
Location: kernel/bpf/arraymap.c:550
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffff811ec560-ffffffff811ec59f: fd_array_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fd_array_map_delete_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811fb420)
Location: kernel/bpf/arraymap.c:550
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_of_map_free
  - kernel/bpf/arraymap.c:cgroup_fd_array_free
  - kernel/bpf/arraymap.c:perf_event_fd_array_release
```
**Symbols:**

```
ffffffff811fa9d0-ffffffff811faa0f: fd_array_map_delete_elem (STB_LOCAL)
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
