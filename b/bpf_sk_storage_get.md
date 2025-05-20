# Function: <code>bpf_sk_storage_get</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff819533f0)
Location: net/core/bpf_sk_storage.c:742
Inline: False
```
**Symbols:**

```
ffffffff819533f0-ffffffff819534c6: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff819897a0)
Location: net/core/bpf_sk_storage.c:841
Inline: False
```
**Symbols:**

```
ffffffff819897a0-ffffffff81989876: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a61d30)
Location: net/core/bpf_sk_storage.c:845
Inline: False
```
**Symbols:**

```
ffffffff81a61d30-ffffffff81a61e1e: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a6a280)
Location: net/core/bpf_sk_storage.c:256
Inline: False
```
**Symbols:**

```
ffffffff81a6a280-ffffffff81a6a385: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a529e0)
Location: net/core/bpf_sk_storage.c:256
Inline: False
```
**Symbols:**

```
ffffffff81a529e0-ffffffff81a52ae6: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:256
Inline: False
```
**Symbols:**

```
ffffffff81d38c5b-ffffffff81d38c7b: bpf_sk_storage_get.cold (STB_LOCAL)
ffffffff81b0b6a0-ffffffff81b0b7b8: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:259
Inline: False
```
**Symbols:**

```
ffffffff81f054b7-ffffffff81f054df: bpf_sk_storage_get.cold (STB_LOCAL)
ffffffff81c91e30-ffffffff81c91f71: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:230
Inline: False
```
**Symbols:**

```
ffffffff820ad4c4-ffffffff820ad4ec: bpf_sk_storage_get.cold (STB_LOCAL)
ffffffff81e4d420-ffffffff81e4d561: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:224
Inline: False
```
**Symbols:**

```
ffffffff8212e62d-ffffffff8212e648: bpf_sk_storage_get.cold (STB_LOCAL)
ffffffff81ea8ae0-ffffffff81ea8c20: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/bpf_sk_storage.c (0)
Location: net/core/bpf_sk_storage.c:224
Inline: False
```
**Symbols:**

```
ffffffff822103e0-ffffffff822103fb: bpf_sk_storage_get.cold (STB_LOCAL)
ffffffff81f6b5a0-ffffffff81f6b6e0: bpf_sk_storage_get (STB_GLOBAL)
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
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffff800010c31fd0)
Location: net/core/bpf_sk_storage.c:841
Inline: False
```
**Symbols:**

```
ffff800010c31fd0-ffff800010c320a4: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c0d48a6c)
Location: net/core/bpf_sk_storage.c:841
Inline: False
```
**Symbols:**

```
c0d48a6c-c0d48b38: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c000000000d2af80)
Location: net/core/bpf_sk_storage.c:841
Inline: False
```
**Symbols:**

```
c000000000d2af80-c000000000d2b108: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffe0007a77a0)
Location: net/core/bpf_sk_storage.c:841
Inline: False
```
**Symbols:**

```
ffffffe0007a77a0-ffffffe0007a7854: bpf_sk_storage_get (STB_GLOBAL)
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
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81929610)
Location: net/core/bpf_sk_storage.c:841
Inline: False
```
**Symbols:**

```
ffffffff81929610-ffffffff819296e6: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff818e33c0)
Location: net/core/bpf_sk_storage.c:841
Inline: False
```
**Symbols:**

```
ffffffff818e33c0-ffffffff818e3496: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8197a7a0)
Location: net/core/bpf_sk_storage.c:841
Inline: False
```
**Symbols:**

```
ffffffff8197a7a0-ffffffff8197a876: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_sk_storage_get(u64 map, u64 sk, u64 value, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8199ccd0)
Location: net/core/bpf_sk_storage.c:841
Inline: False
```
**Symbols:**

```
ffffffff8199ccd0-ffffffff8199cda6: bpf_sk_storage_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 gfp_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 __ur_1</code>
</li>
</ul>
</details>
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
