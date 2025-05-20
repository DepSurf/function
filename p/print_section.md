# Function: <code>print_section</code>

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
In mm/slub.c (ffffffff811e80d9)
Location: mm/slub.c:492
Inline: True
Inline callers:
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:free_debug_processing
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
In mm/slub.c (ffffffff812092f3)
Location: mm/slub.c:503
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff8121b369)
Location: mm/slub.c:499
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff81226d99)
Location: mm/slub.c:501
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff81241dd1)
Location: mm/slub.c:536
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff8126b0e4)
Location: mm/slub.c:521
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff8127f9a8)
Location: mm/slub.c:526
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff8129b884)
Location: mm/slub.c:527
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff812ab710)
Location: mm/slub.c:527
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_section(char *level, char *text, u8 *addr, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812df831)
Location: mm/slub.c:545
Inline: False
Direct callers:
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff812df831-ffffffff812df85b: print_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_section(char *level, char *text, u8 *addr, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81be8fe0)
Location: mm/slub.c:539
Inline: False
Direct callers:
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81be8fe0-ffffffff81be900a: print_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void print_section(char *level, char *text, u8 *addr, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81bdb137)
Location: mm/slub.c:550
Inline: False
Direct callers:
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81bdb137-ffffffff81bdb161: print_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void print_section(char *level, char *text, u8 *addr, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81cc0c8b)
Location: mm/slub.c:661
Inline: False
Direct callers:
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81cc0c8b-ffffffff81cc0cb5: print_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void print_section(char *level, char *text, u8 *addr, unsigned int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81e730be)
Location: mm/slub.c:690
Inline: False
Direct callers:
  - mm/slub.c:slab_pad_check
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
```
**Symbols:**

```
ffffffff81e730be-ffffffff81e730fc: print_section (STB_LOCAL)
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
In mm/slub.c (ffffffff8142b632)
Location: mm/slub.c:705
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:slab_pad_check
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff81460ba2)
Location: mm/slub.c:726
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:slab_pad_check
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff81458b62)
Location: mm/slub.c:839
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:slab_pad_check
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffff800010349b64)
Location: mm/slub.c:527
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (c054dc5c)
Location: mm/slub.c:527
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (c000000000428a44)
Location: mm/slub.c:527
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffe00023b772)
Location: mm/slub.c:527
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff812a3cf0)
Location: mm/slub.c:527
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff812957c0)
Location: mm/slub.c:527
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff812a1b00)
Location: mm/slub.c:527
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
In mm/slub.c (ffffffff812b1d33)
Location: mm/slub.c:527
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
  - mm/slub.c:print_trailer
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
