# Function: <code>threefish_encrypt_512</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void threefish_encrypt_512(struct threefish_key *key_ctx, u64 *input, u64 *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/threefish_block.c (ffffffff816db040)
Location: drivers/staging/skein/threefish_block.c:1139
Inline: False
Direct callers:
  - drivers/staging/skein/threefish_api.c:threefish_encrypt_block_words
```
**Symbols:**

```
ffffffff816db040-ffffffff816dbf7a: threefish_encrypt_512 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void threefish_encrypt_512(struct threefish_key *key_ctx, u64 *input, u64 *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/threefish_block.c (ffffffff8173f1a0)
Location: drivers/staging/skein/threefish_block.c:1140
Inline: False
Direct callers:
  - drivers/staging/skein/threefish_api.c:threefish_encrypt_block_words
```
**Symbols:**

```
ffffffff8173f1a0-ffffffff817400d4: threefish_encrypt_512 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void threefish_encrypt_512(struct threefish_key *key_ctx, u64 *input, u64 *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/threefish_block.c (ffffffff817723d0)
Location: drivers/staging/skein/threefish_block.c:1124
Inline: False
Direct callers:
  - drivers/staging/skein/threefish_api.c:threefish_encrypt_block_words
```
**Symbols:**

```
ffffffff817723d0-ffffffff81773304: threefish_encrypt_512 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void threefish_encrypt_512(struct threefish_key *key_ctx, u64 *input, u64 *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/threefish_block.c (ffffffff817906d0)
Location: drivers/staging/skein/threefish_block.c:1124
Inline: False
Direct callers:
  - drivers/staging/skein/threefish_api.c:threefish_encrypt_block_words
```
**Symbols:**

```
ffffffff817906d0-ffffffff817915f0: threefish_encrypt_512 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void threefish_encrypt_512(struct threefish_key *key_ctx, u64 *input, u64 *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/threefish_block.c (ffffffff81806d50)
Location: drivers/staging/skein/threefish_block.c:1125
Inline: False
Direct callers:
  - drivers/staging/skein/threefish_api.c:threefish_encrypt_block_words
```
**Symbols:**

```
ffffffff81806d50-ffffffff81807c70: threefish_encrypt_512 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void threefish_encrypt_512(struct threefish_key *key_ctx, u64 *input, u64 *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/threefish_block.c (ffffffff81850ba0)
Location: drivers/staging/skein/threefish_block.c:1125
Inline: False
Direct callers:
  - drivers/staging/skein/threefish_api.c:threefish_encrypt_block_words
```
**Symbols:**

```
ffffffff81850ba0-ffffffff81851ad0: threefish_encrypt_512 (STB_GLOBAL)
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
