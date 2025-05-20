# Function: <code>prog_array_map_poke_run</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void prog_array_map_poke_run(struct bpf_map *map, u32 key, struct bpf_prog *old, struct bpf_prog *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81219fc0)
Location: kernel/bpf/arraymap.c:752
Inline: False
```
**Symbols:**

```
ffffffff81219fc0-ffffffff8121a0c5: prog_array_map_poke_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void prog_array_map_poke_run(struct bpf_map *map, u32 key, struct bpf_prog *old, struct bpf_prog *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121cc90)
Location: kernel/bpf/arraymap.c:891
Inline: False
```
**Symbols:**

```
ffffffff8121cc90-ffffffff8121ce5c: prog_array_map_poke_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void prog_array_map_poke_run(struct bpf_map *map, u32 key, struct bpf_prog *old, struct bpf_prog *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812207b0)
Location: kernel/bpf/arraymap.c:933
Inline: False
```
**Symbols:**

```
ffffffff812207b0-ffffffff8122097f: prog_array_map_poke_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void prog_array_map_poke_run(struct bpf_map *map, u32 key, struct bpf_prog *old, struct bpf_prog *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:954
Inline: False
```
**Symbols:**

```
ffffffff81258290-ffffffff8125845d: prog_array_map_poke_run (STB_LOCAL)
ffffffff81cb921f-ffffffff81cb923a: prog_array_map_poke_run.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void prog_array_map_poke_run(struct bpf_map *map, u32 key, struct bpf_prog *old, struct bpf_prog *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:985
Inline: False
```
**Symbols:**

```
ffffffff812a0f40-ffffffff812a111a: prog_array_map_poke_run (STB_LOCAL)
ffffffff81e6a4fd-ffffffff81e6a518: prog_array_map_poke_run.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void prog_array_map_poke_run(struct bpf_map *map, u32 key, struct bpf_prog *old, struct bpf_prog *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:991
Inline: False
```
**Symbols:**

```
ffffffff812fdd10-ffffffff812fdeea: prog_array_map_poke_run (STB_LOCAL)
ffffffff82061650-ffffffff8206166b: prog_array_map_poke_run.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void prog_array_map_poke_run(struct bpf_map *map, u32 key, struct bpf_prog *old, struct bpf_prog *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:1015
Inline: False
```
**Symbols:**

```
ffffffff8132c920-ffffffff8132cafa: prog_array_map_poke_run (STB_LOCAL)
ffffffff820e0beb-ffffffff820e0c06: prog_array_map_poke_run.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void prog_array_map_poke_run(struct bpf_map *map, u32 key, struct bpf_prog *old, struct bpf_prog *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/arraymap.c (0)
Location: kernel/bpf/arraymap.c:1027
Inline: False
```
**Symbols:**

```
ffffffff813526b0-ffffffff813527b0: prog_array_map_poke_run (STB_LOCAL)
ffffffff821bd3cb-ffffffff821bd3e6: prog_array_map_poke_run.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
