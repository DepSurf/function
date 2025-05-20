# Function: <code>bpf_prog_free_id</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191ab4)
Location: kernel/bpf/syscall.c:748
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119ea29)
Location: kernel/bpf/syscall.c:908
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3a70)
Location: kernel/bpf/syscall.c:1002
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff811b3a70-ffffffff811b3adc: bpf_prog_free_id.part.32 (STB_LOCAL)
ffffffff811b5ae0-ffffffff811b5b00: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c1f30)
Location: kernel/bpf/syscall.c:1185
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff811c1f30-ffffffff811c1f9c: bpf_prog_free_id.part.31 (STB_LOCAL)
ffffffff811c3700-ffffffff811c3720: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d26a0)
Location: kernel/bpf/syscall.c:1291
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff811d26a0-ffffffff811d270c: bpf_prog_free_id.part.0 (STB_LOCAL)
ffffffff811d4e50-ffffffff811d4e70: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811dec60)
Location: kernel/bpf/syscall.c:1304
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff811dec60-ffffffff811deccc: bpf_prog_free_id.part.0 (STB_LOCAL)
ffffffff811e1560-ffffffff811e1580: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ffcc0)
Location: kernel/bpf/syscall.c:1690
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff811ffcc0-ffffffff811ffd39: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fefe0)
Location: kernel/bpf/syscall.c:1658
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff811fefe0-ffffffff811ff059: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ffa70)
Location: kernel/bpf/syscall.c:1659
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff811ffa70-ffffffff811ffae9: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81231710)
Location: kernel/bpf/syscall.c:1727
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff81231710-ffffffff8123178f: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81274960)
Location: kernel/bpf/syscall.c:1971
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff81274960-ffffffff81274a01: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c6719)
Location: kernel/bpf/syscall.c:2004
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_put_deferred
  - kernel/bpf/syscall.c:bpf_prog_put_deferred
```
**Symbols:**

```
ffffffff812cbb90-ffffffff812cbc00: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812eda29)
Location: kernel/bpf/syscall.c:2082
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_put_deferred
  - kernel/bpf/syscall.c:bpf_prog_put_deferred
```
**Symbols:**

```
ffffffff812f3500-ffffffff812f3570: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130c5d9)
Location: kernel/bpf/syscall.c:2122
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_put_deferred
  - kernel/bpf/syscall.c:bpf_prog_put_deferred
```
**Symbols:**

```
ffffffff81312390-ffffffff81312400: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff8000102641e0)
Location: kernel/bpf/syscall.c:1304
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffff8000102641e0-ffff8000102642f0: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (c049340c)
Location: kernel/bpf/syscall.c:1304
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
c049340c-c0493488: bpf_prog_free_id.part.0 (STB_LOCAL)
c04967b0-c04967dc: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (c000000000304e60)
Location: kernel/bpf/syscall.c:1304
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
c000000000304e60-c000000000304f2c: bpf_prog_free_id.part.0 (STB_LOCAL)
c000000000309090-c0000000003090b4: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019dce6)
Location: kernel/bpf/syscall.c:1304
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffe00019dce6-ffffffe00019dd74: bpf_prog_free_id.part.0 (STB_LOCAL)
ffffffe0001a02d8-ffffffe0001a0310: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d7280)
Location: kernel/bpf/syscall.c:1304
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff811d7280-ffffffff811d72ec: bpf_prog_free_id.part.0 (STB_LOCAL)
ffffffff811d9b80-ffffffff811d9ba0: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ca040)
Location: kernel/bpf/syscall.c:1304
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff811ca040-ffffffff811ca0ac: bpf_prog_free_id.part.0 (STB_LOCAL)
ffffffff811cc940-ffffffff811cc960: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d5050)
Location: kernel/bpf/syscall.c:1304
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff811d5050-ffffffff811d50bc: bpf_prog_free_id.part.0 (STB_LOCAL)
ffffffff811d7950-ffffffff811d7970: bpf_prog_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_prog_free_id(struct bpf_prog *prog, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e3380)
Location: kernel/bpf/syscall.c:1304
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_prog_offload_destroy
```
**Symbols:**

```
ffffffff811e3380-ffffffff811e33ec: bpf_prog_free_id.part.0 (STB_LOCAL)
ffffffff811e5cf0-ffffffff811e5d10: bpf_prog_free_id (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool do_idr_lock</code>
</li>
</ul>
</details>
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
