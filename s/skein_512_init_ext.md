# Function: <code>skein_512_init_ext</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int skein_512_init_ext(struct skein_512_ctx *ctx, size_t hash_bit_len, u64 tree_info, const u8 *key, size_t key_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_base.c (ffffffff816d6cc0)
Location: drivers/staging/skein/skein_base.c:310
Inline: False
Direct callers:
  - drivers/staging/skein/skein_api.c:skein_init
  - drivers/staging/skein/skein_api.c:skein_mac_init
```
**Symbols:**

```
ffffffff816d6cc0-ffffffff816d6e73: skein_512_init_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int skein_512_init_ext(struct skein_512_ctx *ctx, size_t hash_bit_len, u64 tree_info, const u8 *key, size_t key_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_base.c (ffffffff8173aec0)
Location: drivers/staging/skein/skein_base.c:310
Inline: False
Direct callers:
  - drivers/staging/skein/skein_api.c:skein_mac_init
  - drivers/staging/skein/skein_api.c:skein_init
```
**Symbols:**

```
ffffffff8173aec0-ffffffff8173b073: skein_512_init_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skein_512_init_ext(struct skein_512_ctx *ctx, size_t hash_bit_len, u64 tree_info, const u8 *key, size_t key_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_base.c (ffffffff8176e0f0)
Location: drivers/staging/skein/skein_base.c:310
Inline: False
Direct callers:
  - drivers/staging/skein/skein_api.c:skein_mac_init
  - drivers/staging/skein/skein_api.c:skein_init
```
**Symbols:**

```
ffffffff8176e0f0-ffffffff8176e2a3: skein_512_init_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skein_512_init_ext(struct skein_512_ctx *ctx, size_t hash_bit_len, u64 tree_info, const u8 *key, size_t key_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_base.c (ffffffff8178c430)
Location: drivers/staging/skein/skein_base.c:310
Inline: False
Direct callers:
  - drivers/staging/skein/skein_api.c:skein_mac_init
  - drivers/staging/skein/skein_api.c:skein_init
```
**Symbols:**

```
ffffffff8178c430-ffffffff8178c60a: skein_512_init_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skein_512_init_ext(struct skein_512_ctx *ctx, size_t hash_bit_len, u64 tree_info, const u8 *key, size_t key_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_base.c (ffffffff81802ab0)
Location: drivers/staging/skein/skein_base.c:310
Inline: False
Direct callers:
  - drivers/staging/skein/skein_api.c:skein_mac_init
  - drivers/staging/skein/skein_api.c:skein_init
```
**Symbols:**

```
ffffffff81802ab0-ffffffff81802c8a: skein_512_init_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skein_512_init_ext(struct skein_512_ctx *ctx, size_t hash_bit_len, u64 tree_info, const u8 *key, size_t key_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_base.c (ffffffff8184c6b0)
Location: drivers/staging/skein/skein_base.c:310
Inline: False
Direct callers:
  - drivers/staging/skein/skein_api.c:skein_mac_init
  - drivers/staging/skein/skein_api.c:skein_init
```
**Symbols:**

```
ffffffff8184c6b0-ffffffff8184c88a: skein_512_init_ext (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
</ul>
