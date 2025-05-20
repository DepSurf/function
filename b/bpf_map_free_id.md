# Function: <code>bpf_map_free_id</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119195d)
Location: kernel/bpf/syscall.c:145
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119e8a7)
Location: kernel/bpf/syscall.c:192
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b4ef0)
Location: kernel/bpf/syscall.c:228
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffffffff811b4ef0-ffffffff811b4f5f: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c32c0)
Location: kernel/bpf/syscall.c:256
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffffffff811c32c0-ffffffff811c332f: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4010)
Location: kernel/bpf/syscall.c:272
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffffffff811d4010-ffffffff811d407f: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e03a0)
Location: kernel/bpf/syscall.c:275
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffffffff811e03a0-ffffffff811e040f: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fca7d)
Location: kernel/bpf/syscall.c:429
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffffffff811fe8e0-ffffffff811fe94f: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fbdcd)
Location: kernel/bpf/syscall.c:366
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffffffff811fda20-ffffffff811fda8f: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fcb0d)
Location: kernel/bpf/syscall.c:367
Inline: True
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffffffff811fe5e0-ffffffff811fe64f: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122e64d)
Location: kernel/bpf/syscall.c:386
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff81230220-ffffffff8123028f: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81270c39)
Location: kernel/bpf/syscall.c:393
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff81272b70-ffffffff81272bfd: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c6c49)
Location: kernel/bpf/syscall.c:393
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_map_offload_map_free
```
**Symbols:**

```
ffffffff812c8e70-ffffffff812c8efd: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_free_id(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ec91c)
Location: kernel/bpf/syscall.c:366
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
**Symbols:**

```
ffffffff812f0460-ffffffff812f04c4: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_free_id(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130b030)
Location: kernel/bpf/syscall.c:367
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_map_offload_map_free
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
**Symbols:**

```
ffffffff8130f240-ffffffff8130f2a4: bpf_map_free_id (STB_GLOBAL)
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
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010262a18)
Location: kernel/bpf/syscall.c:275
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffff800010262a18-ffff800010262b08: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0495524)
Location: kernel/bpf/syscall.c:275
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
c0495524-c049559c: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000307710)
Location: kernel/bpf/syscall.c:275
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
c000000000307710-c0000000003077e4: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f314)
Location: kernel/bpf/syscall.c:275
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffffffe00019f314-ffffffe00019f3a2: bpf_map_free_id (STB_GLOBAL)
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
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d89c0)
Location: kernel/bpf/syscall.c:275
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffffffff811d89c0-ffffffff811d8a2f: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cb780)
Location: kernel/bpf/syscall.c:275
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffffffff811cb780-ffffffff811cb7ef: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6790)
Location: kernel/bpf/syscall.c:275
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffffffff811d6790-ffffffff811d67ff: bpf_map_free_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_map_free_id(struct bpf_map *map, bool do_idr_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e4b00)
Location: kernel/bpf/syscall.c:275
Inline: False
Direct callers:
  - kernel/bpf/offload.c:__bpf_map_offload_destroy
```
**Symbols:**

```
ffffffff811e4b00-ffffffff811e4b6f: bpf_map_free_id (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool do_idr_lock</code>
</li>
</ul>
</details>
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
