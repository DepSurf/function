# Function: <code>bpf_prog_array_compatible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811713b0)
Location: kernel/bpf/core.c:657
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811713b0-ffffffff811713ef: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8117f2f2)
Location: kernel/bpf/core.c:926
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8117f180-ffffffff8117f1bf: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118b162)
Location: kernel/bpf/core.c:1008
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8118aff0-ffffffff8118b02f: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118fc96)
Location: kernel/bpf/core.c:1253
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8118fb10-ffffffff8118fb4e: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119e422)
Location: kernel/bpf/core.c:1329
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8119dfa0-ffffffff8119dfea: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b2c5b)
Location: kernel/bpf/core.c:1411
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811b26d0-ffffffff811b2720: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c17d9)
Location: kernel/bpf/core.c:1654
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811c1210-ffffffff811c1260: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1ef1)
Location: kernel/bpf/core.c:1649
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811d1960-ffffffff811d19b0: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811de491)
Location: kernel/bpf/core.c:1649
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811ddee0-ffffffff811ddf30: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fb11a)
Location: kernel/bpf/core.c:1728
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811fa990-ffffffff811fa9e3: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa2cb)
Location: kernel/bpf/core.c:1725
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811f9be0-ffffffff811f9c33: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fb295)
Location: kernel/bpf/core.c:1819
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811fab50-ffffffff811faba3: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122c996)
Location: kernel/bpf/core.c:1823
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff8122a220-ffffffff8122a2b6: bpf_prog_array_compatible.part.0 (STB_LOCAL)
ffffffff81cb78c8-ffffffff81cb78e4: bpf_prog_array_compatible.part.0.cold (STB_LOCAL)
ffffffff8122c2a0-ffffffff8122c2b9: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025f720)
Location: kernel/bpf/core.c:1649
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffff80001025ee70-ffff80001025eefc: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0492b00)
Location: kernel/bpf/core.c:1649
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
c04923e4-c049245c: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c00000000030472c)
Location: kernel/bpf/core.c:1649
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
c000000000303e40-c000000000303eb8: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d5bc)
Location: kernel/bpf/core.c:1649
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffe00019cff2-ffffffe00019d06a: bpf_prog_array_compatible (STB_GLOBAL)
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
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6ab1)
Location: kernel/bpf/core.c:1649
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811d6500-ffffffff811d6550: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c9871)
Location: kernel/bpf/core.c:1649
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811c92c0-ffffffff811c9310: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d4881)
Location: kernel/bpf/core.c:1649
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811d42d0-ffffffff811d4320: bpf_prog_array_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool bpf_prog_array_compatible(struct bpf_array *array, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2bb1)
Location: kernel/bpf/core.c:1649
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
```
**Symbols:**

```
ffffffff811e25f0-ffffffff811e2640: bpf_prog_array_compatible (STB_GLOBAL)
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
