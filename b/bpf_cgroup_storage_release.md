# Function: <code>bpf_cgroup_storage_release</code>

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
void bpf_cgroup_storage_release(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811d8560)
Location: kernel/bpf/local_storage.c:426
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:free_used_maps
  - kernel/bpf/syscall.c:free_used_maps
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811d8560-ffffffff811d85dc: bpf_cgroup_storage_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/local_storage.c (0)
Location: kernel/bpf/local_storage.c:446
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:free_used_maps
  - kernel/bpf/syscall.c:free_used_maps
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811ed3e6-ffffffff811ed3f9: bpf_cgroup_storage_release.cold (STB_LOCAL)
ffffffff811ed010-ffffffff811ed090: bpf_cgroup_storage_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f9760)
Location: kernel/bpf/local_storage.c:446
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811f9760-ffffffff811f97de: bpf_cgroup_storage_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog_aux *aux, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121d5e0)
Location: kernel/bpf/local_storage.c:446
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_free_used_maps
  - kernel/bpf/core.c:__bpf_free_used_maps
```
**Symbols:**

```
ffffffff8121d5e0-ffffffff8121d653: bpf_cgroup_storage_release (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffff80001027f0a0)
Location: kernel/bpf/local_storage.c:446
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffff80001027f0a0-ffff80001027f198: bpf_cgroup_storage_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c04b0514)
Location: kernel/bpf/local_storage.c:446
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
c04b0514-c04b05a8: bpf_cgroup_storage_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c0000000003291e0)
Location: kernel/bpf/local_storage.c:446
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
c0000000003291e0-c0000000003292c0: bpf_cgroup_storage_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffe0001b5e6a)
Location: kernel/bpf/local_storage.c:446
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffe0001b5e6a-ffffffe0001b5eea: bpf_cgroup_storage_release (STB_GLOBAL)
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
void bpf_cgroup_storage_release(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f1d80)
Location: kernel/bpf/local_storage.c:446
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811f1d80-ffffffff811f1dfe: bpf_cgroup_storage_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811e4ad0)
Location: kernel/bpf/local_storage.c:446
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811e4ad0-ffffffff811e4b4e: bpf_cgroup_storage_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811efb50)
Location: kernel/bpf/local_storage.c:446
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811efb50-ffffffff811efbce: bpf_cgroup_storage_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_cgroup_storage_release(struct bpf_prog *prog, struct bpf_map *_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811fe060)
Location: kernel/bpf/local_storage.c:446
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811fe060-ffffffff811fe0de: bpf_cgroup_storage_release (STB_GLOBAL)
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
