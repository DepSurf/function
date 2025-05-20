# Function: <code>bpf_cgroup_storage_assign</code>

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
int bpf_cgroup_storage_assign(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811d84d0)
Location: kernel/bpf/local_storage.c:403
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811d84d0-ffffffff811d8559: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ecf80)
Location: kernel/bpf/local_storage.c:423
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811ecf80-ffffffff811ed00c: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f96d0)
Location: kernel/bpf/local_storage.c:423
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811f96d0-ffffffff811f975c: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog_aux *aux, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121d550)
Location: kernel/bpf/local_storage.c:423
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff8121d550-ffffffff8121d5d4: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog_aux *aux, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81220470)
Location: kernel/bpf/local_storage.c:457
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81220470-ffffffff812204a7: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog_aux *aux, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81223f00)
Location: kernel/bpf/local_storage.c:458
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81223f00-ffffffff81223f37: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog_aux *aux, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8125be00)
Location: kernel/bpf/local_storage.c:464
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff8125be00-ffffffff8125be37: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog_aux *aux, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812a5920)
Location: kernel/bpf/local_storage.c:464
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff812a5920-ffffffff812a596b: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog_aux *aux, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff813038a0)
Location: kernel/bpf/local_storage.c:463
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff813038a0-ffffffff813038eb: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog_aux *aux, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff813322d0)
Location: kernel/bpf/local_storage.c:470
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff813322d0-ffffffff8133231b: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog_aux *aux, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81356880)
Location: kernel/bpf/local_storage.c:470
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81356880-ffffffff813568cb: bpf_cgroup_storage_assign (STB_GLOBAL)
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
int bpf_cgroup_storage_assign(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffff80001027efa0)
Location: kernel/bpf/local_storage.c:423
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffff80001027efa0-ffff80001027f09c: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c04b0488)
Location: kernel/bpf/local_storage.c:423
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
c04b0488-c04b0514: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c000000000329100)
Location: kernel/bpf/local_storage.c:423
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
c000000000329100-c0000000003291d8: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffe0001b5ddc)
Location: kernel/bpf/local_storage.c:423
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffe0001b5ddc-ffffffe0001b5e6a: bpf_cgroup_storage_assign (STB_GLOBAL)
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
int bpf_cgroup_storage_assign(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f1cf0)
Location: kernel/bpf/local_storage.c:423
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811f1cf0-ffffffff811f1d7c: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811e4a40)
Location: kernel/bpf/local_storage.c:423
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811e4a40-ffffffff811e4acc: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811efac0)
Location: kernel/bpf/local_storage.c:423
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811efac0-ffffffff811efb4c: bpf_cgroup_storage_assign (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_cgroup_storage_assign(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811fdfd0)
Location: kernel/bpf/local_storage.c:423
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811fdfd0-ffffffff811fe05c: bpf_cgroup_storage_assign (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog_aux *aux</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_prog *prog</code>
</li>
</ul>
</details>
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
