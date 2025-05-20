# Function: <code>scsi_host_busy_iter</code>

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
void scsi_host_busy_iter(struct Scsi_Host *shost, bool (*fn)(struct scsi_cmnd *, void *, bool), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8182ef50)
Location: drivers/scsi/hosts.c:705
Inline: False
```
**Symbols:**

```
ffffffff8182ef50-ffffffff8182efa1: scsi_host_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_host_busy_iter(struct Scsi_Host *shost, bool (*fn)(struct scsi_cmnd *, void *, bool), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8183ff70)
Location: drivers/scsi/hosts.c:708
Inline: False
```
**Symbols:**

```
ffffffff8183ff70-ffffffff8183ffc1: scsi_host_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_host_busy_iter(struct Scsi_Host *shost, bool (*fn)(struct scsi_cmnd *, void *, bool), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff818231d0)
Location: drivers/scsi/hosts.c:712
Inline: False
```
**Symbols:**

```
ffffffff818231d0-ffffffff81823221: scsi_host_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_host_busy_iter(struct Scsi_Host *shost, bool (*fn)(struct scsi_cmnd *, void *, bool), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff818adaf0)
Location: drivers/scsi/hosts.c:716
Inline: False
```
**Symbols:**

```
ffffffff818adaf0-ffffffff818adb41: scsi_host_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_host_busy_iter(struct Scsi_Host *shost, bool (*fn)(struct scsi_cmnd *, void *, bool), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff819f8990)
Location: drivers/scsi/hosts.c:718
Inline: False
```
**Symbols:**

```
ffffffff819f8990-ffffffff819f89ed: scsi_host_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_host_busy_iter(struct Scsi_Host *shost, bool (*fn)(struct scsi_cmnd *, void *), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81b76420)
Location: drivers/scsi/hosts.c:732
Inline: False
```
**Symbols:**

```
ffffffff81b76420-ffffffff81b7647d: scsi_host_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_host_busy_iter(struct Scsi_Host *shost, bool (*fn)(struct scsi_cmnd *, void *), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81bca0a0)
Location: drivers/scsi/hosts.c:732
Inline: False
```
**Symbols:**

```
ffffffff81bca0a0-ffffffff81bca0fd: scsi_host_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_host_busy_iter(struct Scsi_Host *shost, bool (*fn)(struct scsi_cmnd *, void *), void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81c1ecd0)
Location: drivers/scsi/hosts.c:732
Inline: False
```
**Symbols:**

```
ffffffff81c1ecd0-ffffffff81c1ed2d: scsi_host_busy_iter (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>bool (*fn)(struct scsi_cmnd *, void *, bool)</code> ➡️ <code>bool (*fn)(struct scsi_cmnd *, void *)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
