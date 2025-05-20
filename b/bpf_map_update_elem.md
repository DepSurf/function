# Function: <code>bpf_map_update_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811772f0)
Location: kernel/bpf/helpers.c:57
Inline: False
```
**Symbols:**

```
ffffffff811772f0-ffffffff81177304: bpf_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81185da0)
Location: kernel/bpf/helpers.c:57
Inline: False
```
**Symbols:**

```
ffffffff81185da0-ffffffff81185db4: bpf_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81193170)
Location: kernel/bpf/helpers.c:46
Inline: False
```
**Symbols:**

```
ffffffff81193170-ffffffff81193184: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8119a190)
Location: kernel/bpf/helpers.c:46
Inline: False
```
**Symbols:**

```
ffffffff8119a190-ffffffff8119a1a4: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811a9560)
Location: kernel/bpf/helpers.c:46
Inline: False
```
**Symbols:**

```
ffffffff811a9560-ffffffff811a9579: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811c0a40)
Location: kernel/bpf/helpers.c:46
Inline: False
```
**Symbols:**

```
ffffffff811c0a40-ffffffff811c0a59: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811d1ea0)
Location: kernel/bpf/helpers.c:46
Inline: False
```
**Symbols:**

```
ffffffff811d1ea0-ffffffff811d1eb9: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e61d0)
Location: kernel/bpf/helpers.c:41
Inline: False
```
**Symbols:**

```
ffffffff811e61d0-ffffffff811e61e9: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f2920)
Location: kernel/bpf/helpers.c:41
Inline: False
```
**Symbols:**

```
ffffffff811f2920-ffffffff811f2939: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81214760)
Location: kernel/bpf/helpers.c:44
Inline: False
```
**Symbols:**

```
ffffffff81214760-ffffffff81214779: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81216220)
Location: kernel/bpf/helpers.c:44
Inline: False
```
**Symbols:**

```
ffffffff81216220-ffffffff81216239: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81218f30)
Location: kernel/bpf/helpers.c:45
Inline: False
```
**Symbols:**

```
ffffffff81218f30-ffffffff81218f49: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8124f650)
Location: kernel/bpf/helpers.c:45
Inline: False
```
**Symbols:**

```
ffffffff8124f650-ffffffff8124f669: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812967b0)
Location: kernel/bpf/helpers.c:48
Inline: False
```
**Symbols:**

```
ffffffff812967b0-ffffffff812967d5: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f16f0)
Location: kernel/bpf/helpers.c:51
Inline: False
```
**Symbols:**

```
ffffffff812f16f0-ffffffff812f1715: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8131e2e0)
Location: kernel/bpf/helpers.c:52
Inline: False
```
**Symbols:**

```
ffffffff8131e2e0-ffffffff8131e303: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81340700)
Location: kernel/bpf/helpers.c:54
Inline: False
```
**Symbols:**

```
ffffffff81340700-ffffffff81340723: bpf_map_update_elem (STB_GLOBAL)
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffff800010276258)
Location: kernel/bpf/helpers.c:41
Inline: False
```
**Symbols:**

```
ffff800010276258-ffff8000102762b0: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c04a8860)
Location: kernel/bpf/helpers.c:41
Inline: False
```
**Symbols:**

```
c04a8860-c04a88a0: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c00000000031e6a0)
Location: kernel/bpf/helpers.c:41
Inline: False
```
**Symbols:**

```
c00000000031e6a0-c00000000031e6e4: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffe0001ae742)
Location: kernel/bpf/helpers.c:41
Inline: False
```
**Symbols:**

```
ffffffe0001ae742-ffffffe0001ae782: bpf_map_update_elem (STB_GLOBAL)
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811eaf40)
Location: kernel/bpf/helpers.c:41
Inline: False
```
**Symbols:**

```
ffffffff811eaf40-ffffffff811eaf59: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811ddd00)
Location: kernel/bpf/helpers.c:41
Inline: False
```
**Symbols:**

```
ffffffff811ddd00-ffffffff811ddd19: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e8d10)
Location: kernel/bpf/helpers.c:41
Inline: False
```
**Symbols:**

```
ffffffff811e8d10-ffffffff811e8d29: bpf_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f70c0)
Location: kernel/bpf/helpers.c:41
Inline: False
```
**Symbols:**

```
ffffffff811f70c0-ffffffff811f70d9: bpf_map_update_elem (STB_GLOBAL)
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
<code>u64 value</code>
</li>
<li>
<b>Param added. </b>
<code>u64 flags</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
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
