# Function: <code>__xsk_map_flush</code>

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
void __xsk_map_flush(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811cb3b0)
Location: kernel/bpf/xskmap.c:141
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush_map
```
**Symbols:**

```
ffffffff811cb3b0-ffffffff811cb435: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __xsk_map_flush(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811decc0)
Location: kernel/bpf/xskmap.c:142
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush_map
```
**Symbols:**

```
ffffffff811decc0-ffffffff811ded45: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __xsk_map_flush(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f4620)
Location: kernel/bpf/xskmap.c:140
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush_map
```
**Symbols:**

```
ffffffff811f4620-ffffffff811f46a4: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __xsk_map_flush(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff812015c0)
Location: kernel/bpf/xskmap.c:192
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush_map
```
**Symbols:**

```
ffffffff812015c0-ffffffff81201644: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __xsk_map_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba8180)
Location: net/xdp/xsk.c:241
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush
```
**Symbols:**

```
ffffffff81ba8180-ffffffff81ba822e: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __xsk_map_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb7eb0)
Location: net/xdp/xsk.c:285
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush
```
**Symbols:**

```
ffffffff81bb7eb0-ffffffff81bb7f69: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __xsk_map_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba7090)
Location: net/xdp/xsk.c:300
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush
```
**Symbols:**

```
ffffffff81ba7090-ffffffff81ba713f: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __xsk_map_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c74d10)
Location: net/xdp/xsk.c:300
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush
```
**Symbols:**

```
ffffffff81c74d10-ffffffff81c74dbf: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __xsk_map_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81e18de0)
Location: net/xdp/xsk.c:285
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush
```
**Symbols:**

```
ffffffff81e18de0-ffffffff81e18e9b: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __xsk_map_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ff0090)
Location: net/xdp/xsk.c:285
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush
```
**Symbols:**

```
ffffffff81ff0090-ffffffff81ff014b: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __xsk_map_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8206c230)
Location: net/xdp/xsk.c:286
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush
```
**Symbols:**

```
ffffffff8206c230-ffffffff8206c2eb: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __xsk_map_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff82140010)
Location: net/xdp/xsk.c:388
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush
```
**Symbols:**

```
ffffffff82140010-ffffffff821400cb: __xsk_map_flush (STB_GLOBAL)
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
void __xsk_map_flush(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffff800010289568)
Location: kernel/bpf/xskmap.c:192
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush_map
```
**Symbols:**

```
ffff800010289568-ffff8000102895ec: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __xsk_map_flush(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c04b8f24)
Location: kernel/bpf/xskmap.c:192
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush_map
```
**Symbols:**

```
c04b8f24-c04b8f94: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __xsk_map_flush(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c000000000334c00)
Location: kernel/bpf/xskmap.c:192
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush_map
```
**Symbols:**

```
c000000000334c00-c000000000334cb8: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __xsk_map_flush(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffe0001bd94a)
Location: kernel/bpf/xskmap.c:192
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush_map
```
**Symbols:**

```
ffffffe0001bd94a-ffffffe0001bd9cc: __xsk_map_flush (STB_GLOBAL)
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
void __xsk_map_flush(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f9be0)
Location: kernel/bpf/xskmap.c:192
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush_map
```
**Symbols:**

```
ffffffff811f9be0-ffffffff811f9c64: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __xsk_map_flush(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811ec930)
Location: kernel/bpf/xskmap.c:192
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush_map
```
**Symbols:**

```
ffffffff811ec930-ffffffff811ec9b4: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __xsk_map_flush(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f79b0)
Location: kernel/bpf/xskmap.c:192
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush_map
```
**Symbols:**

```
ffffffff811f79b0-ffffffff811f7a34: __xsk_map_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __xsk_map_flush(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff81205f30)
Location: kernel/bpf/xskmap.c:192
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_flush_map
```
**Symbols:**

```
ffffffff81205f30-ffffffff81205fb4: __xsk_map_flush (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct bpf_map *map</code>
</li>
</ul>
</details>
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
