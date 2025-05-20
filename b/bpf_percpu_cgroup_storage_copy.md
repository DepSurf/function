# Function: <code>bpf_percpu_cgroup_storage_copy</code>

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
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *_key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811d8340)
Location: kernel/bpf/local_storage.c:157
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d8340-ffffffff811d83fb: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *_key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ecde0)
Location: kernel/bpf/local_storage.c:170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811ecde0-ffffffff811ece9b: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *_key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f9530)
Location: kernel/bpf/local_storage.c:170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811f9530-ffffffff811f95eb: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *_key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121d3c0)
Location: kernel/bpf/local_storage.c:170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8121d3c0-ffffffff8121d47b: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812202c0)
Location: kernel/bpf/local_storage.c:183
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff812202c0-ffffffff81220385: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81223d50)
Location: kernel/bpf/local_storage.c:184
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81223d50-ffffffff81223e1b: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8125bbe0)
Location: kernel/bpf/local_storage.c:182
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8125bbe0-ffffffff8125bcdd: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812a56a0)
Location: kernel/bpf/local_storage.c:182
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff812a56a0-ffffffff812a57cc: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff813035f0)
Location: kernel/bpf/local_storage.c:182
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff813035f0-ffffffff81303725: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81332020)
Location: kernel/bpf/local_storage.c:182
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81332020-ffffffff81332155: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff813565d0)
Location: kernel/bpf/local_storage.c:182
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff813565d0-ffffffff81356705: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *_key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffff80001027ed48)
Location: kernel/bpf/local_storage.c:170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffff80001027ed48-ffff80001027ee68: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *_key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c04b02c8)
Location: kernel/bpf/local_storage.c:170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
c04b02c8-c04b0398: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *_key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c000000000328df0)
Location: kernel/bpf/local_storage.c:170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
c000000000328df0-c000000000328f58: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *_key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffe0001b5be0)
Location: kernel/bpf/local_storage.c:170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffe0001b5be0-ffffffe0001b5cd8: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
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
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *_key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f1b50)
Location: kernel/bpf/local_storage.c:170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811f1b50-ffffffff811f1c0b: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *_key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811e48a0)
Location: kernel/bpf/local_storage.c:170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811e48a0-ffffffff811e495b: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *_key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ef920)
Location: kernel/bpf/local_storage.c:170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811ef920-ffffffff811ef9db: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_copy(struct bpf_map *_map, void *_key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811fde00)
Location: kernel/bpf/local_storage.c:170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811fde00-ffffffff811fded3: bpf_percpu_cgroup_storage_copy (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *key</code>
</li>
<li>
<b>Param removed. </b>
<code>void *_key</code>
</li>
</ul>
</details>
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
