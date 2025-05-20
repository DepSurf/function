# Function: <code>sata_pmp_revalidate</code>

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
In drivers/ata/libata-pmp.c (ffffffff815dfcc5)
Location: drivers/ata/libata-pmp.c:649
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffff816399cd)
Location: drivers/ata/libata-pmp.c:649
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffff8166aa5d)
Location: drivers/ata/libata-pmp.c:649
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffff8167f0a7)
Location: drivers/ata/libata-pmp.c:649
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffff816e8907)
Location: drivers/ata/libata-pmp.c:649
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffff81725240)
Location: drivers/ata/libata-pmp.c:649
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffff817479f0)
Location: drivers/ata/libata-pmp.c:649
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffff817838d2)
Location: drivers/ata/libata-pmp.c:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffff817a7542)
Location: drivers/ata/libata-pmp.c:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sata_pmp_revalidate(struct ata_device *dev, unsigned int new_class);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-pmp.c (ffffffff8186cf20)
Location: drivers/ata/libata-pmp.c:648
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff8186cf20-ffffffff8186d0e0: sata_pmp_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sata_pmp_revalidate(struct ata_device *dev, unsigned int new_class);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-pmp.c (ffffffff8187bbf0)
Location: drivers/ata/libata-pmp.c:648
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff8187bbf0-ffffffff8187bdb0: sata_pmp_revalidate (STB_LOCAL)
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
In drivers/ata/libata-pmp.c (ffffffff8185e3d9)
Location: drivers/ata/libata-pmp.c:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
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
In drivers/ata/libata-pmp.c (ffffffff818ed0f9)
Location: drivers/ata/libata-pmp.c:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sata_pmp_revalidate(struct ata_device *dev, unsigned int new_class);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-pmp.c (0)
Location: drivers/ata/libata-pmp.c:648
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81a3f450-ffffffff81a3f5a3: sata_pmp_revalidate (STB_LOCAL)
ffffffff81ed9452-ffffffff81ed94ea: sata_pmp_revalidate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sata_pmp_revalidate(struct ata_device *dev, unsigned int new_class);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-pmp.c (ffffffff81bc4ff0)
Location: drivers/ata/libata-pmp.c:648
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81bc4ff0-ffffffff81bc51be: sata_pmp_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sata_pmp_revalidate(struct ata_device *dev, unsigned int new_class);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-pmp.c (ffffffff81c1cb00)
Location: drivers/ata/libata-pmp.c:648
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81c1cb00-ffffffff81c1ccce: sata_pmp_revalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sata_pmp_revalidate(struct ata_device *dev, unsigned int new_class);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-pmp.c (ffffffff81c71bf0)
Location: drivers/ata/libata-pmp.c:648
Inline: False
Direct callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81c71bf0-ffffffff81c71dbe: sata_pmp_revalidate (STB_LOCAL)
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
In drivers/ata/libata-pmp.c (ffff8000109b3dbc)
Location: drivers/ata/libata-pmp.c:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (c0a82d7c)
Location: drivers/ata/libata-pmp.c:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (c000000000a7cd0c)
Location: drivers/ata/libata-pmp.c:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffe000610392)
Location: drivers/ata/libata-pmp.c:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffff8176c602)
Location: drivers/ata/libata-pmp.c:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffff8174c452)
Location: drivers/ata/libata-pmp.c:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffff8179c3c2)
Location: drivers/ata/libata-pmp.c:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-pmp.c (ffffffff817b6242)
Location: drivers/ata/libata-pmp.c:648
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
