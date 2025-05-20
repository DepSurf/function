# Function: <code>blake2s_compress_generic</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blake2s_compress_generic(struct blake2s_state *state, const u8 *block, size_t nblocks, const u32 inc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/blake2s-generic.c (ffffffff816f0440)
Location: lib/crypto/blake2s-generic.c:44
Inline: False
Direct callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
**Symbols:**

```
ffffffff816f0440-ffffffff816f1bd5: blake2s_compress_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blake2s_compress_generic(struct blake2s_state *state, const u8 *block, size_t nblocks, const u32 inc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/blake2s-generic.c (ffffffff817e1f50)
Location: lib/crypto/blake2s-generic.c:44
Inline: False
Direct callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
**Symbols:**

```
ffffffff817e1f50-ffffffff817e36e3: blake2s_compress_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blake2s_compress_generic(struct blake2s_state *state, const u8 *block, size_t nblocks, const u32 inc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/blake2s-generic.c (ffffffff81821eb0)
Location: lib/crypto/blake2s-generic.c:43
Inline: False
Direct callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
**Symbols:**

```
ffffffff81821eb0-ffffffff81823633: blake2s_compress_generic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blake2s_compress_generic(struct blake2s_state *state, const u8 *block, size_t nblocks, const u32 inc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/blake2s-generic.c (ffffffff81867ef0)
Location: lib/crypto/blake2s-generic.c:43
Inline: False
Direct callers:
  - arch/x86/crypto/blake2s-glue.c:blake2s_compress
```
**Symbols:**

```
ffffffff81867ef0-ffffffff81869673: blake2s_compress_generic (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
