# Function: <code>bpf_prog_create_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81732210)
Location: net/core/filter.c:1093
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81732210-ffffffff817322f1: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179e1e0)
Location: net/core/filter.c:1121
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff8179e1e0-ffffffff8179e2f1: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ccc40)
Location: net/core/filter.c:1123
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff817ccc40-ffffffff817ccd51: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ec070)
Location: net/core/filter.c:1148
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff817ec070-ffffffff817ec184: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81867e60)
Location: net/core/filter.c:1169
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81867e60-ffffffff81867f74: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b7fe0)
Location: net/core/filter.c:1381
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff818b7fe0-ffffffff818b80ea: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818dea40)
Location: net/core/filter.c:1383
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff818dea40-ffffffff818deb4a: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192c950)
Location: net/core/filter.c:1383
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff8192c950-ffffffff8192ca70: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195ec50)
Location: net/core/filter.c:1383
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff8195ec50-ffffffff8195ed70: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a31f60)
Location: net/core/filter.c:1372
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81a31f60-ffffffff81a3216d: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a342a0)
Location: net/core/filter.c:1402
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff81a342a0-ffffffff81a344ad: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a1ace0)
Location: net/core/filter.c:1402
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81a1ace0-ffffffff81a1adfd: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acdc30)
Location: net/core/filter.c:1403
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81acdc30-ffffffff81acdd4d: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4b240)
Location: net/core/filter.c:1404
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81c4b240-ffffffff81c4b36f: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e00510)
Location: net/core/filter.c:1406
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff81e00510-ffffffff81e0063f: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e71fe0)
Location: net/core/filter.c:1406
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff81e71fe0-ffffffff81e7210f: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f31730)
Location: net/core/filter.c:1411
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff81f31730-ffffffff81f3185f: bpf_prog_create_from_user (STB_GLOBAL)
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
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c005d0)
Location: net/core/filter.c:1383
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffff800010c005d0-ffff800010c0070c: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1b528)
Location: net/core/filter.c:1383
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
c0d1b528-c0d1b69c: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ceb1c0)
Location: net/core/filter.c:1383
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
c000000000ceb1c0-c000000000ceb35c: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000781556)
Location: net/core/filter.c:1383
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffe000781556-ffffffe00078164a: bpf_prog_create_from_user (STB_GLOBAL)
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
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fec20)
Location: net/core/filter.c:1383
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff818fec20-ffffffff818fed40: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b8a50)
Location: net/core/filter.c:1383
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff818b8a50-ffffffff818b8b70: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194fc50)
Location: net/core/filter.c:1383
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff8194fc50-ffffffff8194fd70: bpf_prog_create_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_prog_create_from_user(struct bpf_prog **pfp, struct sock_fprog *fprog, bpf_aux_classic_check_t trans, bool save_orig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81971620)
Location: net/core/filter.c:1383
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81971620-ffffffff81971740: bpf_prog_create_from_user (STB_GLOBAL)
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
