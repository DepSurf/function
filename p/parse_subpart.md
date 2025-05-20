# Function: <code>parse_subpart</code>

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
In block/cmdline-parser.c (ffffffff813e6bda)
Location: block/cmdline-parser.c:10
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
In block/cmdline-parser.c (ffffffff8142ce67)
Location: block/cmdline-parser.c:10
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
In block/cmdline-parser.c (ffffffff81446c67)
Location: block/cmdline-parser.c:10
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
In block/cmdline-parser.c (ffffffff81455177)
Location: block/cmdline-parser.c:10
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
In block/cmdline-parser.c (ffffffff81480e07)
Location: block/cmdline-parser.c:11
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
In block/cmdline-parser.c (ffffffff814b5ae0)
Location: block/cmdline-parser.c:11
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
In block/cmdline-parser.c (ffffffff814c9350)
Location: block/cmdline-parser.c:11
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
In block/cmdline-parser.c (ffffffff814f7bcd)
Location: block/cmdline-parser.c:11
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
In block/cmdline-parser.c (ffffffff81515a5d)
Location: block/cmdline-parser.c:11
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
int parse_subpart(struct cmdline_subpart **subpart, char *partdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/cmdline-parser.c (0)
Location: block/cmdline-parser.c:11
Inline: False
Direct callers:
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_parts
```
**Symbols:**

```
ffffffff81575f70-ffffffff815760e2: parse_subpart (STB_LOCAL)
ffffffff815763be-ffffffff815763ea: parse_subpart.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int parse_subpart(struct cmdline_subpart **subpart, char *partdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/cmdline-parser.c (0)
Location: block/cmdline-parser.c:11
Inline: False
Direct callers:
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_parts
```
**Symbols:**

```
ffffffff81592d80-ffffffff81592efc: parse_subpart (STB_LOCAL)
ffffffff81bf3bdb-ffffffff81bf3c13: parse_subpart.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int parse_subpart(struct cmdline_subpart **subpart, char *partdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/cmdline-parser.c (0)
Location: block/cmdline-parser.c:11
Inline: False
Direct callers:
  - block/cmdline-parser.c:parse_parts
  - block/cmdline-parser.c:parse_parts
```
**Symbols:**

```
ffffffff81599b30-ffffffff81599cab: parse_subpart (STB_LOCAL)
ffffffff81be5a3b-ffffffff81be5a73: parse_subpart.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int parse_subpart(struct cmdline_subpart **subpart, char *partdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/cmdline.c (0)
Location: block/partitions/cmdline.c:42
Inline: False
Direct callers:
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
```
**Symbols:**

```
ffffffff815e8470-ffffffff815e8602: parse_subpart (STB_LOCAL)
ffffffff81cd8f35-ffffffff81cd8f6d: parse_subpart.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int parse_subpart(struct cmdline_subpart **subpart, char *partdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/cmdline.c (0)
Location: block/partitions/cmdline.c:42
Inline: False
Direct callers:
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
```
**Symbols:**

```
ffffffff81697b50-ffffffff81697cf0: parse_subpart (STB_LOCAL)
ffffffff81e8ca28-ffffffff81e8ca60: parse_subpart.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_subpart(struct cmdline_subpart **subpart, char *partdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/cmdline.c (ffffffff81756a10)
Location: block/partitions/cmdline.c:42
Inline: False
Direct callers:
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
```
**Symbols:**

```
ffffffff81756a10-ffffffff81756be0: parse_subpart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_subpart(struct cmdline_subpart **subpart, char *partdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/cmdline.c (ffffffff81793be0)
Location: block/partitions/cmdline.c:42
Inline: False
Direct callers:
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_parts
```
**Symbols:**

```
ffffffff81793be0-ffffffff81793db0: parse_subpart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_subpart(struct cmdline_subpart **subpart, char *partdef);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/cmdline.c (ffffffff817d7500)
Location: block/partitions/cmdline.c:42
Inline: False
Direct callers:
  - block/partitions/cmdline.c:parse_parts
```
**Symbols:**

```
ffffffff817d7500-ffffffff817d7713: parse_subpart (STB_LOCAL)
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
In block/cmdline-parser.c (ffff80001061cbf8)
Location: block/cmdline-parser.c:11
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
In block/cmdline-parser.c (c07c487c)
Location: block/cmdline-parser.c:11
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
In block/cmdline-parser.c (c0000000007bb788)
Location: block/cmdline-parser.c:11
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
In block/cmdline-parser.c (ffffffe00044fa44)
Location: block/cmdline-parser.c:11
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
In block/cmdline-parser.c (ffffffff8150e03d)
Location: block/cmdline-parser.c:11
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
In block/cmdline-parser.c (ffffffff814fe46d)
Location: block/cmdline-parser.c:11
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
In block/cmdline-parser.c (ffffffff8150a0cd)
Location: block/cmdline-parser.c:11
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
In block/cmdline-parser.c (ffffffff8152373d)
Location: block/cmdline-parser.c:11
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
