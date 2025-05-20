# Function: <code>audit_field_valid</code>

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
In kernel/auditfilter.c (ffffffff81124a62)
Location: kernel/auditfilter.c:333
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffff8112cb59)
Location: kernel/auditfilter.c:333
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffff81136869)
Location: kernel/auditfilter.c:333
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffff81137a64)
Location: kernel/auditfilter.c:333
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffff8114475a)
Location: kernel/auditfilter.c:336
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffff8115334b)
Location: kernel/auditfilter.c:336
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffff81160007)
Location: kernel/auditfilter.c:336
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_rule_change
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
In kernel/auditfilter.c (ffffffff8116c00b)
Location: kernel/auditfilter.c:323
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (ffffffff81177ee6)
Location: kernel/auditfilter.c:323
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_data_to_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118a550)
Location: kernel/auditfilter.c:323
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff8118a550-ffffffff8118a72b: audit_field_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (ffffffff811877c0)
Location: kernel/auditfilter.c:323
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff811877c0-ffffffff8118799b: audit_field_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (ffffffff81188830)
Location: kernel/auditfilter.c:323
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff81188830-ffffffff811889fa: audit_field_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (ffffffff811b0d90)
Location: kernel/auditfilter.c:323
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff811b0d90-ffffffff811b0f5a: audit_field_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (ffffffff811e3120)
Location: kernel/auditfilter.c:327
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff811e3120-ffffffff811e3353: audit_field_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (ffffffff81229590)
Location: kernel/auditfilter.c:327
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff81229590-ffffffff812297c3: audit_field_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (ffffffff8123fb90)
Location: kernel/auditfilter.c:327
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff8123fb90-ffffffff8123fd8c: audit_field_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditfilter.c (ffffffff81259a10)
Location: kernel/auditfilter.c:327
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_data_to_entry
```
**Symbols:**

```
ffffffff81259a10-ffffffff81259c0c: audit_field_valid.isra.0 (STB_LOCAL)
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
In kernel/auditfilter.c (ffff8000101ed0c4)
Location: kernel/auditfilter.c:323
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (c042cd10)
Location: kernel/auditfilter.c:323
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (c00000000025f320)
Location: kernel/auditfilter.c:323
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (ffffffe000161658)
Location: kernel/auditfilter.c:323
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (ffffffff81170506)
Location: kernel/auditfilter.c:323
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (ffffffff811636a6)
Location: kernel/auditfilter.c:323
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (ffffffff8116e2d6)
Location: kernel/auditfilter.c:323
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_data_to_entry
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
In kernel/auditfilter.c (ffffffff8117bac6)
Location: kernel/auditfilter.c:323
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_data_to_entry
```
</details>
</li>
</ul>

## Differences
