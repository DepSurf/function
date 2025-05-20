# Function: <code>rc_bit_tree_decode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/decompress_unlzma.c (ffffffff81f9d8df)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/decompress_unlzma.c (ffffffff81fc8cc7)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/decompress_unlzma.c (ffffffff82005c20)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
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
In lib/decompress_unlzma.c (ffffffff82110d1c)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
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
In lib/decompress_unlzma.c (ffffffff8271b122)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
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
In lib/decompress_unlzma.c (ffffffff82745957)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
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
In lib/decompress_unlzma.c (ffffffff828ffc7d)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:unlzma
  - lib/decompress_unlzma.c:unlzma
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
In lib/decompress_unlzma.c (ffffffff8291c485)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
In lib/decompress_unlzma.c (ffffffff8292630b)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rc_bit_tree_decode(struct rc *rc, uint16_t *p, int num_levels, int *symbol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unlzma.c (ffffffff82d0bda9)
Location: lib/decompress_unlzma.c:201
Inline: False
Direct callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
```
**Symbols:**

```
ffffffff82d0bda9-ffffffff82d0be02: rc_bit_tree_decode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rc_bit_tree_decode(struct rc *rc, uint16_t *p, int num_levels, int *symbol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unlzma.c (ffffffff82ff937f)
Location: lib/decompress_unlzma.c:201
Inline: False
Direct callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
```
**Symbols:**

```
ffffffff82ff937f-ffffffff82ff93d8: rc_bit_tree_decode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rc_bit_tree_decode(struct rc *rc, uint16_t *p, int num_levels, int *symbol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unlzma.c (ffffffff83203f9b)
Location: lib/decompress_unlzma.c:201
Inline: False
Direct callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
```
**Symbols:**

```
ffffffff83203f9b-ffffffff83203ff4: rc_bit_tree_decode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rc_bit_tree_decode(struct rc *rc, uint16_t *p, int num_levels, int *symbol);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unlzma.c (ffffffff832ebcae)
Location: lib/decompress_unlzma.c:201
Inline: False
Direct callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
```
**Symbols:**

```
ffffffff832ebcae-ffffffff832ebd07: rc_bit_tree_decode (STB_LOCAL)
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
In lib/decompress_unlzma.c (ffffffff834a3a7f)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
In lib/decompress_unlzma.c (ffffffff83f19f4d)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
In lib/decompress_unlzma.c (ffffffff837407aa)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
In lib/decompress_unlzma.c (ffffffff8397525a)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
In lib/decompress_unlzma.c (ffff8000114b758c)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
In lib/decompress_unlzma.c (c15bcab0)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
In lib/decompress_unlzma.c (c0000000013ca03c)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
In lib/decompress_unlzma.c (ffffffe0000460e4)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
In lib/decompress_unlzma.c (ffffffff8290b00f)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
In lib/decompress_unlzma.c (ffffffff8290335d)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
In lib/decompress_unlzma.c (ffffffff82920959)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
In lib/decompress_unlzma.c (ffffffff8292737d)
Location: lib/decompress_unlzma.c:201
Inline: True
Inline callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
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
</ul>
