# Function: <code>chksum_digest</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff813ab7d0)
Location: crypto/crc32c_generic.c:120
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff813ab8c0)
Location: crypto/crct10dif_generic.c:83
Inline: True
```
**Symbols:**

```
ffffffff813ab7d0-ffffffff813ab7f3: chksum_digest (STB_LOCAL)
ffffffff813ab8c0-ffffffff813ab8e0: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff813eb030)
Location: crypto/crc32c_generic.c:120
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff813eb120)
Location: crypto/crct10dif_generic.c:83
Inline: True
```
**Symbols:**

```
ffffffff813eb030-ffffffff813eb053: chksum_digest (STB_LOCAL)
ffffffff813eb120-ffffffff813eb140: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff81404660)
Location: crypto/crc32c_generic.c:120
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff81404750)
Location: crypto/crct10dif_generic.c:83
Inline: True
```
**Symbols:**

```
ffffffff81404660-ffffffff81404683: chksum_digest (STB_LOCAL)
ffffffff81404750-ffffffff81404770: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff81411da0)
Location: crypto/crc32c_generic.c:120
Inline: False
```
```
In crypto/crct10dif_generic.c (0)
Location: crypto/crct10dif_generic.c:83
Inline: False
```
**Symbols:**

```
ffffffff81411da0-ffffffff81411dc3: chksum_digest (STB_LOCAL)
ffffffff81411ee0-ffffffff81411f00: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff8143c510)
Location: crypto/crc32c_generic.c:120
Inline: False
```
```
In crypto/crct10dif_generic.c (0)
Location: crypto/crct10dif_generic.c:83
Inline: False
```
**Symbols:**

```
ffffffff8143c510-ffffffff8143c533: chksum_digest (STB_LOCAL)
ffffffff8143c650-ffffffff8143c670: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff8146f350)
Location: crypto/crc32c_generic.c:121
Inline: False
```
```
In crypto/crct10dif_generic.c (0)
Location: crypto/crct10dif_generic.c:83
Inline: False
```
**Symbols:**

```
ffffffff8146f350-ffffffff8146f373: chksum_digest (STB_LOCAL)
ffffffff8146f490-ffffffff8146f4b0: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff8148cd00)
Location: crypto/crc32c_generic.c:121
Inline: False
```
```
In crypto/crct10dif_generic.c (0)
Location: crypto/crct10dif_generic.c:83
Inline: False
```
**Symbols:**

```
ffffffff8148cd00-ffffffff8148cd23: chksum_digest (STB_LOCAL)
ffffffff8148ce40-ffffffff8148ce60: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff814ba3f0)
Location: crypto/crc32c_generic.c:116
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff814ba4e0)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
ffffffff814ba3f0-ffffffff814ba413: chksum_digest (STB_LOCAL)
ffffffff814ba4e0-ffffffff814ba4fe: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff814d31c0)
Location: crypto/crc32c_generic.c:116
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff814d32b0)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
ffffffff814d31c0-ffffffff814d31e3: chksum_digest (STB_LOCAL)
ffffffff814d32b0-ffffffff814d32ce: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff81532440)
Location: crypto/crc32c_generic.c:114
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff81532550)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
ffffffff81532440-ffffffff81532466: chksum_digest (STB_LOCAL)
ffffffff81532550-ffffffff81532571: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff8154f390)
Location: crypto/crc32c_generic.c:114
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff8154f4a0)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
ffffffff8154f390-ffffffff8154f3b6: chksum_digest (STB_LOCAL)
ffffffff8154f4a0-ffffffff8154f4c1: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff81557c00)
Location: crypto/crc32c_generic.c:114
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff81557d10)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
ffffffff81557c00-ffffffff81557c26: chksum_digest (STB_LOCAL)
ffffffff81557d10-ffffffff81557d31: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff815b8eb0)
Location: crypto/crc32c_generic.c:114
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff815b8fc0)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
ffffffff815b8eb0-ffffffff815b8ed6: chksum_digest (STB_LOCAL)
ffffffff815b8fc0-ffffffff815b8fe1: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff81662260)
Location: crypto/crc32c_generic.c:114
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff81662390)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
```
In crypto/crc64_rocksoft_generic.c (ffffffff81662460)
Location: crypto/crc64_rocksoft_generic.c:50
Inline: False
```
**Symbols:**

