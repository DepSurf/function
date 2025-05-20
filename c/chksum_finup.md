# Function: <code>chksum_finup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff813ab800)
Location: crypto/crc32c_generic.c:112
Inline: False
```
**Symbols:**

```
ffffffff813ab800-ffffffff813ab820: chksum_finup (STB_LOCAL)
ffffffff813ab910-ffffffff813ab930: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff813eb060)
Location: crypto/crc32c_generic.c:112
Inline: False
```
```
In crypto/crct10dif_generic.c (0)
Location: crypto/crct10dif_generic.c:75
Inline: False
```
**Symbols:**

```
ffffffff813eb060-ffffffff813eb080: chksum_finup (STB_LOCAL)
ffffffff813eb170-ffffffff813eb190: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff81404690)
Location: crypto/crc32c_generic.c:112
Inline: False
```
```
In crypto/crct10dif_generic.c (0)
Location: crypto/crct10dif_generic.c:75
Inline: False
```
**Symbols:**

```
ffffffff81404690-ffffffff814046b0: chksum_finup (STB_LOCAL)
ffffffff814047a0-ffffffff814047c0: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff81411dd0)
Location: crypto/crc32c_generic.c:112
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff81411e90)
Location: crypto/crct10dif_generic.c:75
Inline: True
```
**Symbols:**

```
ffffffff81411dd0-ffffffff81411df0: chksum_finup (STB_LOCAL)
ffffffff81411e90-ffffffff81411eb0: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff8143c540)
Location: crypto/crc32c_generic.c:112
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff8143c600)
Location: crypto/crct10dif_generic.c:75
Inline: True
```
**Symbols:**

```
ffffffff8143c540-ffffffff8143c560: chksum_finup (STB_LOCAL)
ffffffff8143c600-ffffffff8143c620: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff8146f380)
Location: crypto/crc32c_generic.c:113
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff8146f440)
Location: crypto/crct10dif_generic.c:75
Inline: True
```
**Symbols:**

```
ffffffff8146f380-ffffffff8146f3a0: chksum_finup (STB_LOCAL)
ffffffff8146f440-ffffffff8146f460: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff8148cd30)
Location: crypto/crc32c_generic.c:113
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff8148cdf0)
Location: crypto/crct10dif_generic.c:75
Inline: True
```
**Symbols:**

```
ffffffff8148cd30-ffffffff8148cd50: chksum_finup (STB_LOCAL)
ffffffff8148cdf0-ffffffff8148ce10: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff814ba420)
Location: crypto/crc32c_generic.c:108
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff814ba500)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
ffffffff814ba420-ffffffff814ba440: chksum_finup (STB_LOCAL)
ffffffff814ba500-ffffffff814ba520: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff814d31f0)
Location: crypto/crc32c_generic.c:108
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff814d32d0)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
ffffffff814d31f0-ffffffff814d3210: chksum_finup (STB_LOCAL)
ffffffff814d32d0-ffffffff814d32f0: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff81532470)
Location: crypto/crc32c_generic.c:106
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff81532580)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
ffffffff81532470-ffffffff81532493: chksum_finup (STB_LOCAL)
ffffffff81532580-ffffffff815325a3: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff8154f3c0)
Location: crypto/crc32c_generic.c:106
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff8154f4d0)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
ffffffff8154f3c0-ffffffff8154f3e3: chksum_finup (STB_LOCAL)
ffffffff8154f4d0-ffffffff8154f4f3: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff81557c30)
Location: crypto/crc32c_generic.c:106
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff81557d40)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
ffffffff81557c30-ffffffff81557c53: chksum_finup (STB_LOCAL)
ffffffff81557d40-ffffffff81557d63: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff815b8ee0)
Location: crypto/crc32c_generic.c:106
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff815b8ff0)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
ffffffff815b8ee0-ffffffff815b8f03: chksum_finup (STB_LOCAL)
ffffffff815b8ff0-ffffffff815b9013: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff816622a0)
Location: crypto/crc32c_generic.c:106
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff816623c0)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
```
In crypto/crc64_rocksoft_generic.c (ffffffff81662490)
Location: crypto/crc64_rocksoft_generic.c:42
Inline: False
```
**Symbols:**

