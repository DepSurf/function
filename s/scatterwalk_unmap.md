# Function: <code>scatterwalk_unmap</code>

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
In crypto/scatterwalk.c (ffffffff8139e925)
Location: include/crypto/scatterwalk.h:81
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff813a119d)
Location: include/crypto/scatterwalk.h:81
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff813db6c7)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff813dd656)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff813f3006)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff813f4f20)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff813ff371)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff81401251)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814279d4)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff81429861)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff8145a834)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff8145c978)
Location: include/crypto/scatterwalk.h:77
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814783a4)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff81479fe8)
Location: include/crypto/scatterwalk.h:64
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814a61e4)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814a7eb0)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814c0e74)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814c2b10)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff8152171e)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
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
In crypto/scatterwalk.c (ffffffff8153e58e)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
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
In crypto/scatterwalk.c (ffffffff81546c5b)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
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
In crypto/scatterwalk.c (ffffffff815a743b)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
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
In crypto/scatterwalk.c (ffffffff8164e791)
Location: include/crypto/scatterwalk.h:60
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
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
In crypto/scatterwalk.c (ffffffff81707bf1)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
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
In crypto/scatterwalk.c (ffffffff81741340)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81743389)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
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
In crypto/scatterwalk.c (ffffffff817821e0)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/skcipher.c (ffffffff81785689)
Location: include/crypto/scatterwalk.h:54
Inline: True
Inline callers:
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
In crypto/scatterwalk.c (ffff8000105bb0d4)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffff8000105bd2d4)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (c07693b4)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (c076b09c)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (c0000000007417d8)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (c000000000744384)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffe000400c06)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffe000402a50)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814b9454)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814bb0f0)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814a9e74)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814abb10)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814b54e4)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814b7180)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
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
In crypto/scatterwalk.c (ffffffff814cdf6f)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/blkcipher.c (ffffffff814cfc28)
Location: include/crypto/scatterwalk.h:59
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_next
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
  - crypto/blkcipher.c:blkcipher_walk_done
```
</details>
</li>
</ul>

## Differences
