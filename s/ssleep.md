# Function: <code>ssleep</code>

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
In init/do_mounts.c (ffffffff81f5a7d0)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff810cfc89)
Location: include/linux/delay.h:50
Inline: True
```
```
In drivers/pci/pci.c (ffffffff814381bd)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff81456852)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/scsi/scsi_error.c (ffffffff815a9a10)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff815c1226)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff81f82773)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff810d4752)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff81483e5d)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff814a3773)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/scsi/scsi_error.c (ffffffff816019bb)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81619966)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff81fbe6cd)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff810db301)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff814a55bd)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff814c53d3)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/scsi/scsi_error.c (ffffffff816310ab)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff8164a5f6)
Location: include/linux/delay.h:50
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff8209e7ff)
Location: include/linux/delay.h:61
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff810da3f6)
Location: include/linux/delay.h:61
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff814af5ae)
Location: include/linux/delay.h:61
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff814cf545)
Location: include/linux/delay.h:61
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/scsi/scsi_error.c (ffffffff81645e89)
Location: include/linux/delay.h:61
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff8165ee1d)
Location: include/linux/delay.h:61
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff826a47fc)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff810e2557)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff814eeace)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff8150f753)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/pci/iov.c:pci_iov_init
```
```
In drivers/scsi/scsi_error.c (ffffffff816aee5c)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff816c842d)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff826cd906)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff810eadd6)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff8151e80e)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff81544c35)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff816eb215)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81704e42)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff828838e4)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff810f6409)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff815345ee)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff8155c002)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff8170ecc5)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81727392)
Location: include/linux/delay.h:62
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff8289a90b)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff810fe9ac)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff81563a9f)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff8158c291)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff8174a465)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81762ad2)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff8289d8f0)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff8110adf8)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff81584d7f)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff815ade44)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff8176e5d5)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81786ac2)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff82cc3eb7)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff81115a60)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff8162b9df)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff816565f3)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff818316cf)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff8184b042)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff82faffe1)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff81bdf28d)
Location: include/linux/delay.h:63
Inline: True
```
```
In drivers/pci/pci.c (ffffffff816516df)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff81676b9c)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff818422df)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff8185b462)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff831ba044)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff81bd13dd)
Location: include/linux/delay.h:63
Inline: True
```
```
In drivers/pci/pci.c (ffffffff8163414f)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff816591b1)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff818254f5)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff8183e452)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff8329a502)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff81ca9f46)
Location: include/linux/delay.h:75
Inline: True
```
```
In drivers/pci/pci.c (ffffffff816a432f)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff816cb06f)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff818b0d75)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff818caf1f)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff834487b2)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff81e5a01a)
Location: include/linux/delay.h:75
Inline: True
```
```
In security/selinux/selinuxfs.c (ffffffff815cf37b)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
```
```
In drivers/pci/pci.c (ffffffff817c6734)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff817f1685)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff819fbdeb)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81a180b5)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff83e6277a)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff81184182)
Location: include/linux/delay.h:75
Inline: True
```
```
In security/selinux/selinuxfs.c (ffffffff8167cf7a)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_checkreqprot
```
```
In drivers/pci/iov.c (ffffffff81919d86)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff81b79f6b)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81b98fe5)
Location: include/linux/delay.h:75
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff83682cbb)
Location: include/linux/delay.h:76
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff836ced12)
Location: include/linux/delay.h:76
Inline: True
Inline callers:
  - kernel/power/hibernate.c:find_resume_device
```
```
In drivers/pci/iov.c (ffffffff8195d3a9)
Location: include/linux/delay.h:76
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcdc7b)
Location: include/linux/delay.h:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81bef546)
Location: include/linux/delay.h:76
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff838b1d93)
Location: include/linux/delay.h:76
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff83900122)
Location: include/linux/delay.h:76
Inline: True
Inline callers:
  - kernel/power/hibernate.c:find_resume_device
```
```
In drivers/pci/iov.c (ffffffff819a69fd)
Location: include/linux/delay.h:76
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff81c2289b)
Location: include/linux/delay.h:76
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81c44ce6)
Location: include/linux/delay.h:76
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffff800011431a40)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In drivers/pci/pci.c (ffff8000106e9404)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffff800010717d6c)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffff800010971fc0)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffff80001098d62c)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
```
```
In drivers/rtc/rtc-mv.c (ffff80001149dee8)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
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
In init/do_mounts.c (c1501a6c)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (c03bd0a0)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (c08843a8)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (c08a249c)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (c0a460ac)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (c0a5f834)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
```
```
In drivers/rtc/rtc-mv.c (c15a0524)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
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
In init/do_mounts.c (c000000001344ed0)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In arch/powerpc/kernel/eeh_driver.c (c00000000004ae50)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_reset_device
```
```
In arch/powerpc/platforms/pseries/mobility.c (c0000000000f4a50)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/mobility.c:migration_store
```
```
In arch/powerpc/platforms/pseries/suspend.c (c000000000104760)
Location: include/linux/delay.h:63
Inline: True
```
```
In drivers/pci/pci.c (c0000000008642d4)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (c0000000008875f0)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (c000000000a2aa20)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (c000000000a4ebbc)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffe0000016ee)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In drivers/pci/pci.c (ffffffe0004bf7ea)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffe0004e0f78)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffe0005daa2e)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffe0005f19b2)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff8288b8f0)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff81103058)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff8157929f)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff815a1611)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff81722cc5)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff8173b1b2)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff8288986d)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff810f42b8)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff815679df)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff815907a4)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff816fc0f5)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff8171ce52)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff8289e8f0)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff811012c8)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff81578acf)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff815a1b94)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff81761a95)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff8177b942)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
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
In init/do_mounts.c (ffffffff8289e8f5)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/power/hibernate.c (ffffffff8110c698)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In drivers/pci/pci.c (ffffffff81592f8f)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_secondary_bus
```
```
In drivers/pci/iov.c (ffffffff815bbf94)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/pci/iov.c:pci_iov_init
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
```
In drivers/scsi/scsi_error.c (ffffffff8177d0f5)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_try_bus_reset
  - drivers/scsi/scsi_error.c:scsi_try_host_reset
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81795772)
Location: include/linux/delay.h:63
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_do_ioctl
```
</details>
</li>
</ul>

## Differences
