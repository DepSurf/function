# Function: <code>scsi_device_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff815b1380)
Location: drivers/scsi/scsi_common.c:44
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff815b1380-ffffffff815b13b9: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81609600)
Location: drivers/scsi/scsi_common.c:44
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff81609600-ffffffff81609639: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81638ee0)
Location: drivers/scsi/scsi_common.c:44
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff81638ee0-ffffffff81638f19: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8164db50)
Location: drivers/scsi/scsi_common.c:44
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff8164db50-ffffffff8164db89: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff816b6e20)
Location: drivers/scsi/scsi_common.c:45
Inline: True
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff816b6e20-ffffffff816b6e59: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff816f3040)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff816f3040-ffffffff816f3079: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8171e9a0)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff8171e9a0-ffffffff8171e9d9: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8175a090)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff8175a090-ffffffff8175a0c9: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8177dfa0)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff8177dfa0-ffffffff8177dfd9: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81841530)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
```
**Symbols:**

```
ffffffff81841530-ffffffff81841569: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81851a50)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
```
**Symbols:**

```
ffffffff81851a50-ffffffff81851a89: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81834ae0)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
```
**Symbols:**

```
ffffffff81834ae0-ffffffff81834b19: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff818c0e30)
Location: drivers/scsi/scsi_common.c:54
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
```
**Symbols:**

```
ffffffff818c0e30-ffffffff818c0e82: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81a0d510)
Location: drivers/scsi/scsi_common.c:54
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
```
**Symbols:**

```
ffffffff81a0d510-ffffffff81a0d572: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81b8d390)
Location: drivers/scsi/scsi_common.c:54
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
```
**Symbols:**

```
ffffffff81b8d390-ffffffff81b8d3f2: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81be13a0)
Location: drivers/scsi/scsi_common.c:55
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
```
**Symbols:**

```
ffffffff81be13a0-ffffffff81be1402: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81c363d0)
Location: drivers/scsi/scsi_common.c:55
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
```
**Symbols:**

```
ffffffff81c363d0-ffffffff81c36432: scsi_device_type (STB_GLOBAL)
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
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffff8000109844a8)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffff8000109844a8-ffff80001098452c: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (c0a56ac8)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
c0a56ac8-c0a56b28: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (c000000000a41360)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
c000000000a41360-c000000000a413bc: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffe0005e92aa)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffe0005e92aa-ffffffe0005e9304: scsi_device_type (STB_GLOBAL)
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
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81732690)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff81732690-ffffffff817326c9: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8170bab0)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff8170bab0-ffffffff8170bae9: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81771460)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff81771460-ffffffff81771499: scsi_device_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *scsi_device_type(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8178cc00)
Location: drivers/scsi/scsi_common.c:45
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_proc.c:scsi_seq_show
```
**Symbols:**

```
ffffffff8178cc00-ffffffff8178cc39: scsi_device_type (STB_GLOBAL)
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
