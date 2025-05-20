# Function: <code>sg_pcopy_to_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813fa640)
Location: lib/scatterlist.c:752
Inline: False
```
**Symbols:**

```
ffffffff813fa640-ffffffff813fa651: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814416c0)
Location: lib/scatterlist.c:752
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff814416c0-ffffffff814416d1: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e8e0)
Location: lib/scatterlist.c:752
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff8145e8e0-ffffffff8145e8f1: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81463ad0)
Location: lib/scatterlist.c:748
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81463ad0-ffffffff81463ae1: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148fa70)
Location: lib/scatterlist.c:789
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff8148fa70-ffffffff8148fa81: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c4750)
Location: lib/scatterlist.c:904
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff814c4750-ffffffff814c4761: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8e40)
Location: lib/scatterlist.c:904
Inline: False
Direct callers:
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff814d8e40-ffffffff814d8e51: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81504cf0)
Location: lib/scatterlist.c:939
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81504cf0-ffffffff81504d01: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522e30)
Location: lib/scatterlist.c:939
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81522e30-ffffffff81522e41: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81586090)
Location: lib/scatterlist.c:939
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
**Symbols:**

```
ffffffff81586090-ffffffff815860a1: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a3170)
Location: lib/scatterlist.c:1020
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
**Symbols:**

```
ffffffff815a3170-ffffffff815a3181: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815aa530)
Location: lib/scatterlist.c:1020
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
**Symbols:**

```
ffffffff815aa530-ffffffff815aa541: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81613690)
Location: lib/scatterlist.c:1050
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
**Symbols:**

```
ffffffff81613690-ffffffff816136a1: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816dff10)
Location: lib/scatterlist.c:1047
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
**Symbols:**

```
ffffffff816dff10-ffffffff816dff33: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817d0310)
Location: lib/scatterlist.c:1057
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
**Symbols:**

```
ffffffff817d0310-ffffffff817d0333: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180e770)
Location: lib/scatterlist.c:1059
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
**Symbols:**

```
ffffffff8180e770-ffffffff8180e793: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff818543f0)
Location: lib/scatterlist.c:1061
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci.c:xhci_map_temp_buffer
  - drivers/usb/host/xhci-ring.c:xhci_align_td
```
**Symbols:**

```
ffffffff818543f0-ffffffff81854413: sg_pcopy_to_buffer (STB_GLOBAL)
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
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062ca08)
Location: lib/scatterlist.c:939
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffff80001062ca08-ffff80001062ca20: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d3464)
Location: lib/scatterlist.c:939
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
c07d3464-c07d348c: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007cf630)
Location: lib/scatterlist.c:939
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
c0000000007cf630-c0000000007cf640: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045cb72)
Location: lib/scatterlist.c:939
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffe00045cb72-ffffffe00045cb8c: sg_pcopy_to_buffer (STB_GLOBAL)
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
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151b410)
Location: lib/scatterlist.c:939
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff8151b410-ffffffff8151b421: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150b700)
Location: lib/scatterlist.c:939
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff8150b700-ffffffff8150b711: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815174a0)
Location: lib/scatterlist.c:939
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff815174a0-ffffffff815174b1: sg_pcopy_to_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t sg_pcopy_to_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530c40)
Location: lib/scatterlist.c:939
Inline: False
Direct callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - drivers/base/devcoredump.c:devcd_read_from_sgtable
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
```
**Symbols:**

```
ffffffff81530c40-ffffffff81530c51: sg_pcopy_to_buffer (STB_GLOBAL)
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
