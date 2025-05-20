# Function: <code>scsi_destroy_command_freelist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_destroy_command_freelist(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a7910)
Location: drivers/scsi/scsi.c:454
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_host_dev_release
```
**Symbols:**

```
ffffffff815a7910-ffffffff815a7974: scsi_destroy_command_freelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_destroy_command_freelist(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815ff700)
Location: drivers/scsi/scsi.c:454
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
**Symbols:**

```
ffffffff815ff700-ffffffff815ff768: scsi_destroy_command_freelist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_destroy_command_freelist(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162ed60)
Location: drivers/scsi/scsi.c:454
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
**Symbols:**

```
ffffffff8162ed60-ffffffff8162edc8: scsi_destroy_command_freelist (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
