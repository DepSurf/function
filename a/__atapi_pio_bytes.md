# Function: <code>__atapi_pio_bytes</code>

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
In drivers/ata/libata-sff.c (ffffffff815de7fb)
Location: drivers/ata/libata-sff.c:828
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff81638560)
Location: drivers/ata/libata-sff.c:828
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff81669600)
Location: drivers/ata/libata-sff.c:828
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff8167dd64)
Location: drivers/ata/libata-sff.c:815
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff816e756e)
Location: drivers/ata/libata-sff.c:815
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff81723cae)
Location: drivers/ata/libata-sff.c:815
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff817465ce)
Location: drivers/ata/libata-sff.c:785
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff8178229f)
Location: drivers/ata/libata-sff.c:775
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff817a5f4f)
Location: drivers/ata/libata-sff.c:775
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __atapi_pio_bytes(struct ata_queued_cmd *qc, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff8186a220)
Location: drivers/ata/libata-sff.c:771
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:atapi_pio_bytes
```
**Symbols:**

```
ffffffff8186a220-ffffffff8186a3a5: __atapi_pio_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __atapi_pio_bytes(struct ata_queued_cmd *qc, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81879030)
Location: drivers/ata/libata-sff.c:771
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:atapi_pio_bytes
```
**Symbols:**

```
ffffffff81879030-ffffffff818791b5: __atapi_pio_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __atapi_pio_bytes(struct ata_queued_cmd *qc, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff8185b870)
Location: drivers/ata/libata-sff.c:790
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
```
**Symbols:**

```
ffffffff8185b870-ffffffff8185b9f5: __atapi_pio_bytes (STB_LOCAL)
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
In drivers/ata/libata-sff.c (ffffffff818eb2fd)
Location: drivers/ata/libata-sff.c:790
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:atapi_pio_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __atapi_pio_bytes(struct ata_queued_cmd *qc, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81a3bc40)
Location: drivers/ata/libata-sff.c:785
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
```
**Symbols:**

```
ffffffff81a3bc40-ffffffff81a3be6c: __atapi_pio_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __atapi_pio_bytes(struct ata_queued_cmd *qc, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81bc1090)
Location: drivers/ata/libata-sff.c:729
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
```
**Symbols:**

```
ffffffff81bc1090-ffffffff81bc12bc: __atapi_pio_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __atapi_pio_bytes(struct ata_queued_cmd *qc, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81c18b70)
Location: drivers/ata/libata-sff.c:729
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
```
**Symbols:**

```
ffffffff81c18b70-ffffffff81c18d9c: __atapi_pio_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __atapi_pio_bytes(struct ata_queued_cmd *qc, unsigned int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81c6d8c0)
Location: drivers/ata/libata-sff.c:729
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
```
**Symbols:**

```
ffffffff81c6d8c0-ffffffff81c6daec: __atapi_pio_bytes (STB_LOCAL)
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
In drivers/ata/libata-sff.c (ffff8000109b22bc)
Location: drivers/ata/libata-sff.c:775
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (c0a815e0)
Location: drivers/ata/libata-sff.c:775
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (c000000000a7ae20)
Location: drivers/ata/libata-sff.c:775
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffe00060ec76)
Location: drivers/ata/libata-sff.c:775
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff8176b00f)
Location: drivers/ata/libata-sff.c:775
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff8174ae6f)
Location: drivers/ata/libata-sff.c:775
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff8179adcf)
Location: drivers/ata/libata-sff.c:775
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff817b4c4f)
Location: drivers/ata/libata-sff.c:775
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
