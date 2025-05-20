# Function: <code>scsi_autopm_put_host</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff815b9390)
Location: drivers/scsi/scsi_pm.c:328
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:__scsi_add_device
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:do_scan_async
```
**Symbols:**

```
ffffffff815b9390-ffffffff815b93ac: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81611ca0)
Location: drivers/scsi/scsi_pm.c:338
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81611ca0-ffffffff81611cbc: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81641530)
Location: drivers/scsi/scsi_pm.c:338
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81641530-ffffffff8164154c: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81655e00)
Location: drivers/scsi/scsi_pm.c:338
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81655e00-ffffffff81655e1c: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff816bf3b0)
Location: drivers/scsi/scsi_pm.c:338
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff816bf3b0-ffffffff816bf3cc: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff816fb9d0)
Location: drivers/scsi/scsi_pm.c:338
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff816fb9d0-ffffffff816fb9ec: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8171e3b0)
Location: drivers/scsi/scsi_pm.c:343
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff8171e3b0-ffffffff8171e3cc: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81759aa0)
Location: drivers/scsi/scsi_pm.c:340
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81759aa0-ffffffff81759abc: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8177d9b0)
Location: drivers/scsi/scsi_pm.c:339
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff8177d9b0-ffffffff8177d9cc: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81840f20)
Location: drivers/scsi/scsi_pm.c:345
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81840f20-ffffffff81840f3c: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81851440)
Location: drivers/scsi/scsi_pm.c:339
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81851440-ffffffff8185145c: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff818344d0)
Location: drivers/scsi/scsi_pm.c:339
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff818344d0-ffffffff818344ec: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff818c04d0)
Location: drivers/scsi/scsi_pm.c:339
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff818c04d0-ffffffff818c04ec: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81a0cb30)
Location: drivers/scsi/scsi_pm.c:257
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81a0cb30-ffffffff81a0cb56: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81b8c8c0)
Location: drivers/scsi/scsi_pm.c:257
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81b8c8c0-ffffffff81b8c8e6: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81be08d0)
Location: drivers/scsi/scsi_pm.c:257
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81be08d0-ffffffff81be08f6: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81c35900)
Location: drivers/scsi/scsi_pm.c:257
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81c35900-ffffffff81c35926: scsi_autopm_put_host (STB_GLOBAL)
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
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffff800010983ce8)
Location: drivers/scsi/scsi_pm.c:339
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffff800010983ce8-ffff800010983d18: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (c0a56470)
Location: drivers/scsi/scsi_pm.c:339
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
c0a56470-c0a56494: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (c000000000a40920)
Location: drivers/scsi/scsi_pm.c:339
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
c000000000a40920-c000000000a4095c: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffe0005e8c92)
Location: drivers/scsi/scsi_pm.c:339
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffe0005e8c92-ffffffe0005e8cc0: scsi_autopm_put_host (STB_GLOBAL)
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
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff817320a0)
Location: drivers/scsi/scsi_pm.c:339
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff817320a0-ffffffff817320bc: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8170b4c0)
Location: drivers/scsi/scsi_pm.c:339
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff8170b4c0-ffffffff8170b4dc: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff81770e70)
Location: drivers/scsi/scsi_pm.c:339
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff81770e70-ffffffff81770e8c: scsi_autopm_put_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_autopm_put_host(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_pm.c (ffffffff8178c610)
Location: drivers/scsi/scsi_pm.c:339
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_scan.c:do_scan_async
  - drivers/scsi/scsi_scan.c:scsi_scan_host_selected
  - drivers/scsi/scsi_scan.c:scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff8178c610-ffffffff8178c62c: scsi_autopm_put_host (STB_GLOBAL)
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
