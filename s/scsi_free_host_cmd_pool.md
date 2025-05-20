# Function: <code>scsi_free_host_cmd_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_free_host_cmd_pool(struct scsi_host_cmd_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a6400)
Location: drivers/scsi/scsi.c:305
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
```
**Symbols:**

```
ffffffff815a6400-ffffffff815a642a: scsi_free_host_cmd_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_free_host_cmd_pool(struct scsi_host_cmd_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815fe690)
Location: drivers/scsi/scsi.c:305
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
```
**Symbols:**

```
ffffffff815fe690-ffffffff815fe6ba: scsi_free_host_cmd_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_free_host_cmd_pool(struct scsi_host_cmd_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162dc90)
Location: drivers/scsi/scsi.c:305
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
```
**Symbols:**

```
ffffffff8162dc90-ffffffff8162dcba: scsi_free_host_cmd_pool (STB_LOCAL)
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
