# Function: <code>scsi_eh_action</code>

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
In drivers/scsi/scsi_error.c (ffffffff815aaad8)
Location: drivers/scsi/scsi_error.c:1106
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
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
In drivers/scsi/scsi_error.c (ffffffff81602a5d)
Location: drivers/scsi/scsi_error.c:1107
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
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
In drivers/scsi/scsi_error.c (ffffffff8163214d)
Location: drivers/scsi/scsi_error.c:1107
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81645990)
Location: drivers/scsi/scsi_error.c:1094
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff81645990-ffffffff816459d1: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816ae960)
Location: drivers/scsi/scsi_error.c:1120
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff816ae960-ffffffff816ae9a4: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816ead10)
Location: drivers/scsi/scsi_error.c:1148
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff816ead10-ffffffff816ead53: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8170e7c0)
Location: drivers/scsi/scsi_error.c:1145
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff8170e7c0-ffffffff8170e803: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81749f60)
Location: drivers/scsi/scsi_error.c:1165
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff81749f60-ffffffff81749fa3: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8176e0c0)
Location: drivers/scsi/scsi_error.c:1168
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff8176e0c0-ffffffff8176e103: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81830680)
Location: drivers/scsi/scsi_error.c:1168
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff81830680-ffffffff818306c3: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff818412f0)
Location: drivers/scsi/scsi_error.c:1176
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff818412f0-ffffffff81841330: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum scsi_disposition scsi_eh_action(struct scsi_cmnd *scmd, enum scsi_disposition rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff818244e0)
Location: drivers/scsi/scsi_error.c:1189
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff818244e0-ffffffff81824520: scsi_eh_action (STB_LOCAL)
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
In drivers/scsi/scsi_error.c (ffffffff818b162d)
Location: drivers/scsi/scsi_error.c:1208
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
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
In drivers/scsi/scsi_error.c (ffffffff819fc6ac)
Location: drivers/scsi/scsi_error.c:1213
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
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
In drivers/scsi/scsi_error.c (ffffffff81b7a86c)
Location: drivers/scsi/scsi_error.c:1220
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
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
In drivers/scsi/scsi_error.c (ffffffff81bce57c)
Location: drivers/scsi/scsi_error.c:1253
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
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
In drivers/scsi/scsi_error.c (ffffffff81c2319c)
Location: drivers/scsi/scsi_error.c:1256
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
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
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffff800010970ff8)
Location: drivers/scsi/scsi_error.c:1168
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffff800010970ff8-ffff80001097105c: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c0a45c48)
Location: drivers/scsi/scsi_error.c:1168
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
c0a45c48-c0a45c9c: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c000000000a2a450)
Location: drivers/scsi/scsi_error.c:1168
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
c000000000a2a450-c000000000a2a4c8: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffe0005da61c)
Location: drivers/scsi/scsi_error.c:1168
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffe0005da61c-ffffffe0005da668: scsi_eh_action (STB_LOCAL)
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
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff817227b0)
Location: drivers/scsi/scsi_error.c:1168
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff817227b0-ffffffff817227f3: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816fbbe0)
Location: drivers/scsi/scsi_error.c:1168
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff816fbbe0-ffffffff816fbc23: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81761580)
Location: drivers/scsi/scsi_error.c:1168
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff81761580-ffffffff817615c3: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_eh_action(struct scsi_cmnd *scmd, int rtn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8177cbe0)
Location: drivers/scsi/scsi_error.c:1168
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
**Symbols:**

```
ffffffff8177cbe0-ffffffff8177cc23: scsi_eh_action (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param type changed. </b>
<code>int rtn</code> ➡️ <code>enum scsi_disposition rtn</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>enum scsi_disposition</code>
</li>
</ul>
</details>
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
