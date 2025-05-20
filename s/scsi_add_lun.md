# Function: <code>scsi_add_lun</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff815b245a)
Location: drivers/scsi/scsi_scan.c:765
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8160a8bc)
Location: drivers/scsi/scsi_scan.c:773
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8163a1a4)
Location: drivers/scsi/scsi_scan.c:771
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8164ecb7)
Location: drivers/scsi/scsi_scan.c:771
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816b7f57)
Location: drivers/scsi/scsi_scan.c:772
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816f45d8)
Location: drivers/scsi/scsi_scan.c:772
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81716c01)
Location: drivers/scsi/scsi_scan.c:764
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81751ae0)
Location: drivers/scsi/scsi_scan.c:764
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81751ae0-ffffffff817520a1: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81775d60)
Location: drivers/scsi/scsi_scan.c:764
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81775d60-ffffffff81776321: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81838b80)
Location: drivers/scsi/scsi_scan.c:763
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81838b80-ffffffff8183913e: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81849400)
Location: drivers/scsi/scsi_scan.c:763
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81849400-ffffffff818499be: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8182c830)
Location: drivers/scsi/scsi_scan.c:782
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8182c830-ffffffff8182cdd4: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff818b85f0)
Location: drivers/scsi/scsi_scan.c:788
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff818b85f0-ffffffff818b8ba5: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81a03ea0)
Location: drivers/scsi/scsi_scan.c:857
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81a03ea0-ffffffff81a04496: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81b82a90)
Location: drivers/scsi/scsi_scan.c:857
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81b82a90-ffffffff81b83086: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81bd6790)
Location: drivers/scsi/scsi_scan.c:859
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81bd6790-ffffffff81bd6da1: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81c2b3e0)
Location: drivers/scsi/scsi_scan.c:859
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81c2b3e0-ffffffff81c2ba19: scsi_add_lun (STB_LOCAL)
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
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffff80001097a420)
Location: drivers/scsi/scsi_scan.c:764
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffff80001097a420-ffff80001097a914: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c0a4dd78)
Location: drivers/scsi/scsi_scan.c:764
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
c0a4dd78-c0a4e334: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c000000000a34cf0)
Location: drivers/scsi/scsi_scan.c:764
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
c000000000a34cf0-c000000000a353c0: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffe0005e15c2)
Location: drivers/scsi/scsi_scan.c:764
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffe0005e15c2-ffffffe0005e1aa8: scsi_add_lun (STB_LOCAL)
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
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8172a450)
Location: drivers/scsi/scsi_scan.c:764
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff8172a450-ffffffff8172aa11: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81703870)
Location: drivers/scsi/scsi_scan.c:764
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81703870-ffffffff81703e31: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81769220)
Location: drivers/scsi/scsi_scan.c:764
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81769220-ffffffff817697e1: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_add_lun(struct scsi_device *sdev, unsigned char *inq_result, blist_flags_t *bflags, int async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81784990)
Location: drivers/scsi/scsi_scan.c:764
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
```
**Symbols:**

```
ffffffff81784990-ffffffff81784f51: scsi_add_lun (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
