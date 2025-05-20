# Function: <code>pci_dev_assign_added</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8151447a)
Location: drivers/pci/pci.h:304
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff815188c2)
Location: drivers/pci/pci.h:304
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff81529bda)
Location: drivers/pci/pci.h:369
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8152e32f)
Location: drivers/pci/pci.h:369
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff81558df2)
Location: drivers/pci/pci.h:374
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8155dad0)
Location: drivers/pci/pci.h:374
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff8157a392)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8157eb40)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff8161f4ae)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff816241d0)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff81645c9e)
Location: drivers/pci/pci.h:396
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff81649d90)
Location: drivers/pci/pci.h:396
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff816289de)
Location: drivers/pci/pci.h:391
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8162c949)
Location: drivers/pci/pci.h:391
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff8169835e)
Location: drivers/pci/pci.h:412
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8169be10)
Location: drivers/pci/pci.h:412
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff817b963e)
Location: drivers/pci/pci.h:373
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff817bd72a)
Location: drivers/pci/pci.h:373
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff818d423a)
Location: drivers/pci/pci.h:371
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff818d985a)
Location: drivers/pci/pci.h:371
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff81917494)
Location: drivers/pci/pci.h:370
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8191cbaa)
Location: drivers/pci/pci.h:370
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff8195f5a4)
Location: drivers/pci/pci.h:381
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff81964fda)
Location: drivers/pci/pci.h:381
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffff8000106dcc98)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffff8000106e163c)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (c087889c)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (c087d104)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (c000000000854dc4)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (c00000000085a7a4)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffe0004b511e)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffe0004b9096)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff8156e8a2)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff81573060)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff8155d012)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff815617c0)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff8156e0e2)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff81572890)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff815885c2)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8158cd70)
Location: drivers/pci/pci.h:408
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
</details>
</li>
</ul>

## Differences
