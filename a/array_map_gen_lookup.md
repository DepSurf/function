# Function: <code>array_map_gen_lookup</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8119ca50)
Location: kernel/bpf/arraymap.c:121
Inline: False
```
**Symbols:**

```
ffffffff8119ca50-ffffffff8119cad4: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ac3e0)
Location: kernel/bpf/arraymap.c:159
Inline: False
```
**Symbols:**

```
ffffffff811ac3e0-ffffffff811ac495: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811c3a20)
Location: kernel/bpf/arraymap.c:164
Inline: False
```
**Symbols:**

```
ffffffff811c3a20-ffffffff811c3ad5: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811d55c0)
Location: kernel/bpf/arraymap.c:164
Inline: False
```
**Symbols:**

```
ffffffff811d55c0-ffffffff811d5675: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e9de0)
Location: kernel/bpf/arraymap.c:185
Inline: False
```
**Symbols:**

```
ffffffff811e9de0-ffffffff811e9e95: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811f6540)
Location: kernel/bpf/arraymap.c:185
Inline: False
```
**Symbols:**

```
ffffffff811f6540-ffffffff811f65f5: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81219b30)
Location: kernel/bpf/arraymap.c:211
Inline: False
```
**Symbols:**

```
ffffffff81219b30-ffffffff81219be5: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121c340)
Location: kernel/bpf/arraymap.c:201
Inline: False
```
**Symbols:**

```
ffffffff8121c340-ffffffff8121c40b: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121fd40)
Location: kernel/bpf/arraymap.c:201
Inline: False
```
**Symbols:**

```
ffffffff8121fd40-ffffffff8121fe18: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:201
Inline: False
```
**Symbols:**

```
ffffffff81258090-ffffffff8125818d: array_map_gen_lookup (STB_LOCAL)
ffffffff81cb91f5-ffffffff81cb920a: array_map_gen_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:207
Inline: False
```
**Symbols:**

```
ffffffff812a0cf0-ffffffff812a0e16: array_map_gen_lookup (STB_LOCAL)
ffffffff81e6a4d3-ffffffff81e6a4e8: array_map_gen_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:205
Inline: False
```
**Symbols:**

```
ffffffff812fdac0-ffffffff812fdbd7: array_map_gen_lookup (STB_LOCAL)
ffffffff82061626-ffffffff8206163b: array_map_gen_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:205
Inline: False
```
**Symbols:**

```
ffffffff8132c6d0-ffffffff8132c7e7: array_map_gen_lookup (STB_LOCAL)
ffffffff820e0bc1-ffffffff820e0bd6: array_map_gen_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:205
Inline: False
```
**Symbols:**

```
ffffffff81350c10-ffffffff81350d27: array_map_gen_lookup (STB_LOCAL)
ffffffff821bd37f-ffffffff821bd394: array_map_gen_lookup.cold (STB_LOCAL)
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
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffff80001027ac60)
Location: kernel/bpf/arraymap.c:185
Inline: False
```
**Symbols:**

```
ffff80001027ac60-ffff80001027ad40: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c04acc60)
Location: kernel/bpf/arraymap.c:185
Inline: False
```
**Symbols:**

```
c04acc60-c04acd6c: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c000000000324090)
Location: kernel/bpf/arraymap.c:185
Inline: False
```
**Symbols:**

```
c000000000324090-c0000000003241ac: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffe0001b33aa)
Location: kernel/bpf/arraymap.c:185
Inline: False
```
**Symbols:**

```
ffffffe0001b33aa-ffffffe0001b34ca: array_map_gen_lookup (STB_LOCAL)
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
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811eeb60)
Location: kernel/bpf/arraymap.c:185
Inline: False
```
**Symbols:**

```
ffffffff811eeb60-ffffffff811eec15: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e18f0)
Location: kernel/bpf/arraymap.c:185
Inline: False
```
**Symbols:**

```
ffffffff811e18f0-ffffffff811e19a5: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ec930)
Location: kernel/bpf/arraymap.c:185
Inline: False
```
**Symbols:**

```
ffffffff811ec930-ffffffff811ec9e5: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 array_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811fadd0)
Location: kernel/bpf/arraymap.c:185
Inline: False
```
**Symbols:**

```
ffffffff811fadd0-ffffffff811fae85: array_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>u32</code> ➡️ <code>int</code>
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
