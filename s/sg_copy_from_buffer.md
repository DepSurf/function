# Function: <code>sg_copy_from_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813fa5f0)
Location: lib/scatterlist.c:699
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff813fa5f0-ffffffff813fa601: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81441670)
Location: lib/scatterlist.c:699
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff81441670-ffffffff81441681: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e890)
Location: lib/scatterlist.c:699
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff8145e890-ffffffff8145e8a1: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81463a80)
Location: lib/scatterlist.c:695
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff81463a80-ffffffff81463a91: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148fa20)
Location: lib/scatterlist.c:736
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff8148fa20-ffffffff8148fa31: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c4700)
Location: lib/scatterlist.c:851
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff814c4700-ffffffff814c4711: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8df0)
Location: lib/scatterlist.c:851
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff814d8df0-ffffffff814d8e01: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81504ca0)
Location: lib/scatterlist.c:886
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff81504ca0-ffffffff81504cb1: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522de0)
Location: lib/scatterlist.c:886
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff81522de0-ffffffff81522df1: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81586040)
Location: lib/scatterlist.c:886
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_format_dsm_trim_descr
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff81586040-ffffffff81586051: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a3120)
Location: lib/scatterlist.c:967
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_format_dsm_trim_descr
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff815a3120-ffffffff815a3131: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815aa4e0)
Location: lib/scatterlist.c:967
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff815aa4e0-ffffffff815aa4f1: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81613640)
Location: lib/scatterlist.c:997
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff81613640-ffffffff81613651: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816dfe90)
Location: lib/scatterlist.c:994
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff816dfe90-ffffffff816dfeb3: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817d0260)
Location: lib/scatterlist.c:1004
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff817d0260-ffffffff817d0283: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180e6c0)
Location: lib/scatterlist.c:1006
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff8180e6c0-ffffffff8180e6e3: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81854340)
Location: lib/scatterlist.c:1008
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
```
**Symbols:**

```
ffffffff81854340-ffffffff81854363: sg_copy_from_buffer (STB_GLOBAL)
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
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c9b0)
Location: lib/scatterlist.c:886
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffff80001062c9b0-ffff80001062c9cc: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d33ec)
Location: lib/scatterlist.c:886
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/mmc/host/sdhci.c:sdhci_request_done
```
**Symbols:**

```
c07d33ec-c07d3414: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007cf5e0)
Location: lib/scatterlist.c:886
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
c0000000007cf5e0-c0000000007cf5f4: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045cb20)
Location: lib/scatterlist.c:886
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffe00045cb20-ffffffe00045cb3c: sg_copy_from_buffer (STB_GLOBAL)
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
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151b3c0)
Location: lib/scatterlist.c:886
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff8151b3c0-ffffffff8151b3d1: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150b6b0)
Location: lib/scatterlist.c:886
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff8150b6b0-ffffffff8150b6c1: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81517450)
Location: lib/scatterlist.c:886
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff81517450-ffffffff81517461: sg_copy_from_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t sg_copy_from_buffer(struct scatterlist *sgl, unsigned int nents, const void *buf, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530bf0)
Location: lib/scatterlist.c:886
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
```
**Symbols:**

```
ffffffff81530bf0-ffffffff81530c01: sg_copy_from_buffer (STB_GLOBAL)
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
