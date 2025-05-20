# Function: <code>array_map_check_btf</code>

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
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, u32 btf_key_id, u32 btf_value_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811c38f0)
Location: kernel/bpf/arraymap.c:361
Inline: False
```
**Symbols:**

```
ffffffff811c38f0-ffffffff811c3995: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811d51d0)
Location: kernel/bpf/arraymap.c:384
Inline: False
```
**Symbols:**

```
ffffffff811d51d0-ffffffff811d5205: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ea2c0)
Location: kernel/bpf/arraymap.c:415
Inline: True
```
**Symbols:**

```
ffffffff811ea2c0-ffffffff811ea343: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811f6a20)
Location: kernel/bpf/arraymap.c:415
Inline: True
```
**Symbols:**

```
ffffffff811f6a20-ffffffff811f6aa3: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121a2d0)
Location: kernel/bpf/arraymap.c:449
Inline: True
```
**Symbols:**

```
ffffffff8121a2d0-ffffffff8121a353: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8121cf40)
Location: kernel/bpf/arraymap.c:435
Inline: True
```
**Symbols:**

```
ffffffff8121cf40-ffffffff8121cfc3: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81220a60)
Location: kernel/bpf/arraymap.c:435
Inline: True
```
**Symbols:**

```
ffffffff81220a60-ffffffff81220add: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81258460)
Location: kernel/bpf/arraymap.c:455
Inline: True
```
**Symbols:**

```
ffffffff81258460-ffffffff812584dd: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812a1150)
Location: kernel/bpf/arraymap.c:484
Inline: True
```
**Symbols:**

```
ffffffff812a1150-ffffffff812a11e1: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff812fdf00)
Location: kernel/bpf/arraymap.c:488
Inline: True
```
**Symbols:**

```
ffffffff812fdf00-ffffffff812fdf91: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff8132cb10)
Location: kernel/bpf/arraymap.c:488
Inline: True
```
**Symbols:**

```
ffffffff8132cb10-ffffffff8132cba9: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff81350e60)
Location: kernel/bpf/arraymap.c:488
Inline: True
```
**Symbols:**

```
ffffffff81350e60-ffffffff81350ef9: array_map_check_btf (STB_LOCAL)
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
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffff80001027b230)
Location: kernel/bpf/arraymap.c:415
Inline: True
```
**Symbols:**

```
ffff80001027b230-ffff80001027b2e4: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c04ad208)
Location: kernel/bpf/arraymap.c:415
Inline: True
```
**Symbols:**

```
c04ad208-c04ad2a0: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (c0000000003248a0)
Location: kernel/bpf/arraymap.c:415
Inline: True
```
**Symbols:**

```
c0000000003248a0-c000000000324968: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffe0001b2eea)
Location: kernel/bpf/arraymap.c:415
Inline: True
```
**Symbols:**

```
ffffffe0001b2eea-ffffffe0001b2f6e: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ef040)
Location: kernel/bpf/arraymap.c:415
Inline: True
```
**Symbols:**

```
ffffffff811ef040-ffffffff811ef0c3: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811e1dd0)
Location: kernel/bpf/arraymap.c:415
Inline: True
```
**Symbols:**

```
ffffffff811e1dd0-ffffffff811e1e53: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811ece10)
Location: kernel/bpf/arraymap.c:415
Inline: True
```
**Symbols:**

```
ffffffff811ece10-ffffffff811ece93: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int array_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/arraymap.c (ffffffff811fb2b0)
Location: kernel/bpf/arraymap.c:415
Inline: True
```
**Symbols:**

```
ffffffff811fb2b0-ffffffff811fb333: array_map_check_btf (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct btf_type *key_type</code>
</li>
<li>
<b>Param added. </b>
<code>const struct btf_type *value_type</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 btf_key_id</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 btf_value_id</code>
</li>
</ul>
</details>
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
