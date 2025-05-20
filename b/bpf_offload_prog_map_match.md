# Function: <code>bpf_offload_prog_map_match</code>

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
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811e0320)
Location: kernel/bpf/offload.c:543
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811e0320-ffffffff811e0380: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f5ee0)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811f5ee0-ffffffff811f5f43: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81202ef0)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff81202ef0-ffffffff81202f53: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8122a4d0)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
**Symbols:**

```
ffffffff8122a4d0-ffffffff8122a52f: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81232060)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
**Symbols:**

```
ffffffff81232060-ffffffff812320bf: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812361e0)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
**Symbols:**

```
ffffffff812361e0-ffffffff8123623f: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81270430)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
**Symbols:**

```
ffffffff81270430-ffffffff8127048f: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812bf520)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
**Symbols:**

```
ffffffff812bf520-ffffffff812bf58f: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81322c40)
Location: kernel/bpf/offload.c:576
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
**Symbols:**

```
ffffffff81322c40-ffffffff81322caf: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81352cd0)
Location: kernel/bpf/offload.c:733
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
**Symbols:**

```
ffffffff81352cd0-ffffffff81352d3f: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8137a1b0)
Location: kernel/bpf/offload.c:743
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_prog_compatibility
```
**Symbols:**

```
ffffffff8137a1b0-ffffffff8137a21f: bpf_offload_prog_map_match (STB_GLOBAL)
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
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffff80001028b4c8)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffff80001028b4c8-ffff80001028b554: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04bac9c)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
c04bac9c-c04bad14: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c000000000337430)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
c000000000337430-c0000000003374e4: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001bf1a6)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffe0001bf1a6-ffffffe0001bf222: bpf_offload_prog_map_match (STB_GLOBAL)
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
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811fb510)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811fb510-ffffffff811fb573: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811ee260)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811ee260-ffffffff811ee2c3: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f92e0)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811f92e0-ffffffff811f9343: bpf_offload_prog_map_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool bpf_offload_prog_map_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81207d80)
Location: kernel/bpf/offload.c:579
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff81207d80-ffffffff81207de3: bpf_offload_prog_map_match (STB_GLOBAL)
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
