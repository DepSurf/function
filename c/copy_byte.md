# Function: <code>copy_byte</code>

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
In lib/decompress_unlzma.c (ffffffff81f9d6d9)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff81fc8aa4)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff820059fd)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff82110b0b)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff8271af11)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff82745745)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff828ffa6b)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff8291c22f)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff829260cf)
Location: lib/decompress_unlzma.c:330
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
int copy_byte(struct writer *wr, uint32_t offs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unlzma.c (ffffffff82d0be9c)
Location: lib/decompress_unlzma.c:330
Inline: False
Direct callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
```
**Symbols:**

```
ffffffff82d0be9c-ffffffff82d0beaf: copy_byte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_byte(struct writer *wr, uint32_t offs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unlzma.c (ffffffff82ff9472)
Location: lib/decompress_unlzma.c:330
Inline: False
Direct callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
```
**Symbols:**

```
ffffffff82ff9472-ffffffff82ff9485: copy_byte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_byte(struct writer *wr, uint32_t offs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unlzma.c (ffffffff8320408e)
Location: lib/decompress_unlzma.c:330
Inline: False
Direct callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
```
**Symbols:**

```
ffffffff8320408e-ffffffff832040a1: copy_byte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_byte(struct writer *wr, uint32_t offs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unlzma.c (ffffffff832ebc9b)
Location: lib/decompress_unlzma.c:330
Inline: False
Direct callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
```
**Symbols:**

```
ffffffff832ebc9b-ffffffff832ebcae: copy_byte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_byte(struct writer *wr, uint32_t offs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unlzma.c (ffffffff834a3794)
Location: lib/decompress_unlzma.c:330
Inline: False
Direct callers:
  - lib/decompress_unlzma.c:process_bit1
  - lib/decompress_unlzma.c:process_bit1
```
**Symbols:**

```
ffffffff834a3794-ffffffff834a37b7: copy_byte (STB_LOCAL)
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
In lib/decompress_unlzma.c (ffffffff83f19e94)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff837406f4)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff839751a4)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffff8000114b736c)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (c15bc8f0)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (c0000000013c9de0)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffe000045f04)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff8290add3)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff82903121)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff8292071d)
Location: lib/decompress_unlzma.c:330
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
In lib/decompress_unlzma.c (ffffffff82927141)
Location: lib/decompress_unlzma.c:330
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