```
ffffffff816622a0-ffffffff816622cf: chksum_finup (STB_LOCAL)
ffffffff816623c0-ffffffff816623ef: chksum_finup (STB_LOCAL)
ffffffff81662490-ffffffff816624bf: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff8171c270)
Location: crypto/crc32c_generic.c:106
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff8171c3f0)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
```
In crypto/crc64_rocksoft_generic.c (ffffffff8171c510)
Location: crypto/crc64_rocksoft_generic.c:42
Inline: False
```
**Symbols:**

```
ffffffff8171c270-ffffffff8171c29f: chksum_finup (STB_LOCAL)
ffffffff8171c3f0-ffffffff8171c41f: chksum_finup (STB_LOCAL)
ffffffff8171c510-ffffffff8171c53f: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff81757a10)
Location: crypto/crc32c_generic.c:106
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff81757b90)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
```
In crypto/crc64_rocksoft_generic.c (ffffffff81757cb0)
Location: crypto/crc64_rocksoft_generic.c:42
Inline: False
```
**Symbols:**

```
ffffffff81757a10-ffffffff81757a3f: chksum_finup (STB_LOCAL)
ffffffff81757b90-ffffffff81757bbf: chksum_finup (STB_LOCAL)
ffffffff81757cb0-ffffffff81757cdf: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff81799910)
Location: crypto/crc32c_generic.c:106
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff81799a90)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
```
In crypto/crc64_rocksoft_generic.c (ffffffff81799bb0)
Location: crypto/crc64_rocksoft_generic.c:42
Inline: False
```
**Symbols:**

```
ffffffff81799910-ffffffff8179993f: chksum_finup (STB_LOCAL)
ffffffff81799a90-ffffffff81799abf: chksum_finup (STB_LOCAL)
ffffffff81799bb0-ffffffff81799bdf: chksum_finup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffff8000105cf848)
Location: crypto/crc32c_generic.c:108
Inline: False
```
```
In crypto/crct10dif_generic.c (ffff8000105cfa18)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
ffff8000105cf848-ffff8000105cf89c: chksum_finup (STB_LOCAL)
ffff8000105cfa18-ffff8000105cfa6c: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (c077d530)
Location: crypto/crc32c_generic.c:108
Inline: False
```
```
In crypto/crct10dif_generic.c (c077d65c)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
c077d530-c077d560: chksum_finup (STB_LOCAL)
c077d65c-c077d68c: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (c00000000075b870)
Location: crypto/crc32c_generic.c:108
Inline: False
```
```
In crypto/crct10dif_generic.c (c00000000075ba60)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
c00000000075b870-c00000000075b8c4: chksum_finup (STB_LOCAL)
c00000000075ba60-c00000000075bab0: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffe000414790)
Location: crypto/crc32c_generic.c:108
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffe00041493e)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
ffffffe000414790-ffffffe0004147fa: chksum_finup (STB_LOCAL)
ffffffe00041493e-ffffffe00041498a: chksum_finup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff814cb7d0)
Location: crypto/crc32c_generic.c:108
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff814cb8b0)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
ffffffff814cb7d0-ffffffff814cb7f0: chksum_finup (STB_LOCAL)
ffffffff814cb8b0-ffffffff814cb8d0: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff814bc1f0)
Location: crypto/crc32c_generic.c:108
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff814bc2d0)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
ffffffff814bc1f0-ffffffff814bc210: chksum_finup (STB_LOCAL)
ffffffff814bc2d0-ffffffff814bc2f0: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff814c7860)
Location: crypto/crc32c_generic.c:108
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff814c7940)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
ffffffff814c7860-ffffffff814c7880: chksum_finup (STB_LOCAL)
ffffffff814c7940-ffffffff814c7960: chksum_finup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
int chksum_finup(struct shash_desc *desc, const u8 *data, unsigned int len, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff814e0330)
Location: crypto/crc32c_generic.c:108
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff814e0410)
Location: crypto/crct10dif_generic.c:74
Inline: False
```
**Symbols:**

```
ffffffff814e0330-ffffffff814e0350: chksum_finup (STB_LOCAL)
ffffffff814e0410-ffffffff814e0430: chksum_finup (STB_LOCAL)
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
