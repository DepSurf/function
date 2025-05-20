# Function: <code>query_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ae2b2)
Location: security/apparmor/apparmorfs.c:275
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
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
In security/apparmor/apparmorfs.c (ffffffff813c50c3)
Location: security/apparmor/apparmorfs.c:369
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
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
In security/apparmor/apparmorfs.c (ffffffff813db339)
Location: security/apparmor/apparmorfs.c:658
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
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
In security/apparmor/apparmorfs.c (ffffffff81401dbb)
Location: security/apparmor/apparmorfs.c:659
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
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
In security/apparmor/apparmorfs.c (ffffffff81432d69)
Location: security/apparmor/apparmorfs.c:656
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
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
In security/apparmor/apparmorfs.c (ffffffff8144fa19)
Location: security/apparmor/apparmorfs.c:654
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (0)
Location: security/apparmor/apparmorfs.c:659
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff8147cc10-ffffffff8147d0ae: query_data.constprop.0 (STB_LOCAL)
ffffffff8147e6c6-ffffffff8147e6d2: query_data.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (0)
Location: security/apparmor/apparmorfs.c:627
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff814968e0-ffffffff81496d7e: query_data.constprop.0 (STB_LOCAL)
ffffffff814983c6-ffffffff814983d2: query_data.constprop.0.cold (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (0)
Location: security/apparmor/apparmorfs.c:658
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff814eeb00-ffffffff814eef09: query_data.constprop.0 (STB_LOCAL)
ffffffff814f0578-ffffffff814f0584: query_data.constprop.0.cold (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (0)
Location: security/apparmor/apparmorfs.c:658
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff8150bf70-ffffffff8150c383: query_data.constprop.0 (STB_LOCAL)
ffffffff81bf1646-ffffffff81bf1652: query_data.constprop.0.cold (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (0)
Location: security/apparmor/apparmorfs.c:658
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff81512900-ffffffff81512d0b: query_data.constprop.0 (STB_LOCAL)
ffffffff81be3656-ffffffff81be3662: query_data.constprop.0.cold (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (0)
Location: security/apparmor/apparmorfs.c:658
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff81570500-ffffffff8157090b: query_data.constprop.0 (STB_LOCAL)
ffffffff81cd6256-ffffffff81cd6262: query_data.constprop.0.cold (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (0)
Location: security/apparmor/apparmorfs.c:662
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff8160c360-ffffffff8160c7ab: query_data.constprop.0 (STB_LOCAL)
ffffffff81e89038-ffffffff81e89044: query_data.constprop.0.cold (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff816bea40)
Location: security/apparmor/apparmorfs.c:829
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff816bea40-ffffffff816bee78: query_data.constprop.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff816f7500)
Location: security/apparmor/apparmorfs.c:874
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff816f7500-ffffffff816f7988: query_data.constprop.0 (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff81734270)
Location: security/apparmor/apparmorfs.c:875
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff81734270-ffffffff817346fb: query_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff80001058cbb0)
Location: security/apparmor/apparmorfs.c:627
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffff80001058cbb0-ffff80001058cfe0: query_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (c073d780)
Location: security/apparmor/apparmorfs.c:627
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
c073d780-c073dc6c: query_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006feb50)
Location: security/apparmor/apparmorfs.c:627
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
c0000000006feb50-c0000000006ff248: query_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003dae7c)
Location: security/apparmor/apparmorfs.c:627
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffe0003dae7c-ffffffe0003db242: query_data.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (0)
Location: security/apparmor/apparmorfs.c:627
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff8148eec0-ffffffff8148f35e: query_data.constprop.0 (STB_LOCAL)
ffffffff814909a6-ffffffff814909b2: query_data.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (0)
Location: security/apparmor/apparmorfs.c:627
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff8147f8e0-ffffffff8147fd7e: query_data.constprop.0 (STB_LOCAL)
ffffffff814813c6-ffffffff814813d2: query_data.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (0)
Location: security/apparmor/apparmorfs.c:627
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff8148af60-ffffffff8148b3fe: query_data.constprop.0 (STB_LOCAL)
ffffffff8148ca46-ffffffff8148ca52: query_data.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (0)
Location: security/apparmor/apparmorfs.c:627
Inline: True
Direct callers:
  - security/apparmor/apparmorfs.c:aa_write_access
```
**Symbols:**

```
ffffffff814a2e50-ffffffff814a3323: query_data.constprop.0 (STB_LOCAL)
ffffffff814a4886-ffffffff814a4892: query_data.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
