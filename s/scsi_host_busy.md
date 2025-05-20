# Function: <code>scsi_host_busy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8170cfe0)
Location: drivers/scsi/hosts.c:557
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff8170cfe0-ffffffff8170cff1: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff817486d0)
Location: drivers/scsi/hosts.c:561
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff817486d0-ffffffff817486e1: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8176c820)
Location: drivers/scsi/hosts.c:561
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff8176c820-ffffffff8176c831: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8182eec0)
Location: drivers/scsi/hosts.c:574
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff8182eec0-ffffffff8182ef13: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8183fee0)
Location: drivers/scsi/hosts.c:577
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff8183fee0-ffffffff8183ff33: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81823140)
Location: drivers/scsi/hosts.c:581
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff81823140-ffffffff81823193: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff818ada60)
Location: drivers/scsi/hosts.c:583
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff818ada60-ffffffff818adab3: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff819f88f0)
Location: drivers/scsi/hosts.c:585
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff819f88f0-ffffffff819f894d: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81b76360)
Location: drivers/scsi/hosts.c:600
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff81b76360-ffffffff81b763bd: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81bc9fe0)
Location: drivers/scsi/hosts.c:600
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff81bc9fe0-ffffffff81bca03d: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81c1ec10)
Location: drivers/scsi/hosts.c:600
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_inc_host_failed
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff81c1ec10-ffffffff81c1ec6d: scsi_host_busy (STB_GLOBAL)
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
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffff80001096eed8)
Location: drivers/scsi/hosts.c:561
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffff80001096eed8-ffff80001096ef00: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c0a4429c)
Location: drivers/scsi/hosts.c:561
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
c0a4429c-c0a442b8: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c000000000a282f0)
Location: drivers/scsi/hosts.c:561
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
c000000000a282f0-c000000000a28304: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffe0005d8fda)
Location: drivers/scsi/hosts.c:561
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffe0005d8fda-ffffffe0005d9000: scsi_host_busy (STB_GLOBAL)
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
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81720f10)
Location: drivers/scsi/hosts.c:561
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff81720f10-ffffffff81720f21: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816fa340)
Location: drivers/scsi/hosts.c:561
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff816fa340-ffffffff816fa351: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8175fce0)
Location: drivers/scsi/hosts.c:561
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff8175fce0-ffffffff8175fcf1: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_host_busy(struct Scsi_Host *shost);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8177b340)
Location: drivers/scsi/hosts.c:561
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_sysfs.c:show_host_busy
```
**Symbols:**

```
ffffffff8177b340-ffffffff8177b351: scsi_host_busy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
