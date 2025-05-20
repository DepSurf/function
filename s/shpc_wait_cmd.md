# Function: <code>shpc_wait_cmd</code>

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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153e737)
Location: drivers/pci/hotplug/shpchp_hpc.c:271
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81555b07)
Location: drivers/pci/hotplug/shpchp_hpc.c:271
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81585b06)
Location: drivers/pci/hotplug/shpchp_hpc.c:271
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815a74e6)
Location: drivers/pci/hotplug/shpchp_hpc.c:271
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff816501e8)
Location: drivers/pci/hotplug/shpchp_hpc.c:271
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81673688)
Location: drivers/pci/hotplug/shpchp_hpc.c:271
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81655bae)
Location: drivers/pci/hotplug/shpchp_hpc.c:266
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shpc_wait_cmd(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:266
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
**Symbols:**

```
ffffffff816c79a0-ffffffff816c7af1: shpc_wait_cmd (STB_LOCAL)
ffffffff81cea1a0-ffffffff81cea1f7: shpc_wait_cmd.cold (STB_LOCAL)
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff817edbbc)
Location: drivers/pci/hotplug/shpchp_hpc.c:266
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81914fe1)
Location: drivers/pci/hotplug/shpchp_hpc.c:266
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819585f6)
Location: drivers/pci/hotplug/shpchp_hpc.c:266
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff819a1b66)
Location: drivers/pci/hotplug/shpchp_hpc.c:266
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
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
In drivers/pci/hotplug/shpchp_hpc.c (ffff80001070fb9c)
Location: drivers/pci/hotplug/shpchp_hpc.c:271
Inline: True
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dc572)
Location: drivers/pci/hotplug/shpchp_hpc.c:271
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159acf6)
Location: drivers/pci/hotplug/shpchp_hpc.c:271
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81589e86)
Location: drivers/pci/hotplug/shpchp_hpc.c:271
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8159b236)
Location: drivers/pci/hotplug/shpchp_hpc.c:271
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
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
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815b566f)
Location: drivers/pci/hotplug/shpchp_hpc.c:271
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
