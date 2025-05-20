# Function: <code>sg_nents</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813f9d80)
Location: lib/scatterlist.c:50
Inline: False
Direct callers:
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
```
**Symbols:**

```
ffffffff813f9d80-ffffffff813f9db2: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81440dc0)
Location: lib/scatterlist.c:50
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff81440dc0-ffffffff81440e01: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145dfe0)
Location: lib/scatterlist.c:50
Inline: False
Direct callers:
  - crypto/scompress.c:crypto_scomp_sg_free
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff8145dfe0-ffffffff8145e021: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814632e0)
Location: lib/scatterlist.c:50
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff814632e0-ffffffff81463321: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148f1f0)
Location: lib/scatterlist.c:50
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff8148f1f0-ffffffff8148f231: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c3e10)
Location: lib/scatterlist.c:47
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff814c3e10-ffffffff814c3e47: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8500)
Location: lib/scatterlist.c:47
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff814d8500-ffffffff814d8537: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81504310)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff81504310-ffffffff81504341: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522320)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff81522320-ffffffff81522351: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81585680)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff81585680-ffffffff815856b1: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a2780)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff815a2780-ffffffff815a27b1: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a96b0)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff815a96b0-ffffffff815a96e1: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81612830)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff81612830-ffffffff81612861: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816decd0)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff816decd0-ffffffff816ded08: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817cee80)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff817cee80-ffffffff817ceeb8: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180d330)
Location: lib/scatterlist.c:47
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff8180d330-ffffffff8180d368: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81852fe0)
Location: lib/scatterlist.c:47
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff81852fe0-ffffffff81853018: sg_nents (STB_GLOBAL)
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
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062bf10)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - lib/sg_split.c:sg_split
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffff80001062bf10-ffff80001062bf48: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d295c)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - lib/sg_split.c:sg_split
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
c07d295c-c07d29ac: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007ce6a0)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
c0000000007ce6a0-c0000000007ce6ec: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c12e)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffe00045c12e-ffffffe00045c160: sg_nents (STB_GLOBAL)
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
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151a900)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff8151a900-ffffffff8151a931: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150abf0)
Location: lib/scatterlist.c:45
Inline: False
```
**Symbols:**

```
ffffffff8150abf0-ffffffff8150ac21: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81516990)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff81516990-ffffffff815169c1: sg_nents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sg_nents(struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530120)
Location: lib/scatterlist.c:45
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/base/devcoredump.c:devcd_free_sgtable
```
**Symbols:**

```
ffffffff81530120-ffffffff81530151: sg_nents (STB_GLOBAL)
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
