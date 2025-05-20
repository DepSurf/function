# Function: <code>scsi_host_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff815a82f0)
Location: drivers/scsi/hosts.c:595
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_unregister
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_host_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff815a82f0-ffffffff815a8307: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816001ad)
Location: drivers/scsi/hosts.c:607
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_unregister
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_host_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81600180-ffffffff81600197: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8162f88d)
Location: drivers/scsi/hosts.c:611
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_unregister
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_host_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8162f860-ffffffff8162f877: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816442cd)
Location: drivers/scsi/hosts.c:599
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_unregister
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_host_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff816442a0-ffffffff816442b7: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816ad27d)
Location: drivers/scsi/hosts.c:594
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_unregister
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_host_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff816ad250-ffffffff816ad267: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816e9560)
Location: drivers/scsi/hosts.c:570
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff816e9560-ffffffff816e9577: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8170d080)
Location: drivers/scsi/hosts.c:567
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8170d080-ffffffff8170d097: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81748ba0)
Location: drivers/scsi/hosts.c:571
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff81748ba0-ffffffff81748bb7: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8176ccf0)
Location: drivers/scsi/hosts.c:571
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8176ccf0-ffffffff8176cd07: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8182eda0)
Location: drivers/scsi/hosts.c:588
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
```
**Symbols:**

```
ffffffff8182eda0-ffffffff8182edb7: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8183fdc0)
Location: drivers/scsi/hosts.c:591
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
```
**Symbols:**

```
ffffffff8183fdc0-ffffffff8183fdd7: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81823020)
Location: drivers/scsi/hosts.c:595
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
```
**Symbols:**

```
ffffffff81823020-ffffffff81823037: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff818ad940)
Location: drivers/scsi/hosts.c:597
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
```
**Symbols:**

```
ffffffff818ad940-ffffffff818ad957: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff819f87d0)
Location: drivers/scsi/hosts.c:599
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
```
**Symbols:**

```
ffffffff819f87d0-ffffffff819f87ed: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81b76230)
Location: drivers/scsi/hosts.c:614
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
```
**Symbols:**

```
ffffffff81b76230-ffffffff81b7624d: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81bc9ec0)
Location: drivers/scsi/hosts.c:614
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/ata/libata-core.c:ata_devres_release
```
**Symbols:**

```
ffffffff81bc9ec0-ffffffff81bc9edd: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81c1eaf0)
Location: drivers/scsi/hosts.c:614
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/ata/libata-core.c:ata_devres_release
```
**Symbols:**

```
ffffffff81c1eaf0-ffffffff81c1eb0d: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffff80001096eff8)
Location: drivers/scsi/hosts.c:571
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffff80001096eff8-ffff80001096f024: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c0a44368)
Location: drivers/scsi/hosts.c:571
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
c0a44368-c0a44388: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c000000000a288c0)
Location: drivers/scsi/hosts.c:571
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
c000000000a288c0-c000000000a288f8: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffe0005d9126)
Location: drivers/scsi/hosts.c:571
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffe0005d9126-ffffffe0005d9152: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff817213e0)
Location: drivers/scsi/hosts.c:571
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff817213e0-ffffffff817213f7: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816fa810)
Location: drivers/scsi/hosts.c:571
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_transport_fc.c:fc_vport_terminate
  - drivers/scsi/scsi_transport_fc.c:fc_vport_setup
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_create
  - drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete
  - drivers/scsi/storvsc_drv.c:storvsc_remove
  - drivers/scsi/storvsc_drv.c:storvsc_probe
  - drivers/scsi/storvsc_drv.c:storvsc_remove_lun
  - drivers/ata/libata-core.c:ata_devres_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff816fa810-ffffffff816fa827: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff817601b0)
Location: drivers/scsi/hosts.c:571
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/ata/libata-core.c:ata_devres_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff817601b0-ffffffff817601c7: scsi_host_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_host_put(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8177b810)
Location: drivers/scsi/hosts.c:571
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/scsi/scsi_proc.c:proc_scsi_write
  - drivers/ata/libata-core.c:ata_devres_release
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
  - drivers/ata/libata-scsi.c:ata_scsi_add_hosts
```
**Symbols:**

```
ffffffff8177b810-ffffffff8177b827: scsi_host_put (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
