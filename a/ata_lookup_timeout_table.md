# Function: <code>ata_lookup_timeout_table</code>

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
In drivers/ata/libata-eh.c (ffffffff815d56c9)
Location: drivers/ata/libata-eh.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
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
In drivers/ata/libata-eh.c (ffffffff8162f1a8)
Location: drivers/ata/libata-eh.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff816602f8)
Location: drivers/ata/libata-eh.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff81675498)
Location: drivers/ata/libata-eh.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff816deaf8)
Location: drivers/ata/libata-eh.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8171b325)
Location: drivers/ata/libata-eh.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
Direct callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
```
**Symbols:**

```
ffffffff8171acb0-ffffffff8171ad08: ata_lookup_timeout_table.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8173dc35)
Location: drivers/ata/libata-eh.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
Direct callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
```
**Symbols:**

```
ffffffff8173d5b0-ffffffff8173d608: ata_lookup_timeout_table.part.9 (STB_LOCAL)
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
In drivers/ata/libata-eh.c (ffffffff81779755)
Location: drivers/ata/libata-eh.c:294
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff8179d5c5)
Location: drivers/ata/libata-eh.c:294
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff81862285)
Location: drivers/ata/libata-eh.c:293
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff81871099)
Location: drivers/ata/libata-eh.c:293
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff81853785)
Location: drivers/ata/libata-eh.c:293
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff818e189b)
Location: drivers/ata/libata-eh.c:301
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff81a3282b)
Location: drivers/ata/libata-eh.c:301
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff81bb6f2b)
Location: drivers/ata/libata-eh.c:303
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff81c0e52b)
Location: drivers/ata/libata-eh.c:303
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff81c6374b)
Location: drivers/ata/libata-eh.c:305
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffff8000109a88bc)
Location: drivers/ata/libata-eh.c:294
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (c0a78610)
Location: drivers/ata/libata-eh.c:294
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (c000000000a6f0a0)
Location: drivers/ata/libata-eh.c:294
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffe000606b2c)
Location: drivers/ata/libata-eh.c:294
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff817626b5)
Location: drivers/ata/libata-eh.c:294
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff81742515)
Location: drivers/ata/libata-eh.c:294
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff81792445)
Location: drivers/ata/libata-eh.c:294
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
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
In drivers/ata/libata-eh.c (ffffffff817ac285)
Location: drivers/ata/libata-eh.c:294
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_internal_cmd_timed_out
  - drivers/ata/libata-eh.c:ata_internal_cmd_timeout
```
</details>
</li>
</ul>

## Differences
