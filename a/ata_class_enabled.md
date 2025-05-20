# Function: <code>ata_class_enabled</code>

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
In drivers/ata/libata-core.c (ffffffff815c7472)
Location: include/linux/libata.h:1514
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_next
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
```
```
In drivers/ata/libata-scsi.c (ffffffff815d19ab)
Location: include/linux/libata.h:1514
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff815d5e5b)
Location: include/linux/libata.h:1514
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-pmp.c (ffffffff815dfd15)
Location: include/linux/libata.h:1514
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff815e1bc4)
Location: include/linux/libata.h:1514
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff816269ea)
Location: include/linux/libata.h:1490
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff8162ae49)
Location: include/linux/libata.h:1490
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff816324a5)
Location: include/linux/libata.h:1490
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffff81639a28)
Location: include/linux/libata.h:1490
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff8163b93c)
Location: include/linux/libata.h:1490
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff8165764a)
Location: include/linux/libata.h:1496
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff8165c0d9)
Location: include/linux/libata.h:1496
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff816635f5)
Location: include/linux/libata.h:1496
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffff8166aab8)
Location: include/linux/libata.h:1496
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff8166c9bc)
Location: include/linux/libata.h:1496
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff8166be5a)
Location: include/linux/libata.h:1499
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff81671739)
Location: include/linux/libata.h:1499
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff81677df3)
Location: include/linux/libata.h:1499
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffff8167f0cb)
Location: include/linux/libata.h:1499
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff81680fd9)
Location: include/linux/libata.h:1499
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff816d54aa)
Location: include/linux/libata.h:1500
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff816dad19)
Location: include/linux/libata.h:1500
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff816e1433)
Location: include/linux/libata.h:1500
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffff816e892b)
Location: include/linux/libata.h:1500
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff816ea846)
Location: include/linux/libata.h:1500
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff8171132b)
Location: include/linux/libata.h:1527
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff81717209)
Location: include/linux/libata.h:1527
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff8171dd53)
Location: include/linux/libata.h:1527
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffff8172524c)
Location: include/linux/libata.h:1527
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff81727193)
Location: include/linux/libata.h:1527
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff817337db)
Location: include/linux/libata.h:1526
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff81739859)
Location: include/linux/libata.h:1526
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffff81740633)
Location: include/linux/libata.h:1526
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffff817479fc)
Location: include/linux/libata.h:1526
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff81749973)
Location: include/linux/libata.h:1526
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff8176f15b)
Location: include/linux/libata.h:1511
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff81775859)
Location: include/linux/libata.h:1511
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff8177c465)
Location: include/linux/libata.h:1511
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffff817838de)
Location: include/linux/libata.h:1511
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff817857e8)
Location: include/linux/libata.h:1511
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff817931cb)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff817997c9)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff8179ffe5)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffff817a754e)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff817a9428)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff818538f3)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-scsi.c (ffffffff8185e8a9)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff81864b1f)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_unload
```
```
In drivers/ata/libata-sata.c (ffffffff818680a0)
Location: include/linux/libata.h:1576
Inline: True
```
```
In drivers/ata/libata-pmp.c (ffffffff8186cf55)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
```
```
In drivers/ata/libata-acpi.c (ffffffff8186ed28)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff81863bc3)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-scsi.c (ffffffff8186d8c9)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff8187391f)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_unload
```
```
In drivers/ata/libata-sata.c (ffffffff81876eb0)
Location: include/linux/libata.h:1576
Inline: True
```
```
In drivers/ata/libata-pmp.c (ffffffff8187bc25)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
  - drivers/ata/libata-pmp.c:sata_pmp_revalidate
```
```
In drivers/ata/libata-acpi.c (ffffffff8187d9f8)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff81846f54)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-scsi.c (ffffffff81850e0d)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-eh.c (ffffffff81856f94)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff818596ad)
Location: include/linux/libata.h:1576
Inline: True
```
```
In drivers/ata/libata-pmp.c (ffffffff8185e3e2)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
```
In drivers/ata/libata-acpi.c (ffffffff81860155)
Location: include/linux/libata.h:1576
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff818d38f5)
Location: include/linux/libata.h:1585
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_runtime_idle
  - drivers/ata/libata-core.c:ata_dev_xfermask
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
```
```
In drivers/ata/libata-scsi.c (ffffffff818de99d)
Location: include/linux/libata.h:1585
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_sas_scsi_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_unlock_native_capacity
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
```
```
In drivers/ata/libata-eh.c (ffffffff818e5834)
Location: include/linux/libata.h:1585
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sata.c (ffffffff818e825d)
Location: include/linux/libata.h:1585
Inline: True
```
```
In drivers/ata/libata-pmp.c (ffffffff818ed102)
Location: include/linux/libata.h:1585
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
```
In drivers/ata/libata-acpi.c (ffffffff818eef15)
Location: include/linux/libata.h:1585
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1581
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/libata.h:1581
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1581
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/libata.h:1581
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1581
Inline: True
```
```
In drivers/ata/libata-acpi.c (0)
Location: include/linux/libata.h:1581
Inline: True
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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1586
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/libata.h:1586
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1586
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/libata.h:1586
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1586
Inline: True
```
```
In drivers/ata/libata-acpi.c (0)
Location: include/linux/libata.h:1586
Inline: True
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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1605
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/libata.h:1605
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1605
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/libata.h:1605
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1605
Inline: True
```
```
In drivers/ata/libata-acpi.c (0)
Location: include/linux/libata.h:1605
Inline: True
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
In drivers/ata/libata-core.c (0)
Location: include/linux/libata.h:1606
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/libata.h:1606
Inline: True
```
```
In drivers/ata/libata-eh.c (0)
Location: include/linux/libata.h:1606
Inline: True
```
```
In drivers/ata/libata-sata.c (0)
Location: include/linux/libata.h:1606
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/libata.h:1606
Inline: True
```
```
In drivers/ata/libata-acpi.c (0)
Location: include/linux/libata.h:1606
Inline: True
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
In drivers/ata/libata-core.c (ffff80001099d594)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffff8000109a1280)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffff8000109aba14)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffff8000109b3dc8)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffff8000109b603c)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
```
```
In drivers/ata/libahci.c (ffff8000109b8d3c)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_error_handler
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
In drivers/ata/libata-core.c (c0a6dae0)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (c0a7412c)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (c0a7b364)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (c0a82d84)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libahci.c (c0a86050)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_error_handler
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
In drivers/ata/libata-core.c (c000000000a61380)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (c000000000a68d6c)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (c000000000a72ad4)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (c000000000a7cd1c)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffe0005fd86e)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffe0006024e6)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
  - drivers/ata/libata-scsi.c:__ata_change_queue_depth
```
```
In drivers/ata/libata-eh.c (ffffffe000609080)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffe000610424)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
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
In drivers/ata/libata-core.c (ffffffff817582db)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff8175e8b9)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff817650d5)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffff8176c60e)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff8176e4e8)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff8173817b)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff8173e759)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff81744f35)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffff8174c45e)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff8174e338)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff8178804b)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff8178e649)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff81794e65)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffff8179c3ce)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff8179e2a8)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
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
In drivers/ata/libata-core.c (ffffffff817a1e9b)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_next
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8499)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_find_dev
```
```
In drivers/ata/libata-eh.c (ffffffff817aecd5)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
```
In drivers/ata/libata-pmp.c (ffffffff817b624e)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
```
In drivers/ata/libata-acpi.c (ffffffff817b8128)
Location: include/linux/libata.h:1513
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
  - drivers/ata/libata-acpi.c:ata_acpi_on_resume
```
</details>
</li>
</ul>

## Differences
