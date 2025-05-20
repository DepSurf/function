# Function: <code>bitmap_parse_region</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503bb3)
Location: lib/bitmap.c:558
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
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
In lib/bitmap.c (ffffffff81521b53)
Location: lib/bitmap.c:578
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *bitmap_parse_region(const char *str, struct region *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584f20)
Location: lib/bitmap.c:574
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff81584f20-ffffffff81585130: bitmap_parse_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *bitmap_parse_region(const char *str, struct region *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a2020)
Location: lib/bitmap.c:574
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff815a2020-ffffffff815a2230: bitmap_parse_region (STB_LOCAL)
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
In lib/bitmap.c (ffffffff815a8fdb)
Location: lib/bitmap.c:580
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *bitmap_parse_region(const char *str, struct region *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81612060)
Location: lib/bitmap.c:701
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parselist
```
**Symbols:**

```
ffffffff81612060-ffffffff816122fa: bitmap_parse_region (STB_LOCAL)
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
In lib/bitmap.c (ffffffff816de49f)
Location: lib/bitmap.c:717
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
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
In lib/bitmap.c (ffffffff817ce79f)
Location: lib/bitmap.c:728
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
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
In lib/bitmap.c (ffffffff8180cc51)
Location: lib/bitmap.c:728
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
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
In lib/bitmap-str.c (ffffffff818618a1)
Location: lib/bitmap-str.c:295
Inline: True
Inline callers:
  - lib/bitmap-str.c:bitmap_parselist
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
In lib/bitmap.c (ffff80001062b3b8)
Location: lib/bitmap.c:578
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
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
In lib/bitmap.c (c07d264c)
Location: lib/bitmap.c:578
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
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
In lib/bitmap.c (c0000000007cd930)
Location: lib/bitmap.c:578
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
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
In lib/bitmap.c (ffffffe00045bd68)
Location: lib/bitmap.c:578
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
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
In lib/bitmap.c (ffffffff8151a133)
Location: lib/bitmap.c:578
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
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
In lib/bitmap.c (ffffffff8150a423)
Location: lib/bitmap.c:578
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
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
In lib/bitmap.c (ffffffff815161c3)
Location: lib/bitmap.c:578
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
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
In lib/bitmap.c (ffffffff8152f953)
Location: lib/bitmap.c:578
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_parselist
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
</ul>
