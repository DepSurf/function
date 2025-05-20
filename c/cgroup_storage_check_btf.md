# Function: <code>cgroup_storage_check_btf</code>

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
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811d7d90)
Location: kernel/bpf/local_storage.c:313
Inline: False
```
**Symbols:**

```
ffffffff811d7d90-ffffffff811d7e05: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ec720)
Location: kernel/bpf/local_storage.c:333
Inline: False
```
**Symbols:**

```
ffffffff811ec720-ffffffff811ec793: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f8e80)
Location: kernel/bpf/local_storage.c:333
Inline: False
```
**Symbols:**

```
ffffffff811f8e80-ffffffff811f8ef3: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121cc80)
Location: kernel/bpf/local_storage.c:333
Inline: False
```
**Symbols:**

```
ffffffff8121cc80-ffffffff8121ccf3: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121fcd0)
Location: kernel/bpf/local_storage.c:350
Inline: True
```
**Symbols:**

```
ffffffff8121fcd0-ffffffff8121fd5e: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81223760)
Location: kernel/bpf/local_storage.c:351
Inline: True
```
**Symbols:**

```
ffffffff81223760-ffffffff812237ee: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8125b590)
Location: kernel/bpf/local_storage.c:357
Inline: True
```
**Symbols:**

```
ffffffff8125b590-ffffffff8125b61e: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812a4e20)
Location: kernel/bpf/local_storage.c:357
Inline: False
```
**Symbols:**

```
ffffffff812a4e20-ffffffff812a4eb7: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81302bc0)
Location: kernel/bpf/local_storage.c:356
Inline: False
```
**Symbols:**

```
ffffffff81302bc0-ffffffff81302c57: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81331660)
Location: kernel/bpf/local_storage.c:356
Inline: False
```
**Symbols:**

```
ffffffff81331660-ffffffff813316f7: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81355c00)
Location: kernel/bpf/local_storage.c:356
Inline: False
```
**Symbols:**

```
ffffffff81355c00-ffffffff81355c97: cgroup_storage_check_btf (STB_LOCAL)
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
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffff80001027e470)
Location: kernel/bpf/local_storage.c:333
Inline: False
```
**Symbols:**

```
ffff80001027e470-ffff80001027e50c: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c04afbb8)
Location: kernel/bpf/local_storage.c:333
Inline: False
```
**Symbols:**

```
c04afbb8-c04afc4c: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c0000000003282d0)
Location: kernel/bpf/local_storage.c:333
Inline: False
```
**Symbols:**

```
c0000000003282d0-c00000000032839c: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffe0001b55b8)
Location: kernel/bpf/local_storage.c:333
Inline: False
```
**Symbols:**

```
ffffffe0001b55b8-ffffffe0001b562a: cgroup_storage_check_btf (STB_LOCAL)
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
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f14a0)
Location: kernel/bpf/local_storage.c:333
Inline: False
```
**Symbols:**

```
ffffffff811f14a0-ffffffff811f1513: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811e41f0)
Location: kernel/bpf/local_storage.c:333
Inline: False
```
**Symbols:**

```
ffffffff811e41f0-ffffffff811e4263: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ef270)
Location: kernel/bpf/local_storage.c:333
Inline: False
```
**Symbols:**

```
ffffffff811ef270-ffffffff811ef2e3: cgroup_storage_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_storage_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811fd740)
Location: kernel/bpf/local_storage.c:333
Inline: False
```
**Symbols:**

```
ffffffff811fd740-ffffffff811fd7b3: cgroup_storage_check_btf (STB_LOCAL)
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
