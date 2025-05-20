# Function: <code>bpf_opcode_in_insntable</code>

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
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b26b0)
Location: kernel/bpf/core.c:943
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811b26b0-ffffffff811b26c6: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c11f0)
Location: kernel/bpf/core.c:1181
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811c11f0-ffffffff811c1206: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1940)
Location: kernel/bpf/core.c:1272
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811d1940-ffffffff811d1956: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811ddec0)
Location: kernel/bpf/core.c:1272
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811ddec0-ffffffff811dded6: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa970)
Location: kernel/bpf/core.c:1331
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811fa970-ffffffff811fa986: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9bc0)
Location: kernel/bpf/core.c:1328
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff811f9bc0-ffffffff811f9bd6: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fab30)
Location: kernel/bpf/core.c:1336
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff811fab30-ffffffff811fab46: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:1338
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81cb794e-ffffffff81cb796e: bpf_opcode_in_insntable.cold (STB_LOCAL)
ffffffff8122c280-ffffffff8122c29c: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:1635
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81e68a8f-ffffffff81e68ab9: bpf_opcode_in_insntable.cold (STB_LOCAL)
ffffffff8126de70-ffffffff8126de96: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:1609
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff8205f729-ffffffff8205f753: bpf_opcode_in_insntable.cold (STB_LOCAL)
ffffffff812c32e0-ffffffff812c3306: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:1616
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff820de650-ffffffff820de67a: bpf_opcode_in_insntable.cold (STB_LOCAL)
ffffffff812ea110-ffffffff812ea136: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:1663
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff821ba4d6-ffffffff821ba500: bpf_opcode_in_insntable.cold (STB_LOCAL)
ffffffff81308420-ffffffff81308446: bpf_opcode_in_insntable (STB_GLOBAL)
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
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025ee38)
Location: kernel/bpf/core.c:1272
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffff80001025ee38-ffff80001025ee6c: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c04923bc)
Location: kernel/bpf/core.c:1272
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
c04923bc-c04923e4: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000303e10)
Location: kernel/bpf/core.c:1272
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
c000000000303e10-c000000000303e34: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019cfc2)
Location: kernel/bpf/core.c:1272
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffe00019cfc2-ffffffe00019cff2: bpf_opcode_in_insntable (STB_GLOBAL)
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
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d64e0)
Location: kernel/bpf/core.c:1272
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811d64e0-ffffffff811d64f6: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c92a0)
Location: kernel/bpf/core.c:1272
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811c92a0-ffffffff811c92b6: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d42b0)
Location: kernel/bpf/core.c:1272
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811d42b0-ffffffff811d42c6: bpf_opcode_in_insntable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool bpf_opcode_in_insntable(u8 code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e25d0)
Location: kernel/bpf/core.c:1272
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:replace_map_fd_with_map_ptr
```
**Symbols:**

```
ffffffff811e25d0-ffffffff811e25e6: bpf_opcode_in_insntable (STB_GLOBAL)
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
