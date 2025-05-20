# Function: <code>parse_parts</code>

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
In block/cmdline-parser.c (ffffffff813e6b55)
Location: block/cmdline-parser.c:89
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffff8142cde2)
Location: block/cmdline-parser.c:89
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffff81446be2)
Location: block/cmdline-parser.c:89
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffff814550f2)
Location: block/cmdline-parser.c:89
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffff81480d82)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffff814b5950)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffff814c91c0)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffff814f7a5f)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffff815158ef)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int parse_parts(struct cmdline_parts **parts, const char *bdevdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/cmdline-parser.c (0)
Location: block/cmdline-parser.c:90
Inline: False
Direct callers:
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff815760f0-ffffffff815762bb: parse_parts (STB_LOCAL)
ffffffff815763ea-ffffffff81576422: parse_parts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int parse_parts(struct cmdline_parts **parts, const char *bdevdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/cmdline-parser.c (0)
Location: block/cmdline-parser.c:90
Inline: False
Direct callers:
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff81592f00-ffffffff815930da: parse_parts (STB_LOCAL)
ffffffff81bf3c13-ffffffff81bf3c4b: parse_parts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int parse_parts(struct cmdline_parts **parts, const char *bdevdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/cmdline-parser.c (0)
Location: block/cmdline-parser.c:90
Inline: False
Direct callers:
  - block/cmdline-parser.c:cmdline_parts_parse
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff81599cb0-ffffffff81599e7c: parse_parts (STB_LOCAL)
ffffffff81be5a73-ffffffff81be5aad: parse_parts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int parse_parts(struct cmdline_parts **parts, const char *bdevdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/cmdline.c (0)
Location: block/partitions/cmdline.c:121
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:cmdline_partition
```
**Symbols:**

```
ffffffff815e8610-ffffffff815e8824: parse_parts (STB_LOCAL)
ffffffff81cd8f6d-ffffffff81cd8fa7: parse_parts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int parse_parts(struct cmdline_parts **parts, const char *bdevdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/cmdline.c (0)
Location: block/partitions/cmdline.c:121
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:cmdline_partition
```
**Symbols:**

```
ffffffff81697cf0-ffffffff81697f3f: parse_parts (STB_LOCAL)
ffffffff81e8ca60-ffffffff81e8ca90: parse_parts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_parts(struct cmdline_parts **parts, const char *bdevdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/cmdline.c (ffffffff81756bf0)
Location: block/partitions/cmdline.c:121
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:cmdline_partition
```
**Symbols:**

```
ffffffff81756bf0-ffffffff81756e77: parse_parts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_parts(struct cmdline_parts **parts, const char *bdevdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/cmdline.c (ffffffff81793dc0)
Location: block/partitions/cmdline.c:121
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:cmdline_partition
```
**Symbols:**

```
ffffffff81793dc0-ffffffff81794047: parse_parts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_parts(struct cmdline_parts **parts, const char *bdevdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/cmdline.c (ffffffff817d7730)
Location: block/partitions/cmdline.c:120
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:cmdline_partition
```
**Symbols:**

```
ffffffff817d7730-ffffffff817d79a2: parse_parts (STB_LOCAL)
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
In block/cmdline-parser.c (ffff80001061caa0)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (c07c4704)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (c0000000007bb5ec)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffe00044f9b6)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffff8150decf)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffff814fe2ff)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffff81509f5f)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
In block/cmdline-parser.c (ffffffff815235cf)
Location: block/cmdline-parser.c:90
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
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
