# Function: <code>xxh32_update</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8149f990)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff8149f990-ffffffff8149fb52: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff814d4b60)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff814d4b60-ffffffff814d4d16: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff814e95b0)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff814e95b0-ffffffff814e9766: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff815161f0)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff815161f0-ffffffff815163aa: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff81536c30)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff81536c30-ffffffff81536dea: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8159b190)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff8159b190-ffffffff8159b34b: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff815b6b80)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff815b6b80-ffffffff815b6d3b: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff815c19e0)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff815c19e0-ffffffff815c1b92: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff81629850)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff81629850-ffffffff81629a02: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff816faa90)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff816faa90-ffffffff816fac76: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xxhash.c (0)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff82078dae-ffffffff82078dc3: xxh32_update.cold (STB_LOCAL)
ffffffff817ed540-ffffffff817ed766: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xxhash.c (0)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff820f9478-ffffffff820f94cd: xxh32_update.cold (STB_LOCAL)
ffffffff8182d7a0-ffffffff8182da9f: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xxhash.c (0)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff821d75e5-ffffffff821d763a: xxh32_update.cold (STB_LOCAL)
ffffffff8187f330-ffffffff8187f62f: xxh32_update (STB_GLOBAL)
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
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffff8000106436e0)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffff8000106436e0-ffff8000106438c8: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (c07e9a44)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
c07e9a44-c07e9c38: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (c0000000007eec10)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
c0000000007eec10-c0000000007eeec4: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffe00046fd2e)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffe00046fd2e-ffffffe000470078: xxh32_update (STB_GLOBAL)
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
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8152f210)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff8152f210-ffffffff8152f3ca: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8151f4f0)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff8151f4f0-ffffffff8151f6aa: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff8152af50)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff8152af50-ffffffff8152b10a: xxh32_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xxh32_update(struct xxh32_state *state, const void *input, const size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xxhash.c (ffffffff81544cb0)
Location: lib/xxhash.c:270
Inline: False
```
**Symbols:**

```
ffffffff81544cb0-ffffffff81544e6a: xxh32_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
