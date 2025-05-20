# Function: <code>cgroup_storage_map_free</code>

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
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811d7e10)
Location: kernel/bpf/local_storage.c:298
Inline: False
```
**Symbols:**

```
ffffffff811d7e10-ffffffff811d7e47: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/local_storage.c (0)
Location: kernel/bpf/local_storage.c:318
Inline: False
```
**Symbols:**

```
ffffffff811ec7a0-ffffffff811ec7e3: cgroup_storage_map_free (STB_LOCAL)
ffffffff811ed3c0-ffffffff811ed3e6: cgroup_storage_map_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f8f00)
Location: kernel/bpf/local_storage.c:318
Inline: False
```
**Symbols:**

```
ffffffff811f8f00-ffffffff811f8f3c: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121cd00)
Location: kernel/bpf/local_storage.c:318
Inline: False
```
**Symbols:**

```
ffffffff8121cd00-ffffffff8121cd3c: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121fd80)
Location: kernel/bpf/local_storage.c:324
Inline: False
```
**Symbols:**

```
ffffffff8121fd80-ffffffff8121fee2: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81223810)
Location: kernel/bpf/local_storage.c:325
Inline: False
```
**Symbols:**

```
ffffffff81223810-ffffffff81223972: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8125b640)
Location: kernel/bpf/local_storage.c:331
Inline: False
```
**Symbols:**

```
ffffffff8125b640-ffffffff8125b7a2: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812a5040)
Location: kernel/bpf/local_storage.c:331
Inline: False
```
**Symbols:**

```
ffffffff812a5040-ffffffff812a51b3: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81302e20)
Location: kernel/bpf/local_storage.c:330
Inline: False
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81325700)
Location: kernel/bpf/bpf_cgrp_storage.c:162
Inline: False
```
**Symbols:**

```
ffffffff81302e20-ffffffff81302f93: cgroup_storage_map_free (STB_LOCAL)
ffffffff81325700-ffffffff81325723: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff813318c0)
Location: kernel/bpf/local_storage.c:330
Inline: False
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81355940)
Location: kernel/bpf/bpf_cgrp_storage.c:155
Inline: False
```
**Symbols:**

```
ffffffff813318c0-ffffffff81331a34: cgroup_storage_map_free (STB_LOCAL)
ffffffff81355940-ffffffff81355963: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81355e60)
Location: kernel/bpf/local_storage.c:330
Inline: False
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8137e470)
Location: kernel/bpf/bpf_cgrp_storage.c:155
Inline: False
```
**Symbols:**

```
ffffffff81355e60-ffffffff81355fd4: cgroup_storage_map_free (STB_LOCAL)
ffffffff8137e470-ffffffff8137e493: cgroup_storage_map_free (STB_LOCAL)
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
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffff80001027e510)
Location: kernel/bpf/local_storage.c:318
Inline: False
```
**Symbols:**

```
ffff80001027e510-ffff80001027e580: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c04afc4c)
Location: kernel/bpf/local_storage.c:318
Inline: False
```
**Symbols:**

```
c04afc4c-c04afcd0: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c0000000003283a0)
Location: kernel/bpf/local_storage.c:318
Inline: False
```
**Symbols:**

```
c0000000003283a0-c0000000003283fc: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffe0001b562a)
Location: kernel/bpf/local_storage.c:318
Inline: False
```
**Symbols:**

```
ffffffe0001b562a-ffffffe0001b5684: cgroup_storage_map_free (STB_LOCAL)
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
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f1520)
Location: kernel/bpf/local_storage.c:318
Inline: False
```
**Symbols:**

```
ffffffff811f1520-ffffffff811f155c: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811e4270)
Location: kernel/bpf/local_storage.c:318
Inline: False
```
**Symbols:**

```
ffffffff811e4270-ffffffff811e42ac: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ef2f0)
Location: kernel/bpf/local_storage.c:318
Inline: False
```
**Symbols:**

```
ffffffff811ef2f0-ffffffff811ef32c: cgroup_storage_map_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_storage_map_free(struct bpf_map *_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811fd7c0)
Location: kernel/bpf/local_storage.c:318
Inline: False
```
**Symbols:**

```
ffffffff811fd7c0-ffffffff811fd7fc: cgroup_storage_map_free (STB_LOCAL)
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
