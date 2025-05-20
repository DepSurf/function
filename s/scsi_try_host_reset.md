# Function: <code>scsi_try_host_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff815a9a40)
Location: drivers/scsi/scsi_error.c:749
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff815a9a40-ffffffff815a9b1b: scsi_try_host_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816019f0)
Location: drivers/scsi/scsi_error.c:750
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff816019f0-ffffffff81601ad6: scsi_try_host_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816310e0)
Location: drivers/scsi/scsi_error.c:750
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff816310e0-ffffffff816311c6: scsi_try_host_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81645ed0)
Location: drivers/scsi/scsi_error.c:735
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff81645ed0-ffffffff81645fbf: scsi_try_host_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816aeea0)
Location: drivers/scsi/scsi_error.c:761
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff816aeea0-ffffffff816aef92: scsi_try_host_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816eb250)
Location: drivers/scsi/scsi_error.c:789
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff816eb250-ffffffff816eb340: scsi_try_host_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8170ed00)
Location: drivers/scsi/scsi_error.c:786
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff8170ed00-ffffffff8170edf0: scsi_try_host_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:787
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff8174a4a0-ffffffff8174a571: scsi_try_host_reset (STB_LOCAL)
ffffffff8174d6cd-ffffffff8174d6ec: scsi_try_host_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:787
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff8176e610-ffffffff8176e6e1: scsi_try_host_reset (STB_LOCAL)
ffffffff8177184d-ffffffff8177186c: scsi_try_host_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:787
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_eh_host_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff81831540-ffffffff8183160b: scsi_try_host_reset (STB_LOCAL)
ffffffff81833faa-ffffffff81833fc9: scsi_try_host_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:795
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_eh_host_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff81842150-ffffffff8184221b: scsi_try_host_reset (STB_LOCAL)
ffffffff81c16672-ffffffff81c16691: scsi_try_host_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
enum scsi_disposition scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:807
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff81825350-ffffffff81825421: scsi_try_host_reset (STB_LOCAL)
ffffffff81c0834b-ffffffff81c0836a: scsi_try_host_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum scsi_disposition scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:826
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff818b0bd0-ffffffff818b0ca1: scsi_try_host_reset (STB_LOCAL)
ffffffff81d0c205-ffffffff81d0c224: scsi_try_host_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum scsi_disposition scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:831
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff819fbc00-ffffffff819fbcfa: scsi_try_host_reset (STB_LOCAL)
ffffffff81ed511b-ffffffff81ed513a: scsi_try_host_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum scsi_disposition scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b79d50)
Location: drivers/scsi/scsi_error.c:838
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff81b79d50-ffffffff81b79e69: scsi_try_host_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum scsi_disposition scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bcda60)
Location: drivers/scsi/scsi_error.c:871
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff81bcda60-ffffffff81bcdb79: scsi_try_host_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum scsi_disposition scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c22680)
Location: drivers/scsi/scsi_error.c:873
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff81c22680-ffffffff81c22799: scsi_try_host_reset (STB_LOCAL)
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
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffff800010971cf8)
Location: drivers/scsi/scsi_error.c:787
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffff800010971cf8-ffff800010971e78: scsi_try_host_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c0a460dc)
Location: drivers/scsi/scsi_error.c:787
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
c0a460dc-c0a461dc: scsi_try_host_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c000000000a2aa70)
Location: drivers/scsi/scsi_error.c:787
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
c000000000a2aa70-c000000000a2ac10: scsi_try_host_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffe0005daa60)
Location: drivers/scsi/scsi_error.c:787
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffe0005daa60-ffffffe0005dab3e: scsi_try_host_reset (STB_LOCAL)
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
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:787
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff81722d00-ffffffff81722dd1: scsi_try_host_reset (STB_LOCAL)
ffffffff81725f3d-ffffffff81725f5c: scsi_try_host_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:787
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff816fc130-ffffffff816fc201: scsi_try_host_reset (STB_LOCAL)
ffffffff816ff36d-ffffffff816ff38c: scsi_try_host_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:787
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff81761ad0-ffffffff81761ba1: scsi_try_host_reset (STB_LOCAL)
ffffffff81764d0d-ffffffff81764d2c: scsi_try_host_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int scsi_try_host_reset(struct scsi_cmnd *scmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:787
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_ioctl_reset
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
**Symbols:**

```
ffffffff8177d130-ffffffff8177d201: scsi_try_host_reset (STB_LOCAL)
ffffffff8178038d-ffffffff817803ac: scsi_try_host_reset.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>enum scsi_disposition</code>
</li>
</ul>
</details>
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
