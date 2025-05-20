# Function: <code>scsi_enable_async_suspend</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void scsi_enable_async_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81a04eb8)
Location: drivers/scsi/scsi_scan.c:128
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
Direct callers:
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
```
**Symbols:**

```
ffffffff81a05920-ffffffff81a05966: scsi_enable_async_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void scsi_enable_async_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81b83b68)
Location: drivers/scsi/scsi_scan.c:128
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
Direct callers:
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
```
**Symbols:**

```
ffffffff81b84660-ffffffff81b846a6: scsi_enable_async_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void scsi_enable_async_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81bd78c3)
Location: drivers/scsi/scsi_scan.c:128
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
Direct callers:
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
```
**Symbols:**

```
ffffffff81bd83d0-ffffffff81bd8416: scsi_enable_async_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_enable_async_suspend(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81c2c563)
Location: drivers/scsi/scsi_scan.c:128
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
Direct callers:
  - drivers/scsi/hosts.c:scsi_host_alloc
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_device_initialize
```
**Symbols:**

```
ffffffff81c2d0a0-ffffffff81c2d0e6: scsi_enable_async_suspend (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
