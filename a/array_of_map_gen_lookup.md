# Function: <code>array_of_map_gen_lookup</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ac4a0)
Location: kernel/bpf/arraymap.c:651
Inline: False
```
**Symbols:**

```
ffffffff811ac4a0-ffffffff811ac569: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811c3ae0)
Location: kernel/bpf/arraymap.c:710
Inline: False
```
**Symbols:**

```
ffffffff811c3ae0-ffffffff811c3ba9: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811d5680)
Location: kernel/bpf/arraymap.c:755
Inline: False
```
**Symbols:**

```
ffffffff811d5680-ffffffff811d5749: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e9ea0)
Location: kernel/bpf/arraymap.c:803
Inline: False
```
**Symbols:**

```
ffffffff811e9ea0-ffffffff811e9f69: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811f6600)
Location: kernel/bpf/arraymap.c:803
Inline: False
```
**Symbols:**

```
ffffffff811f6600-ffffffff811f66c9: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81219bf0)
Location: kernel/bpf/arraymap.c:1049
Inline: False
```
**Symbols:**

```
ffffffff81219bf0-ffffffff81219cb9: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121c410)
Location: kernel/bpf/arraymap.c:1243
Inline: False
```
**Symbols:**

```
ffffffff8121c410-ffffffff8121c4d9: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121fe20)
Location: kernel/bpf/arraymap.c:1285
Inline: False
```
**Symbols:**

```
ffffffff8121fe20-ffffffff8121fef6: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:1307
Inline: False
```
**Symbols:**

```
ffffffff81258190-ffffffff8125828d: array_of_map_gen_lookup (STB_LOCAL)
ffffffff81cb920a-ffffffff81cb921f: array_of_map_gen_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:1331
Inline: False
```
**Symbols:**

```
ffffffff812a0e20-ffffffff812a0f34: array_of_map_gen_lookup (STB_LOCAL)
ffffffff81e6a4e8-ffffffff81e6a4fd: array_of_map_gen_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:1337
Inline: False
```
**Symbols:**

```
ffffffff812fdbf0-ffffffff812fdcf4: array_of_map_gen_lookup (STB_LOCAL)
ffffffff8206163b-ffffffff82061650: array_of_map_gen_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:1364
Inline: False
```
**Symbols:**

```
ffffffff8132c800-ffffffff8132c904: array_of_map_gen_lookup (STB_LOCAL)
ffffffff820e0bd6-ffffffff820e0beb: array_of_map_gen_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:1333
Inline: False
```
**Symbols:**

```
ffffffff81350d40-ffffffff81350e44: array_of_map_gen_lookup (STB_LOCAL)
ffffffff821bd394-ffffffff821bd3a9: array_of_map_gen_lookup.cold (STB_LOCAL)
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
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffff80001027ad40)
Location: kernel/bpf/arraymap.c:803
Inline: False
```
**Symbols:**

```
ffff80001027ad40-ffff80001027ae30: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c04acd6c)
Location: kernel/bpf/arraymap.c:803
Inline: False
```
**Symbols:**

```
c04acd6c-c04ace94: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c0000000003241b0)
Location: kernel/bpf/arraymap.c:803
Inline: False
```
**Symbols:**

```
c0000000003241b0-c0000000003242fc: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffe0001b2a2c)
Location: kernel/bpf/arraymap.c:803
Inline: False
```
**Symbols:**

```
ffffffe0001b2a2c-ffffffe0001b2b60: array_of_map_gen_lookup (STB_LOCAL)
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
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811eec20)
Location: kernel/bpf/arraymap.c:803
Inline: False
```
**Symbols:**

```
ffffffff811eec20-ffffffff811eece9: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e19b0)
Location: kernel/bpf/arraymap.c:803
Inline: False
```
**Symbols:**

```
ffffffff811e19b0-ffffffff811e1a79: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ec9f0)
Location: kernel/bpf/arraymap.c:803
Inline: False
```
**Symbols:**

```
ffffffff811ec9f0-ffffffff811ecab9: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 array_of_map_gen_lookup(struct bpf_map *map, struct bpf_insn *insn_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811fae90)
Location: kernel/bpf/arraymap.c:803
Inline: False
```
**Symbols:**

```
ffffffff811fae90-ffffffff811faf59: array_of_map_gen_lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
