# Function: <code>cgroup_storage_map_alloc</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811d7e80)
Location: kernel/bpf/local_storage.c:258
Inline: False
```
**Symbols:**

```
ffffffff811d7e80-ffffffff811d7f5e: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ec820)
Location: kernel/bpf/local_storage.c:271
Inline: False
```
**Symbols:**

```
ffffffff811ec820-ffffffff811ec97a: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f8f70)
Location: kernel/bpf/local_storage.c:271
Inline: False
```
**Symbols:**

```
ffffffff811f8f70-ffffffff811f90ca: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121cd70)
Location: kernel/bpf/local_storage.c:271
Inline: False
```
**Symbols:**

```
ffffffff8121cd70-ffffffff8121ceca: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121fbb0)
Location: kernel/bpf/local_storage.c:286
Inline: False
```
**Symbols:**

```
ffffffff8121fbb0-ffffffff8121fc9d: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81223630)
Location: kernel/bpf/local_storage.c:287
Inline: False
```
**Symbols:**

```
ffffffff81223630-ffffffff81223725: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8125b450)
Location: kernel/bpf/local_storage.c:285
Inline: False
```
**Symbols:**

```
ffffffff8125b450-ffffffff8125b554: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812a4ef0)
Location: kernel/bpf/local_storage.c:285
Inline: False
```
**Symbols:**

```
ffffffff812a4ef0-ffffffff812a4ff0: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81302c70)
Location: kernel/bpf/local_storage.c:285
Inline: False
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81325740)
Location: kernel/bpf/bpf_cgrp_storage.c:157
Inline: False
```
**Symbols:**

```
ffffffff81302c70-ffffffff81302d60: cgroup_storage_map_alloc (STB_LOCAL)
ffffffff81325740-ffffffff8132575f: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81331710)
Location: kernel/bpf/local_storage.c:285
Inline: False
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81355980)
Location: kernel/bpf/bpf_cgrp_storage.c:150
Inline: False
```
**Symbols:**

```
ffffffff81331710-ffffffff813317f8: cgroup_storage_map_alloc (STB_LOCAL)
ffffffff81355980-ffffffff813559a6: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81355cb0)
Location: kernel/bpf/local_storage.c:285
Inline: False
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8137e4b0)
Location: kernel/bpf/bpf_cgrp_storage.c:150
Inline: False
```
**Symbols:**

```
ffffffff81355cb0-ffffffff81355d98: cgroup_storage_map_alloc (STB_LOCAL)
ffffffff8137e4b0-ffffffff8137e4d6: cgroup_storage_map_alloc (STB_LOCAL)
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
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffff80001027e5b8)
Location: kernel/bpf/local_storage.c:271
Inline: False
```
**Symbols:**

```
ffff80001027e5b8-ffff80001027e6e4: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c04b0018)
Location: kernel/bpf/local_storage.c:271
Inline: True
```
**Symbols:**

```
c04b0018-c04b0138: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c000000000328460)
Location: kernel/bpf/local_storage.c:271
Inline: False
```
**Symbols:**

```
c000000000328460-c00000000032862c: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffe0001b5a8a)
Location: kernel/bpf/local_storage.c:271
Inline: True
```
**Symbols:**

```
ffffffe0001b5a8a-ffffffe0001b5b58: cgroup_storage_map_alloc (STB_LOCAL)
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
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f1590)
Location: kernel/bpf/local_storage.c:271
Inline: False
```
**Symbols:**

```
ffffffff811f1590-ffffffff811f16ea: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811e42e0)
Location: kernel/bpf/local_storage.c:271
Inline: False
```
**Symbols:**

```
ffffffff811e42e0-ffffffff811e443a: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ef360)
Location: kernel/bpf/local_storage.c:271
Inline: False
```
**Symbols:**

```
ffffffff811ef360-ffffffff811ef4ba: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_map *cgroup_storage_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811fd830)
Location: kernel/bpf/local_storage.c:271
Inline: False
```
**Symbols:**

```
ffffffff811fd830-ffffffff811fd98a: cgroup_storage_map_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