```
ffffffff81662260-ffffffff81662292: chksum_digest (STB_LOCAL)
ffffffff81662390-ffffffff816623bd: chksum_digest (STB_LOCAL)
ffffffff81662460-ffffffff8166248d: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff8171c220)
Location: crypto/crc32c_generic.c:114
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff8171c3b0)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
```
In crypto/crc64_rocksoft_generic.c (ffffffff8171c4d0)
Location: crypto/crc64_rocksoft_generic.c:50
Inline: False
```
**Symbols:**

```
ffffffff8171c220-ffffffff8171c252: chksum_digest (STB_LOCAL)
ffffffff8171c3b0-ffffffff8171c3dd: chksum_digest (STB_LOCAL)
ffffffff8171c4d0-ffffffff8171c4fd: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff817579c0)
Location: crypto/crc32c_generic.c:114
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff81757b50)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
```
In crypto/crc64_rocksoft_generic.c (ffffffff81757c70)
Location: crypto/crc64_rocksoft_generic.c:50
Inline: False
```
**Symbols:**

```
ffffffff817579c0-ffffffff817579f2: chksum_digest (STB_LOCAL)
ffffffff81757b50-ffffffff81757b7d: chksum_digest (STB_LOCAL)
ffffffff81757c70-ffffffff81757c9d: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff817998c0)
Location: crypto/crc32c_generic.c:114
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff81799a50)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
```
In crypto/crc64_rocksoft_generic.c (ffffffff81799b70)
Location: crypto/crc64_rocksoft_generic.c:50
Inline: False
```
**Symbols:**

```
ffffffff817998c0-ffffffff817998f2: chksum_digest (STB_LOCAL)
ffffffff81799a50-ffffffff81799a7d: chksum_digest (STB_LOCAL)
ffffffff81799b70-ffffffff81799b9d: chksum_digest (STB_LOCAL)
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
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffff8000105cf7f0)
Location: crypto/crc32c_generic.c:116
Inline: False
```
```
In crypto/crct10dif_generic.c (ffff8000105cf9c8)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
ffff8000105cf7f0-ffff8000105cf848: chksum_digest (STB_LOCAL)
ffff8000105cf9c8-ffff8000105cfa18: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (c077d4fc)
Location: crypto/crc32c_generic.c:116
Inline: False
```
```
In crypto/crct10dif_generic.c (c077d62c)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
c077d4fc-c077d530: chksum_digest (STB_LOCAL)
c077d62c-c077d65c: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (c00000000075b810)
Location: crypto/crc32c_generic.c:116
Inline: False
```
```
In crypto/crct10dif_generic.c (c00000000075ba10)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
c00000000075b810-c00000000075b868: chksum_digest (STB_LOCAL)
c00000000075ba10-c00000000075ba60: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffe000414724)
Location: crypto/crc32c_generic.c:116
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffe0004148fa)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
ffffffe000414724-ffffffe000414790: chksum_digest (STB_LOCAL)
ffffffe0004148fa-ffffffe00041493e: chksum_digest (STB_LOCAL)
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
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff814cb7a0)
Location: crypto/crc32c_generic.c:116
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff814cb890)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
ffffffff814cb7a0-ffffffff814cb7c3: chksum_digest (STB_LOCAL)
ffffffff814cb890-ffffffff814cb8ae: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff814bc1c0)
Location: crypto/crc32c_generic.c:116
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff814bc2b0)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
ffffffff814bc1c0-ffffffff814bc1e3: chksum_digest (STB_LOCAL)
ffffffff814bc2b0-ffffffff814bc2ce: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff814c7830)
Location: crypto/crc32c_generic.c:116
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff814c7920)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
ffffffff814c7830-ffffffff814c7853: chksum_digest (STB_LOCAL)
ffffffff814c7920-ffffffff814c793e: chksum_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
int chksum_digest(struct shash_desc *desc, const u8 *data, unsigned int length, u8 *out);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/crc32c_generic.c (ffffffff814e0300)
Location: crypto/crc32c_generic.c:116
Inline: False
```
```
In crypto/crct10dif_generic.c (ffffffff814e03f0)
Location: crypto/crct10dif_generic.c:82
Inline: False
```
**Symbols:**

```
ffffffff814e0300-ffffffff814e0323: chksum_digest (STB_LOCAL)
ffffffff814e03f0-ffffffff814e040e: chksum_digest (STB_LOCAL)
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
