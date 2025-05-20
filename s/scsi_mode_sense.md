# Function: <code>scsi_mode_sense</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815aef60)
Location: drivers/scsi/scsi_lib.c:2419
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff815aef60-ffffffff815af31d: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81607200)
Location: drivers/scsi/scsi_lib.c:2292
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81607200-ffffffff81607572: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816368c0)
Location: drivers/scsi/scsi_lib.c:2333
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff816368c0-ffffffff81636c42: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816493b0)
Location: drivers/scsi/scsi_lib.c:2415
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff816493b0-ffffffff81649726: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b25d0)
Location: drivers/scsi/scsi_lib.c:2493
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff816b25d0-ffffffff816b2946: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ee790)
Location: drivers/scsi/scsi_lib.c:2509
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff816ee790-ffffffff816eeabc: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81712330)
Location: drivers/scsi/scsi_lib.c:2100
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81712330-ffffffff8171265b: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174dca0)
Location: drivers/scsi/scsi_lib.c:2053
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8174dca0-ffffffff8174dfc9: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81771e50)
Location: drivers/scsi/scsi_lib.c:2100
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81771e50-ffffffff81772179: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818363a0)
Location: drivers/scsi/scsi_lib.c:2079
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:get_capabilities
```
**Symbols:**

```
ffffffff818363a0-ffffffff81836726: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81846e70)
Location: drivers/scsi/scsi_lib.c:2087
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:get_capabilities
```
**Symbols:**

```
ffffffff81846e70-ffffffff818471f6: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8182a040)
Location: drivers/scsi/scsi_lib.c:2100
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:get_capabilities
```
**Symbols:**

```
ffffffff8182a040-ffffffff8182a3e3: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b57e0)
Location: drivers/scsi/scsi_lib.c:2090
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:get_capabilities
```
**Symbols:**

```
ffffffff818b57e0-ffffffff818b5abe: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a00cd0)
Location: drivers/scsi/scsi_lib.c:2156
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:get_capabilities
```
**Symbols:**

```
ffffffff81a00cd0-ffffffff81a00fc3: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7f130)
Location: drivers/scsi/scsi_lib.c:2161
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:get_capabilities
```
**Symbols:**

```
ffffffff81b7f130-ffffffff81b7f423: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, int subpage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd30f0)
Location: drivers/scsi/scsi_lib.c:2171
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_cdl_enable
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:get_capabilities
```
**Symbols:**

```
ffffffff81bd30f0-ffffffff81bd3403: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, int subpage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c27d70)
Location: drivers/scsi/scsi_lib.c:2168
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_cdl_enable
  - drivers/scsi/sd.c:sd_read_app_tag_own
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:get_capabilities
```
**Symbols:**

```
ffffffff81c27d70-ffffffff81c28083: scsi_mode_sense (STB_GLOBAL)
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
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff8000109755f8)
Location: drivers/scsi/scsi_lib.c:2100
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffff8000109755f8-ffff800010975958: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a49b44)
Location: drivers/scsi/scsi_lib.c:2100
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
c0a49b44-c0a49ed0: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a2f380)
Location: drivers/scsi/scsi_lib.c:2100
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
c000000000a2f380-c000000000a2f7a4: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005ddbdc)
Location: drivers/scsi/scsi_lib.c:2100
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffe0005ddbdc-ffffffe0005ddec8: scsi_mode_sense (STB_GLOBAL)
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
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81726540)
Location: drivers/scsi/scsi_lib.c:2100
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81726540-ffffffff81726869: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ff970)
Location: drivers/scsi/scsi_lib.c:2100
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff816ff970-ffffffff816ffc99: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81765310)
Location: drivers/scsi/scsi_lib.c:2100
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81765310-ffffffff81765639: scsi_mode_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_mode_sense(struct scsi_device *sdev, int dbd, int modepage, unsigned char *buffer, int len, int timeout, int retries, struct scsi_mode_data *data, struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817809a0)
Location: drivers/scsi/scsi_lib.c:2100
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:sd_read_cache_type
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff817809a0-ffffffff81780cc9: scsi_mode_sense (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int subpage</code>
</li>
<li>
<b>Param reordered. </b>
<code>sdev, dbd, modepage, buffer, len, timeout, retries, data, sshdr</code> ➡️ <code>sdev, dbd, modepage, subpage, buffer, len, timeout, retries, data, sshdr</code>
</li>
</ul>
</details>
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
