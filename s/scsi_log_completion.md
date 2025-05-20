# Function: <code>scsi_log_completion</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a79d0)
Location: drivers/scsi/scsi.c:501
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff815a79d0-ffffffff815a7a72: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815ff7c0)
Location: drivers/scsi/scsi.c:501
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff815ff7c0-ffffffff815ff862: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162ee20)
Location: drivers/scsi/scsi.c:501
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff8162ee20-ffffffff8162eec2: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81643c00)
Location: drivers/scsi/scsi.c:142
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff81643c00-ffffffff81643ca4: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816acd10)
Location: drivers/scsi/scsi.c:142
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff816acd10-ffffffff816acdb4: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e9240)
Location: drivers/scsi/scsi.c:142
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff816e9240-ffffffff816e92de: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170cd30)
Location: drivers/scsi/scsi.c:142
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff8170cd30-ffffffff8170cdd8: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81748410)
Location: drivers/scsi/scsi.c:138
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff81748410-ffffffff817484bc: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176c560)
Location: drivers/scsi/scsi.c:138
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff8176c560-ffffffff8176c60c: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182e860)
Location: drivers/scsi/scsi.c:124
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff8182e860-ffffffff8182e90c: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183f8a0)
Location: drivers/scsi/scsi.c:124
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff8183f8a0-ffffffff8183f94c: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81822b00)
Location: drivers/scsi/scsi.c:124
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_complete
```
**Symbols:**

```
ffffffff81822b00-ffffffff81822bac: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818ad440)
Location: drivers/scsi/scsi.c:124
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_complete
```
**Symbols:**

```
ffffffff818ad440-ffffffff818ad4f0: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f8110)
Location: drivers/scsi/scsi.c:115
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_complete
```
**Symbols:**

```
ffffffff819f8110-ffffffff819f81e3: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b75ad0)
Location: drivers/scsi/scsi.c:115
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_complete
```
**Symbols:**

```
ffffffff81b75ad0-ffffffff81b75ba3: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc93f0)
Location: drivers/scsi/scsi.c:115
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_complete
```
**Symbols:**

```
ffffffff81bc93f0-ffffffff81bc94c9: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1dfe0)
Location: drivers/scsi/scsi.c:115
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_lib.c:scsi_complete
  - drivers/scsi/scsi_lib.c:scsi_complete
```
**Symbols:**

```
ffffffff81c1dfe0-ffffffff81c1e0b9: scsi_log_completion (STB_GLOBAL)
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
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096eb38)
Location: drivers/scsi/scsi.c:138
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffff80001096eb38-ffff80001096ec18: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a43fa8)
Location: drivers/scsi/scsi.c:138
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
c0a43fa8-c0a44088: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a27ea0)
Location: drivers/scsi/scsi.c:138
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
c000000000a27ea0-c000000000a27fd0: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d8d06)
Location: drivers/scsi/scsi.c:138
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffe0005d8d06-ffffffe0005d8dd2: scsi_log_completion (STB_GLOBAL)
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
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81720c50)
Location: drivers/scsi/scsi.c:138
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff81720c50-ffffffff81720cfc: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816fa080)
Location: drivers/scsi/scsi.c:138
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff816fa080-ffffffff816fa12c: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175fa20)
Location: drivers/scsi/scsi.c:138
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff8175fa20-ffffffff8175facc: scsi_log_completion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_log_completion(struct scsi_cmnd *cmd, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177b080)
Location: drivers/scsi/scsi.c:138
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff8177b080-ffffffff8177b12c: scsi_log_completion (STB_GLOBAL)
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
