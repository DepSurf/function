# Function: <code>__traceiter_scsi_dispatch_cmd_error</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_scsi_dispatch_cmd_error(void *__data, struct scsi_cmnd *cmd, int rtn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183e030)
Location: include/trace/events/scsi.h:242
Inline: False
```
**Symbols:**

```
ffffffff8183e030-ffffffff8183e077: __traceiter_scsi_dispatch_cmd_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_scsi_dispatch_cmd_error(void *__data, struct scsi_cmnd *cmd, int rtn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818211d0)
Location: include/trace/events/scsi.h:242
Inline: False
```
**Symbols:**

```
ffffffff818211d0-ffffffff81821215: __traceiter_scsi_dispatch_cmd_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_scsi_dispatch_cmd_error(void *__data, struct scsi_cmnd *cmd, int rtn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818abb20)
Location: include/trace/events/scsi.h:198
Inline: False
```
**Symbols:**

```
ffffffff818abb20-ffffffff818abb65: __traceiter_scsi_dispatch_cmd_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_scsi_dispatch_cmd_error(void *__data, struct scsi_cmnd *cmd, int rtn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f6430)
Location: include/trace/events/scsi.h:198
Inline: False
```
**Symbols:**

```
ffffffff819f6430-ffffffff819f647f: __traceiter_scsi_dispatch_cmd_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_scsi_dispatch_cmd_error(void *__data, struct scsi_cmnd *cmd, int rtn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b73a60)
Location: include/trace/events/scsi.h:202
Inline: False
```
**Symbols:**

```
ffffffff81b73a60-ffffffff81b73aaf: __traceiter_scsi_dispatch_cmd_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_scsi_dispatch_cmd_error(void *__data, struct scsi_cmnd *cmd, int rtn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc71f0)
Location: include/trace/events/scsi.h:202
Inline: False
```
**Symbols:**

```
ffffffff81bc71f0-ffffffff81bc723f: __traceiter_scsi_dispatch_cmd_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_scsi_dispatch_cmd_error(void *__data, struct scsi_cmnd *cmd, int rtn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1bd60)
Location: include/trace/events/scsi.h:202
Inline: False
```
**Symbols:**

```
ffffffff81c1bd60-ffffffff81c1bdaf: __traceiter_scsi_dispatch_cmd_error (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
