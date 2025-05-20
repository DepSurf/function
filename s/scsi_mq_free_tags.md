# Function: <code>scsi_mq_free_tags</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_mq_free_tags(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b81ec0)
Location: drivers/scsi/scsi_lib.c:1993
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81b81ec0-ffffffff81b81eeb: scsi_mq_free_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_mq_free_tags(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd5bd0)
Location: drivers/scsi/scsi_lib.c:1999
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81bd5bd0-ffffffff81bd5bfb: scsi_mq_free_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_mq_free_tags(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c2a820)
Location: drivers/scsi/scsi_lib.c:1996
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81c2a820-ffffffff81c2a84b: scsi_mq_free_tags (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
