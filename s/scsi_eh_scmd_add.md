# Function: <code>scsi_eh_scmd_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_eh_scmd_add(struct scsi_cmnd *scmd, int eh_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff815abc40)
Location: drivers/scsi/scsi_error.c:231
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff815abc40-ffffffff815abd3e: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_eh_scmd_add(struct scsi_cmnd *scmd, int eh_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81603b60)
Location: drivers/scsi/scsi_error.c:231
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff81603b60-ffffffff81603c5c: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_eh_scmd_add(struct scsi_cmnd *scmd, int eh_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81633240)
Location: drivers/scsi/scsi_error.c:231
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff81633240-ffffffff8163333c: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81647fd0)
Location: drivers/scsi/scsi_error.c:227
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff81647fd0-ffffffff816480ce: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816b1090)
Location: drivers/scsi/scsi_error.c:239
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff816b1090-ffffffff816b1196: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816ed3b0)
Location: drivers/scsi/scsi_error.c:247
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff816ed3b0-ffffffff816ed4bb: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81710ee0)
Location: drivers/scsi/scsi_error.c:247
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff81710ee0-ffffffff81710feb: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8174c300)
Location: drivers/scsi/scsi_error.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff8174c300-ffffffff8174c410: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81770480)
Location: drivers/scsi/scsi_error.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff81770480-ffffffff81770590: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81832d70)
Location: drivers/scsi/scsi_error.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff81832d70-ffffffff81832e80: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81843970)
Location: drivers/scsi/scsi_error.c:256
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff81843970-ffffffff81843a7d: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81826b20)
Location: drivers/scsi/scsi_error.c:268
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_complete
```
**Symbols:**

```
ffffffff81826b20-ffffffff81826c2d: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff818b2470)
Location: drivers/scsi/scsi_error.c:293
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_complete
```
**Symbols:**

```
ffffffff818b2470-ffffffff818b257c: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff819fd520)
Location: drivers/scsi/scsi_error.c:292
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_complete
```
**Symbols:**

```
ffffffff819fd520-ffffffff819fd632: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b7b910)
Location: drivers/scsi/scsi_error.c:297
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_complete
```
**Symbols:**

```
ffffffff81b7b910-ffffffff81b7ba22: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bcf620)
Location: drivers/scsi/scsi_error.c:297
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_complete
```
**Symbols:**

```
ffffffff81bcf620-ffffffff81bcf732: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c24260)
Location: drivers/scsi/scsi_error.c:298
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_complete
```
**Symbols:**

```
ffffffff81c24260-ffffffff81c24392: scsi_eh_scmd_add (STB_GLOBAL)
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
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffff8000109737b8)
Location: drivers/scsi/scsi_error.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffff8000109737b8-ffff800010973924: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c0a482dc)
Location: drivers/scsi/scsi_error.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
c0a482dc-c0a48438: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c000000000a2d330)
Location: drivers/scsi/scsi_error.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
c000000000a2d330-c000000000a2d498: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffe0005dc6b0)
Location: drivers/scsi/scsi_error.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffe0005dc6b0-ffffffe0005dc786: scsi_eh_scmd_add (STB_GLOBAL)
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
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81724b70)
Location: drivers/scsi/scsi_error.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff81724b70-ffffffff81724c80: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816fdfa0)
Location: drivers/scsi/scsi_error.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff816fdfa0-ffffffff816fe0b0: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81763940)
Location: drivers/scsi/scsi_error.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff81763940-ffffffff81763a50: scsi_eh_scmd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_eh_scmd_add(struct scsi_cmnd *scmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8177efa0)
Location: drivers/scsi/scsi_error.c:248
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_lib.c:scsi_softirq_done
```
**Symbols:**

```
ffffffff8177efa0-ffffffff8177f0b0: scsi_eh_scmd_add (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int eh_flag</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
