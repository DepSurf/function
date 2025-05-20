# Function: <code>threefish_encrypt_256</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void threefish_encrypt_256(struct threefish_key *key_ctx, u64 *input, u64 *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/threefish_block.c (ffffffff816da0f0)
Location: drivers/staging/skein/threefish_block.c:3
Inline: False
Direct callers:
  - drivers/staging/skein/threefish_api.c:threefish_encrypt_block_words
```
**Symbols:**

```
ffffffff816da0f0-ffffffff816da867: threefish_encrypt_256 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void threefish_encrypt_256(struct threefish_key *key_ctx, u64 *input, u64 *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/threefish_block.c (ffffffff8173e260)
Location: drivers/staging/skein/threefish_block.c:4
Inline: False
Direct callers:
  - drivers/staging/skein/threefish_api.c:threefish_encrypt_block_words
```
**Symbols:**

```
ffffffff8173e260-ffffffff8173e9da: threefish_encrypt_256 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void threefish_encrypt_256(struct threefish_key *key_ctx, u64 *input, u64 *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/threefish_block.c (ffffffff81771490)
Location: drivers/staging/skein/threefish_block.c:4
Inline: False
Direct callers:
  - drivers/staging/skein/threefish_api.c:threefish_encrypt_block_words
```
**Symbols:**

```
ffffffff81771490-ffffffff81771c0a: threefish_encrypt_256 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void threefish_encrypt_256(struct threefish_key *key_ctx, u64 *input, u64 *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/threefish_block.c (ffffffff8178f770)
Location: drivers/staging/skein/threefish_block.c:4
Inline: False
Direct callers:
  - drivers/staging/skein/threefish_api.c:threefish_encrypt_block_words
```
**Symbols:**

```
ffffffff8178f770-ffffffff8178fef4: threefish_encrypt_256 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void threefish_encrypt_256(struct threefish_key *key_ctx, u64 *input, u64 *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/threefish_block.c (ffffffff81805df0)
Location: drivers/staging/skein/threefish_block.c:5
Inline: False
Direct callers:
  - drivers/staging/skein/threefish_api.c:threefish_encrypt_block_words
```
**Symbols:**

```
ffffffff81805df0-ffffffff81806574: threefish_encrypt_256 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void threefish_encrypt_256(struct threefish_key *key_ctx, u64 *input, u64 *output);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/threefish_block.c (ffffffff8184fc40)
Location: drivers/staging/skein/threefish_block.c:5
Inline: False
Direct callers:
  - drivers/staging/skein/threefish_api.c:threefish_encrypt_block_words
```
**Symbols:**

```
ffffffff8184fc40-ffffffff818503c4: threefish_encrypt_256 (STB_GLOBAL)
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
