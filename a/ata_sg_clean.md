# Function: <code>ata_sg_clean</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_sg_clean(struct ata_queued_cmd *qc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cab70)
Location: drivers/ata/libata-core.c:4598
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
**Symbols:**

```
ffffffff815cab70-ffffffff815cac20: ata_sg_clean (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_sg_clean(struct ata_queued_cmd *qc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816233b0)
Location: drivers/ata/libata-core.c:4785
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
**Symbols:**

```
ffffffff816233b0-ffffffff81623460: ata_sg_clean (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_sg_clean(struct ata_queued_cmd *qc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81653f30)
Location: drivers/ata/libata-core.c:4827
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
```
**Symbols:**

```
ffffffff81653f30-ffffffff81653fe0: ata_sg_clean (STB_GLOBAL)
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
In drivers/ata/libata-core.c (ffffffff81668824)
Location: drivers/ata/libata-core.c:4990
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff816d1ea4)
Location: drivers/ata/libata-core.c:5022
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff8170e5d4)
Location: drivers/ata/libata-core.c:5028
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81730a54)
Location: drivers/ata/libata-core.c:5032
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff8176c1b7)
Location: drivers/ata/libata-core.c:5017
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81790227)
Location: drivers/ata/libata-core.c:5017
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81854eb7)
Location: drivers/ata/libata-core.c:4414
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81865187)
Location: drivers/ata/libata-core.c:4414
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81847c27)
Location: drivers/ata/libata-core.c:4414
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff818d4bfb)
Location: drivers/ata/libata-core.c:4474
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81a252e8)
Location: drivers/ata/libata-core.c:4508
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81ba7498)
Location: drivers/ata/libata-core.c:4514
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81bfe068)
Location: drivers/ata/libata-core.c:4709
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81c53e18)
Location: drivers/ata/libata-core.c:4708
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffff800010999e7c)
Location: drivers/ata/libata-core.c:5017
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (c0a69e80)
Location: drivers/ata/libata-core.c:5017
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (c000000000a5d154)
Location: drivers/ata/libata-core.c:5017
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffe0005fa8a6)
Location: drivers/ata/libata-core.c:5017
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81755397)
Location: drivers/ata/libata-core.c:5017
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff81735237)
Location: drivers/ata/libata-core.c:5017
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff817850a7)
Location: drivers/ata/libata-core.c:5017
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
In drivers/ata/libata-core.c (ffffffff8179ee97)
Location: drivers/ata/libata-core.c:5017
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:__ata_qc_complete
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
</ul>
