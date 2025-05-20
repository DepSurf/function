# Function: <code>pci_dev_is_added</code>

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
In drivers/pci/bus.c (ffffffff815144ce)
Location: drivers/pci/pci.h:309
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff81516ad9)
Location: drivers/pci/pci.h:309
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff81518881)
Location: drivers/pci/pci.h:309
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81540a00)
Location: drivers/pci/pci.h:309
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff81529c2e)
Location: drivers/pci/pci.h:374
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff8152c539)
Location: drivers/pci/pci.h:374
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff8152e301)
Location: drivers/pci/pci.h:374
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff81541d45)
Location: drivers/pci/pci.h:374
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81557c4a)
Location: drivers/pci/pci.h:374
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff81558e2e)
Location: drivers/pci/pci.h:379
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff8155aed2)
Location: drivers/pci/pci.h:379
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff8155daa0)
Location: drivers/pci/pci.h:379
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff815713f4)
Location: drivers/pci/pci.h:379
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81587c8e)
Location: drivers/pci/pci.h:379
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff8157a3ce)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff8157bf83)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff8157eb10)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff815927a4)
Location: drivers/pci/pci.h:413
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a9669)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff8161f4de)
Location: drivers/pci/pci.h:418
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff81621673)
Location: drivers/pci/pci.h:418
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff816241a0)
Location: drivers/pci/pci.h:418
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff816411df)
Location: drivers/pci/pci.h:418
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816522b8)
Location: drivers/pci/pci.h:418
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff81645cce)
Location: drivers/pci/pci.h:401
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff81648203)
Location: drivers/pci/pci.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff81649d60)
Location: drivers/pci/pci.h:401
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff8166762f)
Location: drivers/pci/pci.h:401
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81674c78)
Location: drivers/pci/pci.h:401
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff81628a0e)
Location: drivers/pci/pci.h:396
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff8162ae1b)
Location: drivers/pci/pci.h:396
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff8162c910)
Location: drivers/pci/pci.h:396
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff81649abd)
Location: drivers/pci/pci.h:396
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816571a9)
Location: drivers/pci/pci.h:396
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff8169838e)
Location: drivers/pci/pci.h:417
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff8169a2eb)
Location: drivers/pci/pci.h:417
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff8169bde0)
Location: drivers/pci/pci.h:417
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff816bb978)
Location: drivers/pci/pci.h:417
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c9143)
Location: drivers/pci/pci.h:417
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff817b967e)
Location: drivers/pci/pci.h:378
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff817bb991)
Location: drivers/pci/pci.h:378
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff817bd6f0)
Location: drivers/pci/pci.h:378
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff817dfcf2)
Location: drivers/pci/pci.h:378
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817ef3a4)
Location: drivers/pci/pci.h:378
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff818d429e)
Location: drivers/pci/pci.h:376
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff818d74b1)
Location: drivers/pci/pci.h:376
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff818d9820)
Location: drivers/pci/pci.h:376
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff81902bc2)
Location: drivers/pci/pci.h:376
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819174d5)
Location: drivers/pci/pci.h:376
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff819174ee)
Location: drivers/pci/pci.h:375
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff8191a746)
Location: drivers/pci/pci.h:375
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff8191cb70)
Location: drivers/pci/pci.h:375
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff81946252)
Location: drivers/pci/pci.h:375
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195aaf0)
Location: drivers/pci/pci.h:375
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff8195f5fe)
Location: drivers/pci/pci.h:386
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff81962b46)
Location: drivers/pci/pci.h:386
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff81964fa0)
Location: drivers/pci/pci.h:386
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff8198f582)
Location: drivers/pci/pci.h:386
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_set_acpi_fwnode
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a40e4)
Location: drivers/pci/pci.h:386
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffff8000106dcd28)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffff8000106df564)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffff8000106e160c)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffff8000106f85a4)
Location: drivers/pci/pci.h:413
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff800010712968)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (c08788f8)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (c087b1f0)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (c087d0e0)
Location: drivers/pci/pci.h:413
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
In arch/powerpc/kernel/pci-common.c (c00000000006e2d0)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_devices
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d8660)
Location: drivers/pci/pci.h:413
Inline: True
```
```
In arch/powerpc/platforms/pseries/setup.c (c0000000000ee970)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/setup.c:pseries_pci_fixup_iov_resources
```
```
In drivers/pci/bus.c (c000000000854e80)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (c000000000857fbc)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (c00000000085a754)
Location: drivers/pci/pci.h:413
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
In drivers/pci/bus.c (ffffffe0004b5192)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffe0004b758e)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffe0004b905a)
Location: drivers/pci/pci.h:413
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
In drivers/pci/bus.c (ffffffff8156e8de)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff815704a3)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff81573030)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff81586634)
Location: drivers/pci/pci.h:413
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159ce39)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff8155d04e)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff8155ec03)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff81561790)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff81575404)
Location: drivers/pci/pci.h:413
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158bfc9)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff8156e11e)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff8156fcd3)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff81572860)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff815864f4)
Location: drivers/pci/pci.h:413
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159d3b9)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
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
In drivers/pci/bus.c (ffffffff815885fe)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/bus.c:pci_bus_add_devices
```
```
In drivers/pci/probe.c (ffffffff8158a1b3)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/remove.c (ffffffff8158cd40)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/pci/pci-acpi.c (ffffffff815a09a4)
Location: drivers/pci/pci.h:413
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b77e9)
Location: drivers/pci/pci.h:413
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
</details>
</li>
</ul>

## Differences
