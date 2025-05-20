# Function: <code>scsi_host_dix_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (0)
Location: include/scsi/scsi_host.h:889
Inline: True
```
```
In drivers/scsi/sd_dif.c (0)
Location: include/scsi/scsi_host.h:889
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81615ede)
Location: include/scsi/scsi_host.h:884
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff81617dbf)
Location: include/scsi/scsi_host.h:884
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8164592e)
Location: include/scsi/scsi_host.h:892
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff8164795f)
Location: include/scsi/scsi_host.h:892
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8165960e)
Location: include/scsi/scsi_host.h:882
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff8165c52f)
Location: include/scsi/scsi_host.h:882
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816c2bde)
Location: include/scsi/scsi_host.h:877
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff816c5b9f)
Location: include/scsi/scsi_host.h:877
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816fee1e)
Location: include/scsi/scsi_host.h:853
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff81702141)
Location: include/scsi/scsi_host.h:853
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81721d7e)
Location: include/scsi/scsi_host.h:832
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff81725101)
Location: include/scsi/scsi_host.h:832
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175d52f)
Location: include/scsi/scsi_host.h:825
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff81760761)
Location: include/scsi/scsi_host.h:825
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817813ff)
Location: include/scsi/scsi_host.h:837
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff81784701)
Location: include/scsi/scsi_host.h:837
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8184396e)
Location: include/scsi/scsi_host.h:838
Inline: True
Inline callers:
  - drivers/scsi/sd.c:protection_mode_show
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff81848211)
Location: include/scsi/scsi_host.h:838
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81853c9e)
Location: include/scsi/scsi_host.h:845
Inline: True
Inline callers:
  - drivers/scsi/sd.c:protection_mode_show
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff81858761)
Location: include/scsi/scsi_host.h:845
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818376a1)
Location: include/scsi/scsi_host.h:861
Inline: True
Inline callers:
  - drivers/scsi/sd.c:protection_mode_show
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff8183b6e1)
Location: include/scsi/scsi_host.h:861
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c29e6)
Location: include/scsi/scsi_host.h:862
Inline: True
Inline callers:
  - drivers/scsi/sd.c:protection_mode_show
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff818c7e9d)
Location: include/scsi/scsi_host.h:862
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81a0e133)
Location: include/scsi/scsi_host.h:844
Inline: True
Inline callers:
  - drivers/scsi/sd.c:protection_mode_show
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff81a14d12)
Location: include/scsi/scsi_host.h:844
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81b8e123)
Location: include/scsi/scsi_host.h:853
Inline: True
Inline callers:
  - drivers/scsi/sd.c:protection_mode_show
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff81b951d2)
Location: include/scsi/scsi_host.h:853
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81be41b3)
Location: include/scsi/scsi_host.h:859
Inline: True
Inline callers:
  - drivers/scsi/sd.c:protection_mode_show
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff81beb742)
Location: include/scsi/scsi_host.h:859
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81c39463)
Location: include/scsi/scsi_host.h:862
Inline: True
Inline callers:
  - drivers/scsi/sd.c:protection_mode_show
  - drivers/scsi/sd.c:protection_mode_show
```
```
In drivers/scsi/sd_dif.c (ffffffff81c40e02)
Location: include/scsi/scsi_host.h:862
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff800010987bac)
Location: include/scsi/scsi_host.h:837
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffff80001098aee4)
Location: include/scsi/scsi_host.h:837
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a5a1c4)
Location: include/scsi/scsi_host.h:837
Inline: True
```
```
In drivers/scsi/sd_dif.c (c0a5d1e0)
Location: include/scsi/scsi_host.h:837
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a47c70)
Location: include/scsi/scsi_host.h:837
Inline: True
```
```
In drivers/scsi/sd_dif.c (c000000000a4b960)
Location: include/scsi/scsi_host.h:837
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005ec294)
Location: include/scsi/scsi_host.h:837
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffe0005ef2ec)
Location: include/scsi/scsi_host.h:837
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81735aef)
Location: include/scsi/scsi_host.h:837
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff81738df1)
Location: include/scsi/scsi_host.h:837
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8171778f)
Location: include/scsi/scsi_host.h:837
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff8171aa91)
Location: include/scsi/scsi_host.h:837
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8177627f)
Location: include/scsi/scsi_host.h:837
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff81779581)
Location: include/scsi/scsi_host.h:837
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8179005f)
Location: include/scsi/scsi_host.h:837
Inline: True
```
```
In drivers/scsi/sd_dif.c (ffffffff817933b1)
Location: include/scsi/scsi_host.h:837
Inline: True
Inline callers:
  - drivers/scsi/sd_dif.c:sd_dif_config_host
  - drivers/scsi/sd_dif.c:sd_dif_config_host
```
</details>
</li>
</ul>

## Differences
