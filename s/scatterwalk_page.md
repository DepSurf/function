# Function: <code>scatterwalk_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8139e76c)
Location: include/crypto/scatterwalk.h:76
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (0)
Location: include/crypto/scatterwalk.h:76
Inline: True
```
```
In crypto/blkcipher.c (ffffffff813a1584)
Location: include/crypto/scatterwalk.h:76
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff813db706)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff813dce9f)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff813dd5f1)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff813f3044)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff813f476d)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff813f4ec1)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff813f6403)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff813ff3ab)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff81400ab1)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814011fd)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff81402827)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81427958)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814290b1)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff8142980d)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8142ae97)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8145a7b8)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff8145be5d)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff8145c7dc)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8145dbc5)
Location: include/crypto/scatterwalk.h:72
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81478328)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff8147975d)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff81479e4c)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff8147b465)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814a616b)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814a73fd)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814a7ce4)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814a96d6)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814c0dfb)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814c206d)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814c2944)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814c43c6)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff815216a5)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81523320)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8153e515)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81540270)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81546bea)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81548767)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff815a73ca)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff815a8f47)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8164e71c)
Location: include/crypto/scatterwalk.h:55
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81650533)
Location: include/crypto/scatterwalk.h:55
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff81707b7c)
Location: include/crypto/scatterwalk.h:49
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81709cd3)
Location: include/crypto/scatterwalk.h:49
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff817412dd)
Location: include/crypto/scatterwalk.h:49
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff817438e3)
Location: include/crypto/scatterwalk.h:49
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff8178217d)
Location: include/crypto/scatterwalk.h:49
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81785c13)
Location: include/crypto/scatterwalk.h:49
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_next_copy
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffff8000105bb08c)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffff8000105bc960)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffff8000105bd178)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffff8000105bf054)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (c0769378)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (c076a5f0)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (c076af84)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c076c874)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (c000000000741778)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (c000000000743404)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (c000000000744114)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c00000000074685c)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffe000400bc0)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffe0004021aa)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffe000402884)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffe000404294)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814b93db)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814ba64d)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814baf24)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814bc9a6)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814a9dfb)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814ab06d)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814ab944)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814ad3c6)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814b546b)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814b66dd)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814b6fb4)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814b8a36)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scatterwalk.c (ffffffff814cdeeb)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffffffff814cf17d)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_next
  - crypto/ablkcipher.c:ablkcipher_walk_next
```
```
In crypto/blkcipher.c (ffffffff814cfa44)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffffffff814d14f6)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_next
  - crypto/skcipher.c:skcipher_walk_done
```
</details>
</li>
</ul>

## Differences
