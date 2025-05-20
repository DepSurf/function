# Function: <code>crypto_alloc_acomp_node</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct crypto_acomp *crypto_alloc_acomp_node(const char *alg_name, u32 type, u32 mask, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff81545250)
Location: crypto/acompress.c:112
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
**Symbols:**

```
ffffffff81545250-ffffffff8154526e: crypto_alloc_acomp_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct crypto_acomp *crypto_alloc_acomp_node(const char *alg_name, u32 type, u32 mask, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff8154d8e0)
Location: crypto/acompress.c:112
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
**Symbols:**

```
ffffffff8154d8e0-ffffffff8154d8fe: crypto_alloc_acomp_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct crypto_acomp *crypto_alloc_acomp_node(const char *alg_name, u32 type, u32 mask, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff815ae0c0)
Location: crypto/acompress.c:112
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
**Symbols:**

```
ffffffff815ae0c0-ffffffff815ae0de: crypto_alloc_acomp_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct crypto_acomp *crypto_alloc_acomp_node(const char *alg_name, u32 type, u32 mask, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff816565d0)
Location: crypto/acompress.c:112
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
**Symbols:**

```
ffffffff816565d0-ffffffff816565fd: crypto_alloc_acomp_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct crypto_acomp *crypto_alloc_acomp_node(const char *alg_name, u32 type, u32 mask, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff81710840)
Location: crypto/acompress.c:112
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
**Symbols:**

```
ffffffff81710840-ffffffff8171086d: crypto_alloc_acomp_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct crypto_acomp *crypto_alloc_acomp_node(const char *alg_name, u32 type, u32 mask, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff8174b2f0)
Location: crypto/acompress.c:147
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
**Symbols:**

```
ffffffff8174b2f0-ffffffff8174b31d: crypto_alloc_acomp_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct crypto_acomp *crypto_alloc_acomp_node(const char *alg_name, u32 type, u32 mask, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/acompress.c (ffffffff8178d1c0)
Location: crypto/acompress.c:147
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
```
**Symbols:**

```
ffffffff8178d1c0-ffffffff8178d1ed: crypto_alloc_acomp_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
