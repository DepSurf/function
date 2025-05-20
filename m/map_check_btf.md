# Function: <code>map_check_btf</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c52dd)
Location: kernel/bpf/syscall.c:466
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d44e6)
Location: kernel/bpf/syscall.c:498
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e0be6)
Location: kernel/bpf/syscall.c:501
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int map_check_btf(struct bpf_map *map, const struct btf *btf, u32 btf_key_id, u32 btf_value_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fbbb0)
Location: kernel/bpf/syscall.c:741
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff811fbbb0-ffffffff811fbd38: map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int map_check_btf(struct bpf_map *map, const struct btf *btf, u32 btf_key_id, u32 btf_value_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fac70)
Location: kernel/bpf/syscall.c:748
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff811fac70-ffffffff811fadf8: map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int map_check_btf(struct bpf_map *map, const struct btf *btf, u32 btf_key_id, u32 btf_value_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fbbd0)
Location: kernel/bpf/syscall.c:749
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff811fbbd0-ffffffff811fbd5c: map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int map_check_btf(struct bpf_map *map, const struct btf *btf, u32 btf_key_id, u32 btf_value_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:765
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff8122d940-ffffffff8122db29: map_check_btf (STB_LOCAL)
ffffffff81cb7998-ffffffff81cb79ad: map_check_btf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int map_check_btf(struct bpf_map *map, const struct btf *btf, u32 btf_key_id, u32 btf_value_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:964
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff81272ef0-ffffffff81273166: map_check_btf (STB_LOCAL)
ffffffff81e68cb3-ffffffff81e68cc8: map_check_btf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int map_check_btf(struct bpf_map *map, const struct btf *btf, u32 btf_key_id, u32 btf_value_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c9490)
Location: kernel/bpf/syscall.c:985
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff812c9490-ffffffff812c96f9: map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int map_check_btf(struct bpf_map *map, const struct btf *btf, u32 btf_key_id, u32 btf_value_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f0be0)
Location: kernel/bpf/syscall.c:984
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff812f0be0-ffffffff812f0e71: map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int map_check_btf(struct bpf_map *map, const struct btf *btf, u32 btf_key_id, u32 btf_value_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130f9e0)
Location: kernel/bpf/syscall.c:1014
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff8130f9e0-ffffffff8130fc7a: map_check_btf (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff8000102631e4)
Location: kernel/bpf/syscall.c:501
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0495de0)
Location: kernel/bpf/syscall.c:501
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0000000003084f0)
Location: kernel/bpf/syscall.c:501
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019fb98)
Location: kernel/bpf/syscall.c:501
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d9206)
Location: kernel/bpf/syscall.c:501
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cbfc6)
Location: kernel/bpf/syscall.c:501
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6fd6)
Location: kernel/bpf/syscall.c:501
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e5346)
Location: kernel/bpf/syscall.c:501
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
</details>
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
