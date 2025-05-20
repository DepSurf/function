# Function: <code>ata_eh_nr_in_flight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_eh_nr_in_flight(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff815d4a00)
Location: drivers/ata/libata-eh.c:870
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
**Symbols:**

```
ffffffff815d4a00-ffffffff815d4a5b: ata_eh_nr_in_flight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_eh_nr_in_flight(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8162e490)
Location: drivers/ata/libata-eh.c:870
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
**Symbols:**

```
ffffffff8162e490-ffffffff8162e4eb: ata_eh_nr_in_flight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_eh_nr_in_flight(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8165f5e0)
Location: drivers/ata/libata-eh.c:870
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
```
**Symbols:**

```
ffffffff8165f5e0-ffffffff8165f63b: ata_eh_nr_in_flight (STB_LOCAL)
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
In drivers/ata/libata-eh.c (ffffffff81675749)
Location: drivers/ata/libata-eh.c:871
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff816deda5)
Location: drivers/ata/libata-eh.c:869
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff8171b5bf)
Location: drivers/ata/libata-eh.c:818
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff8173de8f)
Location: drivers/ata/libata-eh.c:818
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff817799ee)
Location: drivers/ata/libata-eh.c:801
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff8179d84e)
Location: drivers/ata/libata-eh.c:801
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff81862437)
Location: drivers/ata/libata-eh.c:800
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff81871247)
Location: drivers/ata/libata-eh.c:800
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff81853937)
Location: drivers/ata/libata-eh.c:800
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_qc_schedule_eh
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff818e1b27)
Location: drivers/ata/libata-eh.c:808
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff81a32b27)
Location: drivers/ata/libata-eh.c:805
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff81bb7227)
Location: drivers/ata/libata-eh.c:807
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff81c0e837)
Location: drivers/ata/libata-eh.c:810
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff81c63a47)
Location: drivers/ata/libata-eh.c:832
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:801
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (c0a789a0)
Location: drivers/ata/libata-eh.c:801
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (c000000000a6f504)
Location: drivers/ata/libata-eh.c:801
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffe000606e10)
Location: drivers/ata/libata-eh.c:801
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff8176293e)
Location: drivers/ata/libata-eh.c:801
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff8174279e)
Location: drivers/ata/libata-eh.c:801
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff817926ce)
Location: drivers/ata/libata-eh.c:801
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
In drivers/ata/libata-eh.c (ffffffff817ac50e)
Location: drivers/ata/libata-eh.c:801
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
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
