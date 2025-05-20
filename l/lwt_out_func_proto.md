# Function: <code>lwt_out_func_proto</code>

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
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3420)
Location: net/core/filter.c:4986
Inline: False
Direct callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_in_func_proto
```
**Symbols:**

```
ffffffff818b3420-ffffffff818b348d: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8340)
Location: net/core/filter.c:5630
Inline: False
Direct callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_in_func_proto
```
**Symbols:**

```
ffffffff818d8340-ffffffff818d83c5: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81926280)
Location: net/core/filter.c:6297
Inline: False
Direct callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_in_func_proto
```
**Symbols:**

```
ffffffff81926280-ffffffff81926304: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81958910)
Location: net/core/filter.c:6384
Inline: False
Direct callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_in_func_proto
```
**Symbols:**

```
ffffffff81958910-ffffffff81958994: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a31696)
Location: net/core/filter.c:6595
Inline: True
Inline callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_in_func_proto
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
```
**Symbols:**

```
ffffffff81a2a900-ffffffff81a2a984: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a339d6)
Location: net/core/filter.c:7400
Inline: True
Inline callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_in_func_proto
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
```
**Symbols:**

```
ffffffff81a2b6b0-ffffffff81a2b734: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a1a896)
Location: net/core/filter.c:7522
Inline: True
Inline callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_in_func_proto
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
```
**Symbols:**

```
ffffffff81a12b90-ffffffff81a12c14: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acd586)
Location: net/core/filter.c:7652
Inline: True
Inline callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_in_func_proto
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
```
**Symbols:**

```
ffffffff81ac3730-ffffffff81ac37b4: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4aebc)
Location: net/core/filter.c:8036
Inline: True
Inline callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_in_func_proto
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
```
**Symbols:**

```
ffffffff81c3e6b0-ffffffff81c3e756: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dff66c)
Location: net/core/filter.c:8175
Inline: True
Inline callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_in_func_proto
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
```
**Symbols:**

```
ffffffff81df2a30-ffffffff81df2ad6: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e71cfc)
Location: net/core/filter.c:8327
Inline: True
Inline callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_in_func_proto
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
```
**Symbols:**

```
ffffffff81e649a0-ffffffff81e64a3f: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f3144c)
Location: net/core/filter.c:8418
Inline: True
Inline callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_in_func_proto
Direct callers:
  - net/core/filter.c:lwt_xmit_func_proto
```
**Symbols:**

```
ffffffff81f23b50-ffffffff81f23bef: lwt_out_func_proto (STB_LOCAL)
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
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf9d18)
Location: net/core/filter.c:6384
Inline: False
Direct callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_in_func_proto
```
**Symbols:**

```
ffff800010bf9d18-ffff800010bf9e30: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d13714)
Location: net/core/filter.c:6384
Inline: False
Direct callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_in_func_proto
```
**Symbols:**

```
c0d13714-c0d1382c: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce17c0)
Location: net/core/filter.c:6384
Inline: False
Direct callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_in_func_proto
```
**Symbols:**

```
c000000000ce17c0-c000000000ce191c: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077ba64)
Location: net/core/filter.c:6384
Inline: False
Direct callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_in_func_proto
```
**Symbols:**

```
ffffffe00077ba64-ffffffe00077bb44: lwt_out_func_proto (STB_LOCAL)
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
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f88e0)
Location: net/core/filter.c:6384
Inline: False
Direct callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_in_func_proto
```
**Symbols:**

```
ffffffff818f88e0-ffffffff818f8964: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2710)
Location: net/core/filter.c:6384
Inline: False
Direct callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_in_func_proto
```
**Symbols:**

```
ffffffff818b2710-ffffffff818b2794: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81949910)
Location: net/core/filter.c:6384
Inline: False
Direct callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_in_func_proto
```
**Symbols:**

```
ffffffff81949910-ffffffff81949994: lwt_out_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct bpf_func_proto *lwt_out_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196b220)
Location: net/core/filter.c:6384
Inline: False
Direct callers:
  - net/core/filter.c:lwt_seg6local_func_proto
  - net/core/filter.c:lwt_xmit_func_proto
  - net/core/filter.c:lwt_in_func_proto
```
**Symbols:**

```
ffffffff8196b220-ffffffff8196b2a4: lwt_out_func_proto (STB_LOCAL)
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
