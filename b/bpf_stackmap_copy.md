# Function: <code>bpf_stackmap_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811814c0)
Location: kernel/bpf/syscall.c:261
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff81188630-ffffffff811886c3: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118d0d0)
Location: kernel/bpf/syscall.c:298
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811974e0-ffffffff81197573: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191f50)
Location: kernel/bpf/syscall.c:386
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff8119f110-ffffffff8119f1a3: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f680)
Location: kernel/bpf/syscall.c:517
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff811b20c0-ffffffff811b215c: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b5730)
Location: kernel/bpf/syscall.c:594
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811d1640-ffffffff811d16e5: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c3680)
Location: kernel/bpf/syscall.c:650
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e11c0-ffffffff811e1265: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4890)
Location: kernel/bpf/syscall.c:707
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811f6da0-ffffffff811f6e4c: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e0f90)
Location: kernel/bpf/syscall.c:720
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff81203d60-ffffffff81203e0c: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ff0a0)
Location: kernel/bpf/syscall.c:978
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8122bbe0-ffffffff8122bc86: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe3e0)
Location: kernel/bpf/syscall.c:991
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81233ff0-ffffffff81234096: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fee70)
Location: kernel/bpf/syscall.c:992
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81237e30-ffffffff81237ed6: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81230ac0)
Location: kernel/bpf/syscall.c:1019
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81272400-ffffffff812724a6: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81273c10)
Location: kernel/bpf/syscall.c:1254
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff812c1650-ffffffff812c1708: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cad30)
Location: kernel/bpf/syscall.c:1297
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff81324f60-ffffffff81325018: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f26c0)
Location: kernel/bpf/syscall.c:1374
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff813551b0-ffffffff81355268: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81311560)
Location: kernel/bpf/syscall.c:1405
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
```
**Symbols:**

```
ffffffff8137db80-ffffffff8137dc38: bpf_stackmap_copy (STB_GLOBAL)
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
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010263b28)
Location: kernel/bpf/syscall.c:720
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffff80001028c4d0-ffff80001028c5dc: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0496170)
Location: kernel/bpf/syscall.c:720
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
c04bbba0-c04bbc78: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000308950)
Location: kernel/bpf/syscall.c:720
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
c000000000338810-c00000000033895c: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019fe26)
Location: kernel/bpf/syscall.c:720
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffe0001bfec0-ffffffe0001bff7c: bpf_stackmap_copy (STB_GLOBAL)
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
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d95b0)
Location: kernel/bpf/syscall.c:720
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811fc380-ffffffff811fc42c: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cc370)
Location: kernel/bpf/syscall.c:720
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811ef0d0-ffffffff811ef17c: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d7380)
Location: kernel/bpf/syscall.c:720
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff811fa150-ffffffff811fa1fc: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_stackmap_copy(struct bpf_map *map, void *key, void *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e5710)
Location: kernel/bpf/syscall.c:720
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
```
**Symbols:**

```
ffffffff81208c10-ffffffff81208cbc: bpf_stackmap_copy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
