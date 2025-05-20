# Function: <code>cmdline_parts_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff813e6a30)
Location: block/cmdline-parser.c:150
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff813e6a30-ffffffff813e6a88: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff8142ccc0)
Location: block/cmdline-parser.c:150
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff8142ccc0-ffffffff8142cd18: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff81446ac0)
Location: block/cmdline-parser.c:150
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff81446ac0-ffffffff81446b18: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff81454fc0)
Location: block/cmdline-parser.c:150
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff81454fc0-ffffffff81455018: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff81480c50)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff81480c50-ffffffff81480ca8: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff814b5820)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff814b5820-ffffffff814b5878: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff814c90e0)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff814c90e0-ffffffff814c9138: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff814f7980)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff814f7980-ffffffff814f79d9: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff81515810)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff81515810-ffffffff81515869: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff81576373)
Location: block/cmdline-parser.c:151
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
```
**Symbols:**

```
ffffffff81575f10-ffffffff81575f69: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff81593193)
Location: block/cmdline-parser.c:151
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
```
**Symbols:**

```
ffffffff81592d20-ffffffff81592d79: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff81599f93)
Location: block/cmdline-parser.c:151
Inline: True
Inline callers:
  - block/cmdline-parser.c:cmdline_parts_parse
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
```
**Symbols:**

```
ffffffff81599e80-ffffffff81599ed9: cmdline_parts_free (STB_GLOBAL)
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
In block/partitions/cmdline.c (ffffffff815e8874)
Location: block/partitions/cmdline.c:182
Inline: True
Inline callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:cmdline_partition
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
In block/partitions/cmdline.c (ffffffff81697f84)
Location: block/partitions/cmdline.c:182
Inline: True
Inline callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:cmdline_partition
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
In block/partitions/cmdline.c (ffffffff81756ed4)
Location: block/partitions/cmdline.c:182
Inline: True
Inline callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:cmdline_partition
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
In block/partitions/cmdline.c (ffffffff81794091)
Location: block/partitions/cmdline.c:182
Inline: True
Inline callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:cmdline_partition
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
In block/partitions/cmdline.c (ffffffff817d79f1)
Location: block/partitions/cmdline.c:179
Inline: True
Inline callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/partitions/cmdline.c:cmdline_partition
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffff80001061c9a8)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffff80001061c9a8-ffff80001061ca14: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (c07c4610)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
c07c4610-c07c4678: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (c0000000007bb2f0)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
c0000000007bb2f0-c0000000007bb3a0: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffe00044f908)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffe00044f908-ffffffe00044f968: cmdline_parts_free (STB_GLOBAL)
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
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff8150ddf0)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff8150ddf0-ffffffff8150de49: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff814fe220)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff814fe220-ffffffff814fe279: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff81509e80)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff81509e80-ffffffff81509ed9: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cmdline_parts_free(struct cmdline_parts **parts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/cmdline-parser.c (ffffffff815234f0)
Location: block/cmdline-parser.c:151
Inline: False
Direct callers:
  - block/partitions/cmdline.c:cmdline_partition
  - block/cmdline-parser.c:cmdline_parts_parse
```
**Symbols:**

```
ffffffff815234f0-ffffffff81523549: cmdline_parts_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
