# Function: <code>rproc_disable_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f4f93)
Location: drivers/remoteproc/remoteproc_core.c:132
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
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
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9f50)
Location: drivers/remoteproc/remoteproc_core.c:135
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff819cb8c0-ffffffff819cb8e5: rproc_disable_iommu.isra.0 (STB_LOCAL)
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
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca698)
Location: drivers/remoteproc/remoteproc_core.c:134
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_actuate
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81c2e436-ffffffff81c2e45b: rproc_disable_iommu.isra.0 (STB_LOCAL)
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
In drivers/remoteproc/remoteproc_core.c (ffffffff819af94a)
Location: drivers/remoteproc/remoteproc_core.c:134
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81c20510-ffffffff81c20535: rproc_disable_iommu.isra.0 (STB_LOCAL)
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5ddca)
Location: drivers/remoteproc/remoteproc_core.c:135
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81d31ef8-ffffffff81d31f1d: rproc_disable_iommu.isra.0 (STB_LOCAL)
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcdf6b)
Location: drivers/remoteproc/remoteproc_core.c:135
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff81efe411-ffffffff81efe444: rproc_disable_iommu.isra.0 (STB_LOCAL)
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81d77cea)
Location: drivers/remoteproc/remoteproc_core.c:134
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81de5c3a)
Location: drivers/remoteproc/remoteproc_core.c:134
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
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
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9be1a)
Location: drivers/remoteproc/remoteproc_core.c:134
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_detach
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_attach
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
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
In drivers/remoteproc/remoteproc_core.c (ffff800010b81260)
Location: drivers/remoteproc/remoteproc_core.c:132
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
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
In drivers/remoteproc/remoteproc_core.c (c0c64850)
Location: drivers/remoteproc/remoteproc_core.c:132
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
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
In drivers/remoteproc/remoteproc_core.c (c000000000c5ddb8)
Location: drivers/remoteproc/remoteproc_core.c:132
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/remoteproc/remoteproc_core.c (ffffffff818962c3)
Location: drivers/remoteproc/remoteproc_core.c:132
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81906a23)
Location: drivers/remoteproc/remoteproc_core.c:132
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
</details>
</li>
</ul>

## Differences
