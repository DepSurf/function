# Function: <code>ata_eh_speed_down</code>

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
In drivers/ata/libata-eh.c (ffffffff815d68a8)
Location: drivers/ata/libata-eh.c:2036
Inline: True
Inline callers:
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
In drivers/ata/libata-eh.c (ffffffff81630396)
Location: drivers/ata/libata-eh.c:2120
Inline: True
Inline callers:
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
In drivers/ata/libata-eh.c (ffffffff816614e6)
Location: drivers/ata/libata-eh.c:2120
Inline: True
Inline callers:
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
In drivers/ata/libata-eh.c (ffffffff8167652d)
Location: drivers/ata/libata-eh.c:2057
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff816dfb80)
Location: drivers/ata/libata-eh.c:2055
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff8171c4c2)
Location: drivers/ata/libata-eh.c:2008
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff8173ed6a)
Location: drivers/ata/libata-eh.c:2004
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff8177adee)
Location: drivers/ata/libata-eh.c:1989
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
In drivers/ata/libata-eh.c (ffffffff8179e90b)
Location: drivers/ata/libata-eh.c:1989
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int ata_eh_speed_down(struct ata_device *dev, unsigned int eflags, unsigned int err_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81861fb0)
Location: drivers/ata/libata-eh.c:1791
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81861fb0-ffffffff818621ec: ata_eh_speed_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int ata_eh_speed_down(struct ata_device *dev, unsigned int eflags, unsigned int err_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81870dc0)
Location: drivers/ata/libata-eh.c:1791
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81870dc0-ffffffff81870ffc: ata_eh_speed_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int ata_eh_speed_down(struct ata_device *dev, unsigned int eflags, unsigned int err_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81853300)
Location: drivers/ata/libata-eh.c:1791
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81853300-ffffffff818536e9: ata_eh_speed_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int ata_eh_speed_down(struct ata_device *dev, unsigned int eflags, unsigned int err_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e1360)
Location: drivers/ata/libata-eh.c:1799
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff818e1360-ffffffff818e177d: ata_eh_speed_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int ata_eh_speed_down(struct ata_device *dev, unsigned int eflags, unsigned int err_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:1795
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81a322c0-ffffffff81a326dc: ata_eh_speed_down (STB_LOCAL)
ffffffff81ed8699-ffffffff81ed86c4: ata_eh_speed_down.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int ata_eh_speed_down(struct ata_device *dev, unsigned int eflags, unsigned int err_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb69a0)
Location: drivers/ata/libata-eh.c:1800
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81bb69a0-ffffffff81bb6dba: ata_eh_speed_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int ata_eh_speed_down(struct ata_device *dev, unsigned int eflags, unsigned int err_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0df00)
Location: drivers/ata/libata-eh.c:1810
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81c0df00-ffffffff81c0e3cd: ata_eh_speed_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int ata_eh_speed_down(struct ata_device *dev, unsigned int eflags, unsigned int err_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c63140)
Location: drivers/ata/libata-eh.c:1817
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81c63140-ffffffff81c6360d: ata_eh_speed_down (STB_LOCAL)
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
In drivers/ata/libata-eh.c (ffff8000109aa2d4)
Location: drivers/ata/libata-eh.c:1989
Inline: True
Inline callers:
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
In drivers/ata/libata-eh.c (c0a79af4)
Location: drivers/ata/libata-eh.c:1989
Inline: True
Inline callers:
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
In drivers/ata/libata-eh.c (c000000000a70edc)
Location: drivers/ata/libata-eh.c:1989
Inline: True
Inline callers:
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
In drivers/ata/libata-eh.c (ffffffe000607c1c)
Location: drivers/ata/libata-eh.c:1989
Inline: True
Inline callers:
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
In drivers/ata/libata-eh.c (ffffffff817639fb)
Location: drivers/ata/libata-eh.c:1989
Inline: True
Inline callers:
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
In drivers/ata/libata-eh.c (ffffffff8174385b)
Location: drivers/ata/libata-eh.c:1989
Inline: True
Inline callers:
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
In drivers/ata/libata-eh.c (ffffffff8179378b)
Location: drivers/ata/libata-eh.c:1989
Inline: True
Inline callers:
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
In drivers/ata/libata-eh.c (ffffffff817ad5e4)
Location: drivers/ata/libata-eh.c:1989
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
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
