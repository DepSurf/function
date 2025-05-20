# Function: <code>sd_set_flush_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff815ba4a0)
Location: drivers/scsi/sd.c:138
Inline: False
Direct callers:
  - drivers/scsi/sd.c:cache_type_store
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff815ba4a0-ffffffff815ba4de: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81612be0)
Location: drivers/scsi/sd.c:138
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81612be0-ffffffff81612c1b: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81642420)
Location: drivers/scsi/sd.c:140
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81642420-ffffffff8164245b: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81656c40)
Location: drivers/scsi/sd.c:142
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81656c40-ffffffff81656c7b: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816c0100)
Location: drivers/scsi/sd.c:142
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff816c0100-ffffffff816c013b: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816fc6b0)
Location: drivers/scsi/sd.c:142
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff816fc6b0-ffffffff816fc6eb: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8171f500)
Location: drivers/scsi/sd.c:143
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8171f500-ffffffff8171f53b: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175abe0)
Location: drivers/scsi/sd.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8175abe0-ffffffff8175ac1b: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8177eaf0)
Location: drivers/scsi/sd.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8177eaf0-ffffffff8177eb2b: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8184794c)
Location: drivers/scsi/sd.c:142
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81857fef)
Location: drivers/scsi/sd.c:142
Inline: True
Inline callers:
  - drivers/scsi/sd.c:cache_type_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8183af81)
Location: drivers/scsi/sd.c:142
Inline: True
Inline callers:
  - drivers/scsi/sd.c:cache_type_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c764b)
Location: drivers/scsi/sd.c:141
Inline: True
Inline callers:
  - drivers/scsi/sd.c:cache_type_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81a1435b)
Location: drivers/scsi/sd.c:133
Inline: True
Inline callers:
  - drivers/scsi/sd.c:cache_type_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81b9475b)
Location: drivers/scsi/sd.c:133
Inline: True
Inline callers:
  - drivers/scsi/sd.c:cache_type_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81beacac)
Location: drivers/scsi/sd.c:133
Inline: True
Inline callers:
  - drivers/scsi/sd.c:cache_type_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81c402fc)
Location: drivers/scsi/sd.c:121
Inline: True
Inline callers:
  - drivers/scsi/sd.c:cache_type_store
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
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff800010985360)
Location: drivers/scsi/sd.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffff800010985360-ffff8000109853c0: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a579b4)
Location: drivers/scsi/sd.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
c0a579b4-c0a579ec: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a44500)
Location: drivers/scsi/sd.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
c000000000a44500-c000000000a44578: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005e9f88)
Location: drivers/scsi/sd.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffe0005e9f88-ffffffe0005e9fd0: sd_set_flush_flag (STB_LOCAL)
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
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817331e0)
Location: drivers/scsi/sd.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff817331e0-ffffffff8173321b: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81714e80)
Location: drivers/scsi/sd.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81714e80-ffffffff81714ebb: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81773970)
Location: drivers/scsi/sd.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff81773970-ffffffff817739ab: sd_set_flush_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sd_set_flush_flag(struct scsi_disk *sdkp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8178d750)
Location: drivers/scsi/sd.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
```
**Symbols:**

```
ffffffff8178d750-ffffffff8178d78b: sd_set_flush_flag (STB_LOCAL)
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
