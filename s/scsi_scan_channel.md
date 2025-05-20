# Function: <code>scsi_scan_channel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, int rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff815b3a80)
Location: drivers/scsi/scsi_scan.c:1621
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff815b3a80-ffffffff815b3b18: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8160bee0)
Location: drivers/scsi/scsi_scan.c:1650
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff8160bee0-ffffffff8160bf7c: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8163b780)
Location: drivers/scsi/scsi_scan.c:1644
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff8163b780-ffffffff8163b81c: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8164fe00)
Location: drivers/scsi/scsi_scan.c:1627
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff8164fe00-ffffffff8164fe9c: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816b9510)
Location: drivers/scsi/scsi_scan.c:1633
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff816b9510-ffffffff816b95ac: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816f5a5f)
Location: drivers/scsi/scsi_scan.c:1633
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff816f5860-ffffffff816f58dc: scsi_scan_channel.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81718180)
Location: drivers/scsi/scsi_scan.c:1625
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff81718180-ffffffff8171821c: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff817538c0)
Location: drivers/scsi/scsi_scan.c:1626
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff817538c0-ffffffff81753956: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81777b40)
Location: drivers/scsi/scsi_scan.c:1626
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff81777b40-ffffffff81777bd6: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8183aaa0)
Location: drivers/scsi/scsi_scan.c:1625
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff8183aaa0-ffffffff8183ab36: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8184b470)
Location: drivers/scsi/scsi_scan.c:1625
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff8184b470-ffffffff8184b506: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8182e7e0)
Location: drivers/scsi/scsi_scan.c:1643
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff8182e7e0-ffffffff8182e87a: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff818ba5b0)
Location: drivers/scsi/scsi_scan.c:1652
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff818ba5b0-ffffffff818ba64a: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81a06040)
Location: drivers/scsi/scsi_scan.c:1728
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff81a06040-ffffffff81a060fd: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81b84df0)
Location: drivers/scsi/scsi_scan.c:1728
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff81b84df0-ffffffff81b84ead: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81bd8b70)
Location: drivers/scsi/scsi_scan.c:1740
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff81bd8b70-ffffffff81bd8c2d: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81c2d870)
Location: drivers/scsi/scsi_scan.c:1757
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff81c2d870-ffffffff81c2d92d: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffff80001097c020)
Location: drivers/scsi/scsi_scan.c:1626
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffff80001097c020-ffff80001097c0e0: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c0a4fa08)
Location: drivers/scsi/scsi_scan.c:1626
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
c0a4fa08-c0a4faa4: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c000000000a375d0)
Location: drivers/scsi/scsi_scan.c:1626
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
c000000000a375d0-c000000000a376b0: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffe0005e31f8)
Location: drivers/scsi/scsi_scan.c:1626
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffe0005e31f8-ffffffe0005e328a: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8172c230)
Location: drivers/scsi/scsi_scan.c:1626
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff8172c230-ffffffff8172c2c6: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81705650)
Location: drivers/scsi/scsi_scan.c:1626
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff81705650-ffffffff817056e6: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8176b000)
Location: drivers/scsi/scsi_scan.c:1626
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff8176b000-ffffffff8176b096: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void scsi_scan_channel(struct Scsi_Host *shost, unsigned int channel, unsigned int id, u64 lun, enum scsi_scan_mode rescan);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81786750)
Location: drivers/scsi/scsi_scan.c:1626
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
```
**Symbols:**

```
ffffffff81786750-ffffffff817867e6: scsi_scan_channel (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int rescan</code> ➡️ <code>enum scsi_scan_mode rescan</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
