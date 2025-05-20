# Function: <code>ata_dev_config_ncq</code>

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
In drivers/ata/libata-core.c (ffffffff815cd057)
Location: drivers/ata/libata-core.c:2081
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff81625874)
Location: drivers/ata/libata-core.c:2159
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff81656414)
Location: drivers/ata/libata-core.c:2199
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff8166a895)
Location: drivers/ata/libata-core.c:2280
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff816d3ee5)
Location: drivers/ata/libata-core.c:2281
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff8171049f)
Location: drivers/ata/libata-core.c:2272
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (ffffffff8173294f)
Location: drivers/ata/libata-core.c:2272
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
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
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2256
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff8176dc10-ffffffff8176dfdc: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
ffffffff8177135b-ffffffff817714a2: ata_dev_config_ncq.constprop.0.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2256
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81791c80-ffffffff8179204c: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
ffffffff81795336-ffffffff8179547d: ata_dev_config_ncq.constprop.0.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2202
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff818566a0-ffffffff81856941: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
ffffffff818596d4-ffffffff8185973e: ata_dev_config_ncq.constprop.0.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2202
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81866920-ffffffff81866bc1: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
ffffffff81c176e7-ffffffff81c17751: ata_dev_config_ncq.constprop.0.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2202
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81848c00-ffffffff81848fbb: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
ffffffff81c09206-ffffffff81c0933e: ata_dev_config_ncq.constprop.0.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2212
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff818d5bb0-ffffffff818d5f9c: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
ffffffff81d0dae5-ffffffff81d0db8b: ata_dev_config_ncq.constprop.0.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2197
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81a267e0-ffffffff81a26b72: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
ffffffff81ed6b22-ffffffff81ed6b70: ata_dev_config_ncq.constprop.0.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff81ba8d40)
Location: drivers/ata/libata-core.c:2198
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81ba8d40-ffffffff81ba9025: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff81bffc70)
Location: drivers/ata/libata-core.c:2232
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81bffc70-ffffffff81bfff4e: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffff81c55ce0)
Location: drivers/ata/libata-core.c:2367
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81c55ce0-ffffffff81c55fbe: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffff80001099bc20)
Location: drivers/ata/libata-core.c:2256
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffff80001099bc20-ffff80001099c0cc: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
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
In drivers/ata/libata-core.c (c0a6ba84)
Location: drivers/ata/libata-core.c:2256
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
c0a6ba84-c0a6bf54: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
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
In drivers/ata/libata-core.c (c000000000a5f540)
Location: drivers/ata/libata-core.c:2256
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
c000000000a5f540-c000000000a5fad8: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffffffe0005fc082)
Location: drivers/ata/libata-core.c:2256
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffe0005fc082-ffffffe0005fc46a: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
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
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2256
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81756dc0-ffffffff8175718c: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
ffffffff8175a446-ffffffff8175a58d: ata_dev_config_ncq.constprop.0.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2256
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81736c60-ffffffff8173702c: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
ffffffff8173a2e6-ffffffff8173a42d: ata_dev_config_ncq.constprop.0.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2256
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff81786b00-ffffffff81786ecc: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
ffffffff8178a1b6-ffffffff8178a2fd: ata_dev_config_ncq.constprop.0.cold (STB_LOCAL)
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
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2256
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_configure
```
**Symbols:**

```
ffffffff817a0950-ffffffff817a0d1c: ata_dev_config_ncq.constprop.0 (STB_LOCAL)
ffffffff817a4006-ffffffff817a414d: ata_dev_config_ncq.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
