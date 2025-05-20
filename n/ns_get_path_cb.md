# Function: <code>ns_get_path_cb</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812d5e00)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffffffff812d5e00-ffffffff812d5e58: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff812eb1d0)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffffffff812eb1d0-ffffffff812eb228: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81309c40)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffffffff81309c40-ffffffff81309c90: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8131ccb0)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffffffff8131ccb0-ffffffff8131cd00: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81356a05)
Location: fs/nsfs.c:109
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
**Symbols:**

```
ffffffff813569b0-ffffffff813569f2: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813633be)
Location: fs/nsfs.c:109
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
**Symbols:**

```
ffffffff81363360-ffffffff813633a2: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81369e4e)
Location: fs/nsfs.c:109
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
**Symbols:**

```
ffffffff81369df0-ffffffff81369e32: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813b8b3e)
Location: fs/nsfs.c:109
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
**Symbols:**

```
ffffffff813b8ae0-ffffffff813b8b22: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8143e49e)
Location: fs/nsfs.c:109
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
**Symbols:**

```
ffffffff8143e440-ffffffff8143e48d: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff814ccf1e)
Location: fs/nsfs.c:109
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
**Symbols:**

```
ffffffff814cceb0-ffffffff814ccefd: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8150315e)
Location: fs/nsfs.c:110
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
**Symbols:**

```
ffffffff815030f0-ffffffff8150313d: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81537d7e)
Location: fs/nsfs.c:107
Inline: True
Inline callers:
  - fs/nsfs.c:ns_get_path
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
```
**Symbols:**

```
ffffffff81537d10-ffffffff81537d5d: ns_get_path_cb (STB_GLOBAL)
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
void *ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffff8000103d4a80)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffff8000103d4a80-ffff8000103d4ae4: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (c05ae960)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
c05ae960-c05ae9b0: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (c0000000004d77b0)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
c0000000004d77b0-c0000000004d7858: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffe00028ed94)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffffffe00028ed94-ffffffe00028edea: ns_get_path_cb (STB_GLOBAL)
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
void *ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81315290)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffffffff81315290-ffffffff813152e0: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81305e80)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffffffff81305e80-ffffffff81305ed0: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81313080)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffffffff81313080-ffffffff813130d0: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *ns_get_path_cb(struct path *path, ns_get_path_helper_t *ns_get_cb, void *private_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813248d0)
Location: fs/nsfs.c:106
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_info_fill
  - kernel/bpf/offload.c:bpf_prog_offload_info_fill
  - fs/nsfs.c:ns_get_path
```
**Symbols:**

```
ffffffff813248d0-ffffffff81324920: ns_get_path_cb (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>int</code>
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
