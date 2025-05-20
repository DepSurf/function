# Function: <code>sg_kfree</code>

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
In lib/scatterlist.c (ffffffff813fa0e1)
Location: lib/scatterlist.c:183
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
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
In lib/scatterlist.c (ffffffff81441131)
Location: lib/scatterlist.c:183
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
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
In lib/scatterlist.c (ffffffff8145e2d1)
Location: lib/scatterlist.c:183
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
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
In lib/scatterlist.c (ffffffff81463541)
Location: lib/scatterlist.c:183
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
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
In lib/scatterlist.c (ffffffff8148f451)
Location: lib/scatterlist.c:183
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sg_kfree(struct scatterlist *sg, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c4030)
Location: lib/scatterlist.c:171
Inline: False
```
**Symbols:**

```
ffffffff814c4030-ffffffff814c404c: sg_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sg_kfree(struct scatterlist *sg, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8730)
Location: lib/scatterlist.c:171
Inline: False
```
**Symbols:**

```
ffffffff814d8730-ffffffff814d874c: sg_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sg_kfree(struct scatterlist *sg, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815045b0)
Location: lib/scatterlist.c:169
Inline: False
```
**Symbols:**

```
ffffffff815045b0-ffffffff815045cc: sg_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sg_kfree(struct scatterlist *sg, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522620)
Location: lib/scatterlist.c:169
Inline: False
```
**Symbols:**

```
ffffffff81522620-ffffffff8152263c: sg_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815864c6)
Location: lib/scatterlist.c:169
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_free_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a2f01)
Location: lib/scatterlist.c:169
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
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
In lib/scatterlist.c (ffffffff815a9e31)
Location: lib/scatterlist.c:169
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
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
In lib/scatterlist.c (ffffffff816137b2)
Location: lib/scatterlist.c:169
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
  - lib/scatterlist.c:sg_alloc_table
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
In lib/scatterlist.c (ffffffff816e0023)
Location: lib/scatterlist.c:169
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_alloc_table
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
In lib/scatterlist.c (ffffffff817d04f0)
Location: lib/scatterlist.c:169
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_free_append_table
  - lib/scatterlist.c:sg_free_append_table
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
In lib/scatterlist.c (ffffffff8180f140)
Location: lib/scatterlist.c:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_free_append_table
  - lib/scatterlist.c:sg_free_append_table
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
In lib/scatterlist.c (ffffffff81854dc0)
Location: lib/scatterlist.c:171
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_free_append_table
  - lib/scatterlist.c:sg_free_append_table
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
void sg_kfree(struct scatterlist *sg, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c278)
Location: lib/scatterlist.c:169
Inline: False
```
**Symbols:**

```
ffff80001062c278-ffff80001062c2a4: sg_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sg_kfree(struct scatterlist *sg, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d2c0c)
Location: lib/scatterlist.c:169
Inline: False
```
**Symbols:**

```
c07d2c0c-c07d2c34: sg_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sg_kfree(struct scatterlist *sg, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007cec40)
Location: lib/scatterlist.c:169
Inline: False
```
**Symbols:**

```
c0000000007cec40-c0000000007cec9c: sg_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sg_kfree(struct scatterlist *sg, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c488)
Location: lib/scatterlist.c:169
Inline: False
```
**Symbols:**

```
ffffffe00045c488-ffffffe00045c4ba: sg_kfree (STB_LOCAL)
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
void sg_kfree(struct scatterlist *sg, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151ac00)
Location: lib/scatterlist.c:169
Inline: False
```
**Symbols:**

```
ffffffff8151ac00-ffffffff8151ac1c: sg_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sg_kfree(struct scatterlist *sg, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150aef0)
Location: lib/scatterlist.c:169
Inline: False
```
**Symbols:**

```
ffffffff8150aef0-ffffffff8150af0c: sg_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sg_kfree(struct scatterlist *sg, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81516c90)
Location: lib/scatterlist.c:169
Inline: False
```
**Symbols:**

```
ffffffff81516c90-ffffffff81516cac: sg_kfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sg_kfree(struct scatterlist *sg, unsigned int nents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530420)
Location: lib/scatterlist.c:169
Inline: False
```
**Symbols:**

```
ffffffff81530420-ffffffff8153043c: sg_kfree (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
