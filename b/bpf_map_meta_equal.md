# Function: <code>bpf_map_meta_equal</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff8119ebb2)
Location: kernel/bpf/map_in_map.c:59
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff8119eb40-ffffffff8119eb6c: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811aea52)
Location: kernel/bpf/map_in_map.c:59
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff811ae9d0-ffffffff811aea02: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811c6200)
Location: kernel/bpf/map_in_map.c:59
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff811c6180-ffffffff811c61b2: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811d7cf0)
Location: kernel/bpf/map_in_map.c:74
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff811d7c70-ffffffff811d7ca2: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811ec681)
Location: kernel/bpf/map_in_map.c:77
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff811ec600-ffffffff811ec632: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811f8de1)
Location: kernel/bpf/map_in_map.c:77
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff811f8d60-ffffffff811f8d92: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff8121cbe1)
Location: kernel/bpf/map_in_map.c:77
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff8121cb60-ffffffff8121cb92: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff8121fa90)
Location: kernel/bpf/map_in_map.c:71
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_meta_equal
```
**Symbols:**

```
ffffffff8121fa90-ffffffff8121faba: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff81223510)
Location: kernel/bpf/map_in_map.c:71
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_meta_equal
```
**Symbols:**

```
ffffffff81223510-ffffffff8122353a: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff8125b320)
Location: kernel/bpf/map_in_map.c:78
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_meta_equal
```
**Symbols:**

```
ffffffff8125b320-ffffffff8125b352: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff812a4510)
Location: kernel/bpf/map_in_map.c:80
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_meta_equal
```
**Symbols:**

```
ffffffff812a4510-ffffffff812a455d: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff813021a0)
Location: kernel/bpf/map_in_map.c:108
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_meta_equal
```
**Symbols:**

```
ffffffff813021a0-ffffffff813021ed: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff81330d30)
Location: kernel/bpf/map_in_map.c:97
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_meta_equal
```
**Symbols:**

```
ffffffff81330d30-ffffffff81330d7d: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff81355290)
Location: kernel/bpf/map_in_map.c:97
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_meta_equal
```
**Symbols:**

```
ffffffff81355290-ffffffff813552dd: bpf_map_meta_equal (STB_GLOBAL)
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
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffff80001027e36c)
Location: kernel/bpf/map_in_map.c:77
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffff80001027e2a8-ffff80001027e31c: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (c04afad4)
Location: kernel/bpf/map_in_map.c:77
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
c04afa0c-c04afa80: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (c0000000003281a8)
Location: kernel/bpf/map_in_map.c:77
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
c0000000003280d0-c00000000032813c: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffe0001b54f8)
Location: kernel/bpf/map_in_map.c:77
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffe0001b544a-ffffffe0001b54a0: bpf_map_meta_equal (STB_GLOBAL)
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
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811f1401)
Location: kernel/bpf/map_in_map.c:77
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff811f1380-ffffffff811f13b2: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811e4151)
Location: kernel/bpf/map_in_map.c:77
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff811e40d0-ffffffff811e4102: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811ef1d1)
Location: kernel/bpf/map_in_map.c:77
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff811ef150-ffffffff811ef182: bpf_map_meta_equal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool bpf_map_meta_equal(const struct bpf_map *meta0, const struct bpf_map *meta1);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/map_in_map.c (ffffffff811fd6a1)
Location: kernel/bpf/map_in_map.c:77
Inline: True
Inline callers:
  - kernel/bpf/map_in_map.c:bpf_map_fd_get_ptr
```
**Symbols:**

```
ffffffff811fd620-ffffffff811fd652: bpf_map_meta_equal (STB_GLOBAL)
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
