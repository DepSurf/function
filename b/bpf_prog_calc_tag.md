# Function: <code>bpf_prog_calc_tag</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118a650)
Location: kernel/bpf/core.c:149
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8118a650-ffffffff8118a860: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118ed90)
Location: kernel/bpf/core.c:152
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8118ed90-ffffffff8118ef82: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119d200)
Location: kernel/bpf/core.c:148
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8119d200-ffffffff8119d3f2: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1950)
Location: kernel/bpf/core.c:150
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811b1950-ffffffff811b1b51: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c0190)
Location: kernel/bpf/core.c:238
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811c0190-ffffffff811c0391: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d0b30)
Location: kernel/bpf/core.c:263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811d0b30-ffffffff811d0d4f: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dd0c0)
Location: kernel/bpf/core.c:263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811dd0c0-ffffffff811dd2df: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9af0)
Location: kernel/bpf/core.c:263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811f9af0-ffffffff811f9cf3: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8b20)
Location: kernel/bpf/core.c:259
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff811f8b20-ffffffff811f8d23: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9910)
Location: kernel/bpf/core.c:265
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff811f9910-ffffffff811f9b13: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122afc0)
Location: kernel/bpf/core.c:265
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff8122afc0-ffffffff8122b1e4: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126c990)
Location: kernel/bpf/core.c:270
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff8126c990-ffffffff8126cc09: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c1aa0)
Location: kernel/bpf/core.c:278
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff812c1aa0-ffffffff812c1d19: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e8920)
Location: kernel/bpf/core.c:279
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff812e8920-ffffffff812e8bb2: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81306c90)
Location: kernel/bpf/core.c:283
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81306c90-ffffffff81306f22: bpf_prog_calc_tag (STB_GLOBAL)
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
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025dc00)
Location: kernel/bpf/core.c:263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffff80001025dc00-ffff80001025de30: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c04912ec)
Location: kernel/bpf/core.c:263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
c04912ec-c0491530: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003026b0)
Location: kernel/bpf/core.c:263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
c0000000003026b0-c0000000003029b0: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019c0ac)
Location: kernel/bpf/core.c:263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffe00019c0ac-ffffffe00019c2fa: bpf_prog_calc_tag (STB_GLOBAL)
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
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d56e0)
Location: kernel/bpf/core.c:263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811d56e0-ffffffff811d58ff: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c84a0)
Location: kernel/bpf/core.c:263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811c84a0-ffffffff811c86bf: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d34b0)
Location: kernel/bpf/core.c:263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811d34b0-ffffffff811d36cf: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_prog_calc_tag(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e17a0)
Location: kernel/bpf/core.c:263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811e17a0-ffffffff811e19bf: bpf_prog_calc_tag (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
