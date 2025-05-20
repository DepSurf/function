# Function: <code>scsi_host_complete_all_commands</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_host_complete_all_commands(struct Scsi_Host *shost, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8182ef20)
Location: drivers/scsi/hosts.c:675
Inline: False
```
**Symbols:**

```
ffffffff8182ef20-ffffffff8182ef49: scsi_host_complete_all_commands (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_host_complete_all_commands(struct Scsi_Host *shost, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8183ff40)
Location: drivers/scsi/hosts.c:678
Inline: False
```
**Symbols:**

```
ffffffff8183ff40-ffffffff8183ff69: scsi_host_complete_all_commands (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_host_complete_all_commands(struct Scsi_Host *shost, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff818231a0)
Location: drivers/scsi/hosts.c:682
Inline: False
```
**Symbols:**

```
ffffffff818231a0-ffffffff818231c9: scsi_host_complete_all_commands (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_host_complete_all_commands(struct Scsi_Host *shost, enum scsi_host_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff818adac0)
Location: drivers/scsi/hosts.c:685
Inline: False
```
**Symbols:**

```
ffffffff818adac0-ffffffff818adae9: scsi_host_complete_all_commands (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_host_complete_all_commands(struct Scsi_Host *shost, enum scsi_host_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff819f8950)
Location: drivers/scsi/hosts.c:687
Inline: False
```
**Symbols:**

```
ffffffff819f8950-ffffffff819f8983: scsi_host_complete_all_commands (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_host_complete_all_commands(struct Scsi_Host *shost, enum scsi_host_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81b763d0)
Location: drivers/scsi/hosts.c:702
Inline: False
```
**Symbols:**

```
ffffffff81b763d0-ffffffff81b76403: scsi_host_complete_all_commands (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_host_complete_all_commands(struct Scsi_Host *shost, enum scsi_host_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81bca050)
Location: drivers/scsi/hosts.c:702
Inline: False
```
**Symbols:**

```
ffffffff81bca050-ffffffff81bca083: scsi_host_complete_all_commands (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_host_complete_all_commands(struct Scsi_Host *shost, enum scsi_host_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81c1ec80)
Location: drivers/scsi/hosts.c:702
Inline: False
```
**Symbols:**

```
ffffffff81c1ec80-ffffffff81c1ecb3: scsi_host_complete_all_commands (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int status</code> ➡️ <code>enum scsi_host_status status</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
