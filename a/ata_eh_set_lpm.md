# Function: <code>ata_eh_set_lpm</code>

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
In drivers/ata/libata-eh.c (ffffffff815d8f23)
Location: drivers/ata/libata-eh.c:3423
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff816329ff)
Location: drivers/ata/libata-eh.c:3514
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff81663b4f)
Location: drivers/ata/libata-eh.c:3514
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff8167863d)
Location: drivers/ata/libata-eh.c:3469
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff816e1c7d)
Location: drivers/ata/libata-eh.c:3467
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff8171e586)
Location: drivers/ata/libata-eh.c:3445
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff817411a2)
Location: drivers/ata/libata-eh.c:3441
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff8177cd42)
Location: drivers/ata/libata-eh.c:3426
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff817a080e)
Location: drivers/ata/libata-eh.c:3426
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ata_eh_set_lpm(struct ata_link *link, enum ata_lpm_policy policy, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81860c50)
Location: drivers/ata/libata-eh.c:3228
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81860c50-ffffffff8186105b: ata_eh_set_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ata_eh_set_lpm(struct ata_link *link, enum ata_lpm_policy policy, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8186fa70)
Location: drivers/ata/libata-eh.c:3228
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8186fa70-ffffffff8186fe7b: ata_eh_set_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ata_eh_set_lpm(struct ata_link *link, enum ata_lpm_policy policy, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81852280)
Location: drivers/ata/libata-eh.c:3229
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81852280-ffffffff81852688: ata_eh_set_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ata_eh_set_lpm(struct ata_link *link, enum ata_lpm_policy policy, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e00a0)
Location: drivers/ata/libata-eh.c:3236
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff818e00a0-ffffffff818e04d4: ata_eh_set_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_eh_set_lpm(struct ata_link *link, enum ata_lpm_policy policy, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:3238
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81a30d40-ffffffff81a3112d: ata_eh_set_lpm (STB_LOCAL)
ffffffff81ed835e-ffffffff81ed8492: ata_eh_set_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_eh_set_lpm(struct ata_link *link, enum ata_lpm_policy policy, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb4ec0)
Location: drivers/ata/libata-eh.c:3260
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81bb4ec0-ffffffff81bb53c6: ata_eh_set_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_eh_set_lpm(struct ata_link *link, enum ata_lpm_policy policy, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0c3b0)
Location: drivers/ata/libata-eh.c:3370
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c0c3b0-ffffffff81c0c892: ata_eh_set_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_eh_set_lpm(struct ata_link *link, enum ata_lpm_policy policy, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c61580)
Location: drivers/ata/libata-eh.c:3369
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c61580-ffffffff81c61a62: ata_eh_set_lpm (STB_LOCAL)
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
In drivers/ata/libata-eh.c (ffff8000109ac0d8)
Location: drivers/ata/libata-eh.c:3426
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (c0a7bb80)
Location: drivers/ata/libata-eh.c:3426
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (c000000000a733b0)
Location: drivers/ata/libata-eh.c:3426
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffe00060916a)
Location: drivers/ata/libata-eh.c:3426
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff817658f8)
Location: drivers/ata/libata-eh.c:3426
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff81745758)
Location: drivers/ata/libata-eh.c:3426
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff8179568e)
Location: drivers/ata/libata-eh.c:3426
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff817af4fe)
Location: drivers/ata/libata-eh.c:3426
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
