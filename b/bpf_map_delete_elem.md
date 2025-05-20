# Function: <code>bpf_map_delete_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81177310)
Location: kernel/bpf/helpers.c:78
Inline: False
```
**Symbols:**

```
ffffffff81177310-ffffffff81177324: bpf_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81185dc0)
Location: kernel/bpf/helpers.c:78
Inline: False
```
**Symbols:**

```
ffffffff81185dc0-ffffffff81185dd4: bpf_map_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81193190)
Location: kernel/bpf/helpers.c:64
Inline: False
```
**Symbols:**

```
ffffffff81193190-ffffffff811931a4: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8119a1b0)
Location: kernel/bpf/helpers.c:64
Inline: False
```
**Symbols:**

```
ffffffff8119a1b0-ffffffff8119a1c4: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811a9580)
Location: kernel/bpf/helpers.c:64
Inline: False
```
**Symbols:**

```
ffffffff811a9580-ffffffff811a9599: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811c0a60)
Location: kernel/bpf/helpers.c:64
Inline: False
```
**Symbols:**

```
ffffffff811c0a60-ffffffff811c0a79: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811d1ec0)
Location: kernel/bpf/helpers.c:64
Inline: False
```
**Symbols:**

```
ffffffff811d1ec0-ffffffff811d1ed9: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e61f0)
Location: kernel/bpf/helpers.c:59
Inline: False
```
**Symbols:**

```
ffffffff811e61f0-ffffffff811e6209: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f2940)
Location: kernel/bpf/helpers.c:59
Inline: False
```
**Symbols:**

```
ffffffff811f2940-ffffffff811f2959: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81214780)
Location: kernel/bpf/helpers.c:62
Inline: False
```
**Symbols:**

```
ffffffff81214780-ffffffff81214799: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81216240)
Location: kernel/bpf/helpers.c:62
Inline: False
```
**Symbols:**

```
ffffffff81216240-ffffffff81216259: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81218f50)
Location: kernel/bpf/helpers.c:63
Inline: False
```
**Symbols:**

```
ffffffff81218f50-ffffffff81218f69: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8124f670)
Location: kernel/bpf/helpers.c:63
Inline: False
```
**Symbols:**

```
ffffffff8124f670-ffffffff8124f689: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812967e0)
Location: kernel/bpf/helpers.c:66
Inline: False
```
**Symbols:**

```
ffffffff812967e0-ffffffff81296801: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f1730)
Location: kernel/bpf/helpers.c:69
Inline: False
```
**Symbols:**

```
ffffffff812f1730-ffffffff812f1751: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8131e320)
Location: kernel/bpf/helpers.c:70
Inline: False
```
**Symbols:**

```
ffffffff8131e320-ffffffff8131e33f: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81340740)
Location: kernel/bpf/helpers.c:73
Inline: False
```
**Symbols:**

```
ffffffff81340740-ffffffff8134075f: bpf_map_delete_elem (STB_GLOBAL)
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
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffff8000102762b0)
Location: kernel/bpf/helpers.c:59
Inline: False
```
**Symbols:**

```
ffff8000102762b0-ffff8000102762f0: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c04a88a0)
Location: kernel/bpf/helpers.c:59
Inline: False
```
**Symbols:**

```
c04a88a0-c04a88cc: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c00000000031e6f0)
Location: kernel/bpf/helpers.c:59
Inline: False
```
**Symbols:**

```
c00000000031e6f0-c00000000031e734: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffe0001ae782)
Location: kernel/bpf/helpers.c:59
Inline: False
```
**Symbols:**

```
ffffffe0001ae782-ffffffe0001ae7b2: bpf_map_delete_elem (STB_GLOBAL)
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
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811eaf60)
Location: kernel/bpf/helpers.c:59
Inline: False
```
**Symbols:**

```
ffffffff811eaf60-ffffffff811eaf79: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811ddd20)
Location: kernel/bpf/helpers.c:59
Inline: False
```
**Symbols:**

```
ffffffff811ddd20-ffffffff811ddd39: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e8d30)
Location: kernel/bpf/helpers.c:59
Inline: False
```
**Symbols:**

```
ffffffff811e8d30-ffffffff811e8d49: bpf_map_delete_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_map_delete_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f70e0)
Location: kernel/bpf/helpers.c:59
Inline: False
```
**Symbols:**

```
ffffffff811f70e0-ffffffff811f70f9: bpf_map_delete_elem (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 key</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
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
