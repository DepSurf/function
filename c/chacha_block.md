# Function: <code>chacha_block</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void chacha_block(u32 *state, u8 *stream, int nrounds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha.c (ffffffff81a06eb0)
Location: lib/chacha.c:79
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff81a06eb0-ffffffff81a06f52: chacha_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void chacha_block(u32 *state, u8 *stream, int nrounds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha.c (ffffffff81a76820)
Location: lib/chacha.c:75
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff81a76820-ffffffff81a768c2: chacha_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void chacha_block(u32 *state, u8 *stream, int nrounds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha.c (ffffffff81aadc30)
Location: lib/chacha.c:75
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff81aadc30-ffffffff81aadcd2: chacha_block (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void chacha_block(u32 *state, u8 *stream, int nrounds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha.c (ffff800010d83ea8)
Location: lib/chacha.c:75
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffff800010d83ea8-ffff800010d83f60: chacha_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void chacha_block(u32 *state, u8 *stream, int nrounds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha.c (c0e7f338)
Location: lib/chacha.c:75
Inline: False
```
**Symbols:**

```
c0e7f338-c0e7f400: chacha_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void chacha_block(u32 *state, u8 *stream, int nrounds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha.c (c000000000ec2dd0)
Location: lib/chacha.c:75
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
c000000000ec2dd0-c000000000ec2eb4: chacha_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void chacha_block(u32 *state, u8 *stream, int nrounds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha.c (ffffffe0008ae5d6)
Location: lib/chacha.c:75
Inline: False
```
**Symbols:**

```
ffffffe0008ae5d6-ffffffe0008ae65a: chacha_block (STB_GLOBAL)
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
void chacha_block(u32 *state, u8 *stream, int nrounds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha.c (ffffffff81a4ca80)
Location: lib/chacha.c:75
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff81a4ca80-ffffffff81a4cb22: chacha_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void chacha_block(u32 *state, u8 *stream, int nrounds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha.c (ffffffff81a09bb0)
Location: lib/chacha.c:75
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff81a09bb0-ffffffff81a09c52: chacha_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void chacha_block(u32 *state, u8 *stream, int nrounds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha.c (ffffffff81ab8e70)
Location: lib/chacha.c:75
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff81ab8e70-ffffffff81ab8f12: chacha_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void chacha_block(u32 *state, u8 *stream, int nrounds);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/chacha.c (ffffffff81ac52c0)
Location: lib/chacha.c:75
Inline: False
Direct callers:
  - drivers/char/random.c:_extract_crng
```
**Symbols:**

```
ffffffff81ac52c0-ffffffff81ac5362: chacha_block (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
