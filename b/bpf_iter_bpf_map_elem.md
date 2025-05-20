# Function: <code>bpf_iter_bpf_map_elem</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_iter_bpf_map_elem(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff82fe464e)
Location: kernel/bpf/map_iter.c:165
Inline: False
```
**Symbols:**

```
ffffffff82fe464e-ffffffff82fe465b: bpf_iter_bpf_map_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_bpf_map_elem(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff831eed2b)
Location: kernel/bpf/map_iter.c:165
Inline: False
```
**Symbols:**

```
ffffffff831eed2b-ffffffff831eed38: bpf_iter_bpf_map_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_bpf_map_elem(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff832d42cd)
Location: kernel/bpf/map_iter.c:165
Inline: False
```
**Symbols:**

```
ffffffff832d42cd-ffffffff832d42da: bpf_iter_bpf_map_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_bpf_map_elem(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff834888cc)
Location: kernel/bpf/map_iter.c:165
Inline: False
```
**Symbols:**

```
ffffffff834888cc-ffffffff834888dd: bpf_iter_bpf_map_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_iter_bpf_map_elem(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff83eb8c30)
Location: kernel/bpf/map_iter.c:165
Inline: False
```
**Symbols:**

```
ffffffff83eb8c30-ffffffff83eb8c41: bpf_iter_bpf_map_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_iter_bpf_map_elem(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff836de160)
Location: kernel/bpf/map_iter.c:165
Inline: False
```
**Symbols:**

```
ffffffff836de160-ffffffff836de171: bpf_iter_bpf_map_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_iter_bpf_map_elem(struct bpf_iter_meta *meta, struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_iter.c (ffffffff839107a0)
Location: kernel/bpf/map_iter.c:164
Inline: False
```
**Symbols:**

```
ffffffff839107a0-ffffffff839107b1: bpf_iter_bpf_map_elem (STB_GLOBAL)
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
