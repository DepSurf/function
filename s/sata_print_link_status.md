# Function: <code>sata_print_link_status</code>

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
In drivers/ata/libata-core.c (ffffffff815cea62)
Location: drivers/ata/libata-core.c:2709
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff81627642)
Location: drivers/ata/libata-core.c:2884
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff816582a2)
Location: drivers/ata/libata-core.c:2926
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff8166cad2)
Location: drivers/ata/libata-core.c:3003
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff816d6122)
Location: drivers/ata/libata-core.c:3005
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff81711dc2)
Location: drivers/ata/libata-core.c:2999
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff81734282)
Location: drivers/ata/libata-core.c:2999
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff8176fc33)
Location: drivers/ata/libata-core.c:2983
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff81793ca3)
Location: drivers/ata/libata-core.c:2983
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void sata_print_link_status(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2936
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
```
**Symbols:**

```
ffffffff81853680-ffffffff818536f6: sata_print_link_status (STB_LOCAL)
ffffffff818592f3-ffffffff8185936e: sata_print_link_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void sata_print_link_status(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2936
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
```
**Symbols:**

```
ffffffff81863950-ffffffff818639c6: sata_print_link_status (STB_LOCAL)
ffffffff81c17306-ffffffff81c17381: sata_print_link_status.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff81846a53)
Location: drivers/ata/libata-core.c:2936
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff818d3648)
Location: drivers/ata/libata-core.c:2987
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sata_print_link_status(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3018
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
```
**Symbols:**

```
ffffffff81a23be0-ffffffff81a23d65: sata_print_link_status (STB_LOCAL)
ffffffff81ed673e-ffffffff81ed6792: sata_print_link_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sata_print_link_status(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba5b00)
Location: drivers/ata/libata-core.c:3019
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
```
**Symbols:**

```
ffffffff81ba5b00-ffffffff81ba5cde: sata_print_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sata_print_link_status(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfc640)
Location: drivers/ata/libata-core.c:3212
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
```
**Symbols:**

```
ffffffff81bfc640-ffffffff81bfc81e: sata_print_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sata_print_link_status(struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c52920)
Location: drivers/ata/libata-core.c:3209
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
```
**Symbols:**

```
ffffffff81c52920-ffffffff81c52afe: sata_print_link_status (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffff80001099e0d4)
Location: drivers/ata/libata-core.c:2983
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (c0a6e7e4)
Location: drivers/ata/libata-core.c:2983
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (c000000000a622a4)
Location: drivers/ata/libata-core.c:2983
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffe0005fe266)
Location: drivers/ata/libata-core.c:2983
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff81758db3)
Location: drivers/ata/libata-core.c:2983
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff81738c53)
Location: drivers/ata/libata-core.c:2983
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff81788b23)
Location: drivers/ata/libata-core.c:2983
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
In drivers/ata/libata-core.c (ffffffff817a2973)
Location: drivers/ata/libata-core.c:2983
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_std_postreset
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
