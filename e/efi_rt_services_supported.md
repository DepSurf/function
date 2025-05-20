# Function: <code>efi_rt_services_supported</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/platform_certs/load_uefi.c (ffffffff82d07152)
Location: include/linux/efi.h:825
Inline: True
Inline callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
```
In drivers/firmware/efi/efi.c (ffffffff82d29681)
Location: include/linux/efi.h:825
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/reboot.c (ffffffff82d29e07)
Location: include/linux/efi.h:825
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
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
In security/integrity/platform_certs/load_uefi.c (ffffffff82ff4698)
Location: include/linux/efi.h:830
Inline: True
Inline callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
```
In drivers/firmware/efi/efi.c (ffffffff83017d99)
Location: include/linux/efi.h:830
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/reboot.c (ffffffff8301852c)
Location: include/linux/efi.h:830
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
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
In security/integrity/platform_certs/load_uefi.c (ffffffff831ff2e2)
Location: include/linux/efi.h:825
Inline: True
Inline callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
```
In drivers/firmware/efi/efi.c (ffffffff83222c71)
Location: include/linux/efi.h:825
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/reboot.c (ffffffff83223404)
Location: include/linux/efi.h:825
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
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
In security/integrity/platform_certs/load_uefi.c (ffffffff832e66d1)
Location: include/linux/efi.h:825
Inline: True
Inline callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
```
In drivers/firmware/efi/efi.c (ffffffff8330c9d5)
Location: include/linux/efi.h:825
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/reboot.c (ffffffff8330d20a)
Location: include/linux/efi.h:825
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
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
In security/integrity/platform_certs/load_uefi.c (ffffffff8349d716)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
```
In security/integrity/ima/ima_efi.c (ffffffff81648846)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:get_sb_mode
```
```
In drivers/firmware/efi/efi.c (ffffffff834c62d5)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/reboot.c (ffffffff834c6ce7)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
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
In security/integrity/platform_certs/load_uefi.c (ffffffff83ed5302)
Location: include/linux/efi.h:894
Inline: True
Inline callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
```
In security/integrity/ima/ima_efi.c (ffffffff81701586)
Location: include/linux/efi.h:894
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:get_sb_mode
```
```
In drivers/firmware/efi/efi.c (ffffffff83f06f64)
Location: include/linux/efi.h:894
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/reboot.c (ffffffff83f07ee5)
Location: include/linux/efi.h:894
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
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
In security/integrity/platform_certs/load_uefi.c (ffffffff836fa462)
Location: include/linux/efi.h:914
Inline: True
Inline callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
```
In security/integrity/ima/ima_efi.c (ffffffff8173b626)
Location: include/linux/efi.h:914
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:get_sb_mode
```
```
In drivers/firmware/efi/efi.c (ffffffff8372cfbc)
Location: include/linux/efi.h:914
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/reboot.c (ffffffff8372e005)
Location: include/linux/efi.h:914
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
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
In fs/efivarfs/super.c (ffffffff816aec37)
Location: include/linux/efi.h:908
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_statfs
```
```
In security/integrity/platform_certs/load_uefi.c (ffffffff8392d922)
Location: include/linux/efi.h:908
Inline: True
Inline callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
```
```
In security/integrity/ima/ima_efi.c (ffffffff8177c1e6)
Location: include/linux/efi.h:908
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:get_sb_mode
```
```
In drivers/firmware/efi/efi.c (ffffffff839613d9)
Location: include/linux/efi.h:908
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
```
```
In drivers/firmware/efi/reboot.c (ffffffff83962405)
Location: include/linux/efi.h:908
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
