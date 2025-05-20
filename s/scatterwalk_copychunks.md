# Function: <code>scatterwalk_copychunks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8139e900)
Location: crypto/scatterwalk.c:80
Inline: False
Direct callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_next
```
**Symbols:**

```
ffffffff8139e900-ffffffff8139eab2: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff813db6a0)
Location: crypto/scatterwalk.c:31
Inline: False
Direct callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
**Symbols:**

```
ffffffff813db6a0-ffffffff813db87f: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff813f2fe0)
Location: crypto/scatterwalk.c:31
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff813f2fe0-ffffffff813f31b4: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff813ff340)
Location: crypto/scatterwalk.c:31
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff813ff340-ffffffff813ff4e0: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81427900)
Location: crypto/scatterwalk.c:31
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff81427900-ffffffff81427a91: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8145a760)
Location: crypto/scatterwalk.c:31
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff8145a760-ffffffff8145a8f1: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814782d0)
Location: crypto/scatterwalk.c:31
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff814782d0-ffffffff81478461: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814a6100)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff814a6100-ffffffff814a629d: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814c0d90)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff814c0d90-ffffffff814c0f2d: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81521640)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff81521640-ffffffff815217d1: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8153e4b0)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff8153e4b0-ffffffff8153e641: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81546b90)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff81546b90-ffffffff81546cff: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff815a7370)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff815a7370-ffffffff815a74df: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8164e6c0)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff8164e6c0-ffffffff8164e865: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81707b20)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff81707b20-ffffffff81707cc5: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81741290)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff81741290-ffffffff817413f0: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81782130)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/scatterwalk.c:scatterwalk_map_and_copy
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_next_slow
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff81782130-ffffffff81782290: scatterwalk_copychunks (STB_GLOBAL)
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
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffff8000105baff0)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffff8000105baff0-ffff8000105bb1ac: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (c076930c)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
c076930c-c07694b4: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (c0000000007416c0)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
c0000000007416c0-c000000000741908: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffe000400b2a)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffe000400b2a-ffffffe000400c6e: scatterwalk_copychunks (STB_GLOBAL)
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
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814b9370)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff814b9370-ffffffff814b950d: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814a9d90)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff814a9d90-ffffffff814a9f2d: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814b5400)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff814b5400-ffffffff814b559d: scatterwalk_copychunks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scatterwalk_copychunks(void *buf, struct scatter_walk *walk, size_t nbytes, int out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814cde80)
Location: crypto/scatterwalk.c:26
Inline: False
Direct callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:__ablkcipher_walk_complete
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_aead_common
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_complete
  - crypto/skcipher.c:skcipher_walk_done
```
**Symbols:**

```
ffffffff814cde80-ffffffff814ce03f: scatterwalk_copychunks (STB_GLOBAL)
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
