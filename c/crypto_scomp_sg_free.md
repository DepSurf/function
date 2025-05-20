# Function: <code>crypto_scomp_sg_free</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void crypto_scomp_sg_free(struct scatterlist *sgl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff813fa6b0)
Location: crypto/scompress.c:133
Inline: False
Direct callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
**Symbols:**

```
ffffffff813fa6b0-ffffffff813fa709: crypto_scomp_sg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void crypto_scomp_sg_free(struct scatterlist *sgl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/scompress.c (ffffffff8140763a)
Location: crypto/scompress.c:134
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
Direct callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
**Symbols:**

```
ffffffff81407090-ffffffff814070e7: crypto_scomp_sg_free.part.2 (STB_LOCAL)
ffffffff814070f0-ffffffff81407107: crypto_scomp_sg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void crypto_scomp_sg_free(struct scatterlist *sgl);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/scompress.c (ffffffff8142ff7c)
Location: crypto/scompress.c:143
Inline: True
Inline callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
Direct callers:
  - crypto/scompress.c:scomp_acomp_comp_decomp
```
**Symbols:**

```
ffffffff8142fb40-ffffffff8142fb97: crypto_scomp_sg_free.part.2 (STB_LOCAL)
ffffffff8142fba0-ffffffff8142fbb7: crypto_scomp_sg_free (STB_LOCAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
