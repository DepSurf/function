# Function: <code>atapi_send_cdb</code>

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
In drivers/ata/libata-sff.c (ffffffff815de59a)
Location: drivers/ata/libata-sff.c:788
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
In drivers/ata/libata-sff.c (ffffffff8163844e)
Location: drivers/ata/libata-sff.c:788
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
In drivers/ata/libata-sff.c (ffffffff816694ee)
Location: drivers/ata/libata-sff.c:788
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
In drivers/ata/libata-sff.c (ffffffff8167db4d)
Location: drivers/ata/libata-sff.c:775
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
In drivers/ata/libata-sff.c (ffffffff816e734b)
Location: drivers/ata/libata-sff.c:775
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
In drivers/ata/libata-sff.c (ffffffff81723a83)
Location: drivers/ata/libata-sff.c:775
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
In drivers/ata/libata-sff.c (ffffffff817463a3)
Location: drivers/ata/libata-sff.c:745
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
In drivers/ata/libata-sff.c (ffffffff817821b2)
Location: drivers/ata/libata-sff.c:735
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
In drivers/ata/libata-sff.c (ffffffff817a5e62)
Location: drivers/ata/libata-sff.c:735
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
void atapi_send_cdb(struct ata_port *ap, struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff8186b470)
Location: drivers/ata/libata-sff.c:731
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
```
**Symbols:**

```
ffffffff8186b470-ffffffff8186b538: atapi_send_cdb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void atapi_send_cdb(struct ata_port *ap, struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff8187a280)
Location: drivers/ata/libata-sff.c:731
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
```
**Symbols:**

```
ffffffff8187a280-ffffffff8187a348: atapi_send_cdb (STB_LOCAL)
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
In drivers/ata/libata-sff.c (ffffffff8185cd4e)
Location: drivers/ata/libata-sff.c:750
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff818eb6ae)
Location: drivers/ata/libata-sff.c:750
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff81a3db69)
Location: drivers/ata/libata-sff.c:744
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff81bc3339)
Location: drivers/ata/libata-sff.c:688
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff81c1a951)
Location: drivers/ata/libata-sff.c:688
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffffffff81c6f801)
Location: drivers/ata/libata-sff.c:688
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
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
In drivers/ata/libata-sff.c (ffff8000109b21ac)
Location: drivers/ata/libata-sff.c:735
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
In drivers/ata/libata-sff.c (c0a81454)
Location: drivers/ata/libata-sff.c:735
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
In drivers/ata/libata-sff.c (c000000000a7ad30)
Location: drivers/ata/libata-sff.c:735
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
In drivers/ata/libata-sff.c (ffffffe00060edea)
Location: drivers/ata/libata-sff.c:735
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
In drivers/ata/libata-sff.c (ffffffff8176af22)
Location: drivers/ata/libata-sff.c:735
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
In drivers/ata/libata-sff.c (ffffffff8174ad82)
Location: drivers/ata/libata-sff.c:735
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
In drivers/ata/libata-sff.c (ffffffff8179ace2)
Location: drivers/ata/libata-sff.c:735
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
In drivers/ata/libata-sff.c (ffffffff817b4b62)
Location: drivers/ata/libata-sff.c:735
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
</ul>
