# Function: <code>scsi_log_print_sense_hdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff815b84c0)
Location: drivers/scsi/scsi_logging.c:365
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff815b84c0-ffffffff815b87a5: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81610d40)
Location: drivers/scsi/scsi_logging.c:365
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff81610d40-ffffffff81611021: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816405d0)
Location: drivers/scsi/scsi_logging.c:365
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff816405d0-ffffffff816408b1: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81654fb0)
Location: drivers/scsi/scsi_logging.c:365
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff81654fb0-ffffffff81655292: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816be500)
Location: drivers/scsi/scsi_logging.c:365
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff816be500-ffffffff816be7e2: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816faad0)
Location: drivers/scsi/scsi_logging.c:365
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff816faad0-ffffffff816fadb2: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8171d500)
Location: drivers/scsi/scsi_logging.c:365
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff8171d500-ffffffff8171d7e2: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:364
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff81758ab0-ffffffff81758c2b: scsi_log_print_sense_hdr (STB_LOCAL)
ffffffff8175911f-ffffffff817592a7: scsi_log_print_sense_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:322
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff8177c970-ffffffff8177cac4: scsi_log_print_sense_hdr (STB_LOCAL)
ffffffff8177cffa-ffffffff8177d194: scsi_log_print_sense_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8183fc50)
Location: drivers/scsi/scsi_logging.c:322
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff8183fc50-ffffffff8183fd82: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff818502b0)
Location: drivers/scsi/scsi_logging.c:318
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff818502b0-ffffffff818503e2: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:318
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff818332f0-ffffffff8183347f: scsi_log_print_sense_hdr (STB_LOCAL)
ffffffff81c088df-ffffffff81c08a67: scsi_log_print_sense_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:319
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff818bf340-ffffffff818bf4cf: scsi_log_print_sense_hdr (STB_LOCAL)
ffffffff81d0c9c4-ffffffff81d0cb4c: scsi_log_print_sense_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:318
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff81a0b790-ffffffff81a0b93c: scsi_log_print_sense_hdr (STB_LOCAL)
ffffffff81ed58c0-ffffffff81ed5a37: scsi_log_print_sense_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81b8ba00)
Location: drivers/scsi/scsi_logging.c:318
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff81b8ba00-ffffffff81b8bd0d: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81bdfa00)
Location: drivers/scsi/scsi_logging.c:318
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff81bdfa00-ffffffff81bdfd0f: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81c349a0)
Location: drivers/scsi/scsi_logging.c:318
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff81c349a0-ffffffff81c34d0b: scsi_log_print_sense_hdr (STB_LOCAL)
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
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffff8000109829d0)
Location: drivers/scsi/scsi_logging.c:322
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffff8000109829d0-ffff800010982ca4: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c0a553f0)
Location: drivers/scsi/scsi_logging.c:322
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
c0a553f0-c0a556a0: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c000000000a3f170)
Location: drivers/scsi/scsi_logging.c:322
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
c000000000a3f170-c000000000a3f4ec: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffe0005e8210)
Location: drivers/scsi/scsi_logging.c:322
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffe0005e8210-ffffffe0005e84a4: scsi_log_print_sense_hdr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:322
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff81731060-ffffffff817311b4: scsi_log_print_sense_hdr (STB_LOCAL)
ffffffff817316ea-ffffffff81731884: scsi_log_print_sense_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:322
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff8170a480-ffffffff8170a5d4: scsi_log_print_sense_hdr (STB_LOCAL)
ffffffff8170ab0a-ffffffff8170aca4: scsi_log_print_sense_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:322
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff8176fe30-ffffffff8176ff84: scsi_log_print_sense_hdr (STB_LOCAL)
ffffffff817704ba-ffffffff81770654: scsi_log_print_sense_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void scsi_log_print_sense_hdr(const struct scsi_device *sdev, const char *name, int tag, const struct scsi_sense_hdr *sshdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:322
Inline: False
Direct callers:
  - drivers/scsi/scsi_logging.c:scsi_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
```
**Symbols:**

```
ffffffff8178b5d0-ffffffff8178b724: scsi_log_print_sense_hdr (STB_LOCAL)
ffffffff8178bc5a-ffffffff8178bdf4: scsi_log_print_sense_hdr.cold (STB_LOCAL)
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
