# Function: <code>ata_sg_setup</code>

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
In drivers/ata/libata-core.c (ffffffff815cb50b)
Location: drivers/ata/libata-core.c:4712
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff81623ca4)
Location: drivers/ata/libata-core.c:4899
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff81654824)
Location: drivers/ata/libata-core.c:4941
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff81668e32)
Location: drivers/ata/libata-core.c:5020
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff816d24d6)
Location: drivers/ata/libata-core.c:5052
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff8170ebc7)
Location: drivers/ata/libata-core.c:5058
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff8173105b)
Location: drivers/ata/libata-core.c:5062
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff8176c80e)
Location: drivers/ata/libata-core.c:5047
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff8179087e)
Location: drivers/ata/libata-core.c:5047
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ata_sg_setup(struct ata_queued_cmd *qc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81852d10)
Location: drivers/ata/libata-core.c:4444
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
**Symbols:**

```
ffffffff81852d10-ffffffff81852d93: ata_sg_setup (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff81865678)
Location: drivers/ata/libata-core.c:4444
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff81848118)
Location: drivers/ata/libata-core.c:4444
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff818d515e)
Location: drivers/ata/libata-core.c:4504
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff81a258a0)
Location: drivers/ata/libata-core.c:4536
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff81ba7a60)
Location: drivers/ata/libata-core.c:4542
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff81bfe686)
Location: drivers/ata/libata-core.c:4737
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff81c54377)
Location: drivers/ata/libata-core.c:4736
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffff80001099a4d4)
Location: drivers/ata/libata-core.c:5047
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (c0a6a740)
Location: drivers/ata/libata-core.c:5047
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (c000000000a5da80)
Location: drivers/ata/libata-core.c:5047
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffe0005faea8)
Location: drivers/ata/libata-core.c:5047
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff817559be)
Location: drivers/ata/libata-core.c:5047
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff8173585e)
Location: drivers/ata/libata-core.c:5047
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff817856fe)
Location: drivers/ata/libata-core.c:5047
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
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
In drivers/ata/libata-core.c (ffffffff8179f52e)
Location: drivers/ata/libata-core.c:5047
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_qc_issue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
