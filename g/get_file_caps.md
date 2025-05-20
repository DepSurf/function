# Function: <code>get_file_caps</code>

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
In security/commoncap.c (ffffffff8133acb2)
Location: security/commoncap.c:446
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffff8137023c)
Location: security/commoncap.c:446
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffff81386a4c)
Location: security/commoncap.c:441
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffff8139b71c)
Location: security/commoncap.c:661
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffff813c0d2f)
Location: security/commoncap.c:653
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffff813f1ca6)
Location: security/commoncap.c:655
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffff8140cf76)
Location: security/commoncap.c:653
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffff8143a123)
Location: security/commoncap.c:650
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffff81453f93)
Location: security/commoncap.c:650
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (0)
Location: security/commoncap.c:650
Inline: True
Direct callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff814a6870-ffffffff814a69b3: get_file_caps.constprop.0 (STB_LOCAL)
ffffffff814a6f87-ffffffff814a6f9c: get_file_caps.constprop.0.cold (STB_LOCAL)
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
In security/commoncap.c (0)
Location: security/commoncap.c:668
Inline: True
Direct callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff814c3e20-ffffffff814c3f63: get_file_caps.constprop.0 (STB_LOCAL)
ffffffff81bf0049-ffffffff81bf005e: get_file_caps.constprop.0.cold (STB_LOCAL)
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
In security/commoncap.c (ffffffff814ca32d)
Location: security/commoncap.c:726
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
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
In security/commoncap.c (0)
Location: security/commoncap.c:726
Inline: True
Direct callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff81522f60-ffffffff815230bf: get_file_caps.constprop.0 (STB_LOCAL)
ffffffff81cd331f-ffffffff81cd3349: get_file_caps.constprop.0.cold (STB_LOCAL)
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
In security/commoncap.c (ffffffff815b6d57)
Location: security/commoncap.c:729
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
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
In security/commoncap.c (0)
Location: security/commoncap.c:729
Inline: True
Direct callers:
  - security/commoncap.c:cap_bprm_creds_from_file
```
**Symbols:**

```
ffffffff81661ec0-ffffffff81662068: get_file_caps.constprop.0 (STB_LOCAL)
ffffffff820731b2-ffffffff820731c7: get_file_caps.constprop.0.cold (STB_LOCAL)
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
In security/commoncap.c (ffffffff8169a52f)
Location: security/commoncap.c:724
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
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
In security/commoncap.c (ffffffff816d6c6f)
Location: security/commoncap.c:724
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_creds_from_file
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
In security/commoncap.c (ffff80001053f0c4)
Location: security/commoncap.c:650
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (c06f50ac)
Location: security/commoncap.c:650
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (c00000000068fa68)
Location: security/commoncap.c:650
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffe00039c672)
Location: security/commoncap.c:650
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffff8144c573)
Location: security/commoncap.c:650
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffff8143cfc3)
Location: security/commoncap.c:650
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffff81448613)
Location: security/commoncap.c:650
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
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
In security/commoncap.c (ffffffff8145f9e3)
Location: security/commoncap.c:650
Inline: True
Inline callers:
  - security/commoncap.c:cap_bprm_set_creds
```
</details>
</li>
</ul>

## Differences
