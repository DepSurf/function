# Function: <code>chacha20_block</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void chacha20_block(u32 *state, void *stream);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha20.c (ffffffff81890c10)
Location: lib/chacha20.c:24
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff81890c10-ffffffff81890eb1: chacha20_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void chacha20_block(u32 *state, void *stream);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha20.c (ffffffff818c5230)
Location: lib/chacha20.c:24
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff818c5230-ffffffff818c54d1: chacha20_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void chacha20_block(u32 *state, void *stream);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha20.c (ffffffff818eb560)
Location: lib/chacha20.c:24
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff818eb560-ffffffff818eb7fc: chacha20_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void chacha20_block(u32 *state, void *stream);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha20.c (ffffffff81971520)
Location: lib/chacha20.c:24
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff81971520-ffffffff819717bc: chacha20_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void chacha20_block(u32 *state, u32 *stream);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha20.c (ffffffff819cd8f0)
Location: lib/chacha20.c:19
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff819cd8f0-ffffffff819cdb8c: chacha20_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81666532)
Location: include/crypto/chacha.h:38
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169af42)
Location: include/crypto/chacha.h:38
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bdc72)
Location: include/crypto/chacha.h:38
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817724f2)
Location: include/crypto/chacha.h:38
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178d562)
Location: include/crypto/chacha.h:34
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81770512)
Location: include/crypto/chacha.h:34
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f5ec5)
Location: include/crypto/chacha.h:34
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff819354c1)
Location: include/crypto/chacha.h:34
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_fast_key_erasure
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a93da1)
Location: include/crypto/chacha.h:34
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_fast_key_erasure
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81adef81)
Location: include/crypto/chacha.h:34
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_fast_key_erasure
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b323a1)
Location: include/crypto/chacha.h:34
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_user
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:crng_fast_key_erasure
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108afaa8)
Location: include/crypto/chacha.h:38
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09aa320)
Location: include/crypto/chacha.h:38
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000947cf8)
Location: include/crypto/chacha.h:38
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe0005620f2)
Location: include/crypto/chacha.h:38
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816836e2)
Location: include/crypto/chacha.h:38
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81661362)
Location: include/crypto/chacha.h:38
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b1ab2)
Location: include/crypto/chacha.h:38
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cbf52)
Location: include/crypto/chacha.h:38
Inline: True
Inline callers:
  - drivers/char/random.c:_extract_crng
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *stream</code> ➡️ <code>u32 *stream</code>
</li>
</ul>
</details>
</li>
</ul>
