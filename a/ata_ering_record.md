# Function: <code>ata_ering_record</code>

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
In drivers/ata/libata-eh.c (ffffffff815d6052)
Location: drivers/ata/libata-eh.c:378
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff8162fab2)
Location: drivers/ata/libata-eh.c:378
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff81660c02)
Location: drivers/ata/libata-eh.c:378
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff81675bf2)
Location: drivers/ata/libata-eh.c:378
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_ering_record(struct ata_ering *ering, unsigned int eflags, unsigned int err_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816dd6f0)
Location: drivers/ata/libata-eh.c:378
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff816dd6f0-ffffffff816dd733: ata_ering_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ata_ering_record(struct ata_ering *ering, unsigned int eflags, unsigned int err_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81719df0)
Location: drivers/ata/libata-eh.c:378
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81719df0-ffffffff81719e33: ata_ering_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ata_ering_record(struct ata_ering *ering, unsigned int eflags, unsigned int err_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8173c6f0)
Location: drivers/ata/libata-eh.c:378
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff8173c6f0-ffffffff8173c733: ata_ering_record (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ata_ering_record(struct ata_ering *ering, unsigned int eflags, unsigned int err_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:361
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81778340-ffffffff81778390: ata_ering_record (STB_LOCAL)
ffffffff8177de1f-ffffffff8177de3e: ata_ering_record.cold (STB_LOCAL)
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
In drivers/ata/libata-eh.c (ffffffff8179dd02)
Location: drivers/ata/libata-eh.c:361
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff81862847)
Location: drivers/ata/libata-eh.c:360
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
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
In drivers/ata/libata-eh.c (ffffffff81871657)
Location: drivers/ata/libata-eh.c:360
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
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
In drivers/ata/libata-eh.c (ffffffff81853d67)
Location: drivers/ata/libata-eh.c:360
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
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
In drivers/ata/libata-eh.c (ffffffff818e1f80)
Location: drivers/ata/libata-eh.c:368
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
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
In drivers/ata/libata-eh.c (ffffffff81a3300e)
Location: drivers/ata/libata-eh.c:368
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
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
In drivers/ata/libata-eh.c (ffffffff81bb776e)
Location: drivers/ata/libata-eh.c:370
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
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
In drivers/ata/libata-eh.c (ffffffff81c0ed7a)
Location: drivers/ata/libata-eh.c:370
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
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
In drivers/ata/libata-eh.c (ffffffff81c63fba)
Location: drivers/ata/libata-eh.c:372
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
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
In drivers/ata/libata-eh.c (ffff8000109a92d0)
Location: drivers/ata/libata-eh.c:361
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (c0a78ed4)
Location: drivers/ata/libata-eh.c:361
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (c000000000a6fc20)
Location: drivers/ata/libata-eh.c:361
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffe0006072fe)
Location: drivers/ata/libata-eh.c:361
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff81762df2)
Location: drivers/ata/libata-eh.c:361
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff81742c52)
Location: drivers/ata/libata-eh.c:361
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff81792b82)
Location: drivers/ata/libata-eh.c:361
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff817ac9c2)
Location: drivers/ata/libata-eh.c:361
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
