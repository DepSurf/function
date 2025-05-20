# Function: <code>skcipher_next_slow</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813f64d6)
Location: crypto/skcipher.c:218
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814028ef)
Location: crypto/skcipher.c:219
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8142af5f)
Location: crypto/skcipher.c:219
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8145dc99)
Location: crypto/skcipher.c:220
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff8147b539)
Location: crypto/skcipher.c:220
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff814a97b0)
Location: crypto/skcipher.c:220
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff814c44a0)
Location: crypto/skcipher.c:224
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skcipher_next_slow(struct skcipher_walk *walk, unsigned int bsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815237e0)
Location: crypto/skcipher.c:224
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff815237e0-ffffffff81523916: skcipher_next_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skcipher_next_slow(struct skcipher_walk *walk, unsigned int bsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81540730)
Location: crypto/skcipher.c:224
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff81540730-ffffffff81540866: skcipher_next_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skcipher_next_slow(struct skcipher_walk *walk, unsigned int bsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81548d90)
Location: crypto/skcipher.c:225
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff81548d90-ffffffff81548ec4: skcipher_next_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skcipher_next_slow(struct skcipher_walk *walk, unsigned int bsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a9570)
Location: crypto/skcipher.c:225
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff815a9570-ffffffff815a96a4: skcipher_next_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skcipher_next_slow(struct skcipher_walk *walk, unsigned int bsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff816509b0)
Location: crypto/skcipher.c:225
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff816509b0-ffffffff81650ae1: skcipher_next_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skcipher_next_slow(struct skcipher_walk *walk, unsigned int bsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8170a170)
Location: crypto/skcipher.c:225
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff8170a170-ffffffff8170a2a1: skcipher_next_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skcipher_next_slow(struct skcipher_walk *walk, unsigned int bsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff817436d0)
Location: crypto/skcipher.c:243
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff817436d0-ffffffff81743801: skcipher_next_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skcipher_next_slow(struct skcipher_walk *walk, unsigned int bsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81785a00)
Location: crypto/skcipher.c:242
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_next
```
**Symbols:**

```
ffffffff81785a00-ffffffff81785b31: skcipher_next_slow (STB_LOCAL)
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
In crypto/skcipher.c (ffff8000105bf128)
Location: crypto/skcipher.c:224
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (c076c980)
Location: crypto/skcipher.c:224
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (c000000000746968)
Location: crypto/skcipher.c:224
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffe00040434e)
Location: crypto/skcipher.c:224
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff814bca80)
Location: crypto/skcipher.c:224
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff814ad4a0)
Location: crypto/skcipher.c:224
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff814b8b10)
Location: crypto/skcipher.c:224
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
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
In crypto/skcipher.c (ffffffff814d15d0)
Location: crypto/skcipher.c:224
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_next
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
