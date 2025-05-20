# Function: <code>shpc_get_max_bus_speed</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153efdb)
Location: drivers/pci/hotplug/shpchp_hpc.c:851
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81556409)
Location: drivers/pci/hotplug/shpchp_hpc.c:851
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8158682a)
Location: drivers/pci/hotplug/shpchp_hpc.c:851
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815a8206)
Location: drivers/pci/hotplug/shpchp_hpc.c:851
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81650841)
Location: drivers/pci/hotplug/shpchp_hpc.c:851
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
**Symbols:**

```
ffffffff81650841-ffffffff81650926: shpc_get_max_bus_speed.isra.0 (STB_LOCAL)
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81bfd16b)
Location: drivers/pci/hotplug/shpchp_hpc.c:851
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
**Symbols:**

```
ffffffff81bfd16b-ffffffff81bfd250: shpc_get_max_bus_speed.isra.0 (STB_LOCAL)
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81bef6cf)
Location: drivers/pci/hotplug/shpchp_hpc.c:846
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81cea987)
Location: drivers/pci/hotplug/shpchp_hpc.c:846
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81eb1a03)
Location: drivers/pci/hotplug/shpchp_hpc.c:846
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81915aa3)
Location: drivers/pci/hotplug/shpchp_hpc.c:829
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819590af)
Location: drivers/pci/hotplug/shpchp_hpc.c:829
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a261f)
Location: drivers/pci/hotplug/shpchp_hpc.c:829
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffff8000107111b4)
Location: drivers/pci/hotplug/shpchp_hpc.c:851
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dd0a2)
Location: drivers/pci/hotplug/shpchp_hpc.c:851
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159ba16)
Location: drivers/pci/hotplug/shpchp_hpc.c:851
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8158aba6)
Location: drivers/pci/hotplug/shpchp_hpc.c:851
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159bf56)
Location: drivers/pci/hotplug/shpchp_hpc.c:851
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815b6386)
Location: drivers/pci/hotplug/shpchp_hpc.c:851
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
```
</details>
</li>
</ul>

## Differences
