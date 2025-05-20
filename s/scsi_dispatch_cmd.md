# Function: <code>scsi_dispatch_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815adc50)
Location: drivers/scsi/scsi_lib.c:1661
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff815adc50-ffffffff815ade89: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81605b50)
Location: drivers/scsi/scsi_lib.c:1577
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff81605b50-ffffffff81605d5a: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816350e0)
Location: drivers/scsi/scsi_lib.c:1587
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff816350e0-ffffffff816352ea: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164a040)
Location: drivers/scsi/scsi_lib.c:1623
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff8164a040-ffffffff8164a25d: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b3190)
Location: drivers/scsi/scsi_lib.c:1672
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff816b3190-ffffffff816b33bf: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ef3a0)
Location: drivers/scsi/scsi_lib.c:1708
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff816ef3a0-ffffffff816ef5cf: scsi_dispatch_cmd (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff817154de)
Location: drivers/scsi/scsi_lib.c:1521
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81750d5a)
Location: drivers/scsi/scsi_lib.c:1486
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81774fc0)
Location: drivers/scsi/scsi_lib.c:1498
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81835f30)
Location: drivers/scsi/scsi_lib.c:1486
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81835f30-ffffffff8183614d: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818469e0)
Location: drivers/scsi/scsi_lib.c:1470
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff818469e0-ffffffff81846bd9: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81829bb0)
Location: drivers/scsi/scsi_lib.c:1448
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81829bb0-ffffffff81829da9: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b55f0)
Location: drivers/scsi/scsi_lib.c:1452
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff818b55f0-ffffffff818b57e0: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a020a0)
Location: drivers/scsi/scsi_lib.c:1460
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81a020a0-ffffffff81a022c3: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b80790)
Location: drivers/scsi/scsi_lib.c:1462
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81b80790-ffffffff81b809a9: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd4810)
Location: drivers/scsi/scsi_lib.c:1463
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81bd4810-ffffffff81bd4a47: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_dispatch_cmd(struct scsi_cmnd *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c29480)
Location: drivers/scsi/scsi_lib.c:1460
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81c29480-ffffffff81c296b7: scsi_dispatch_cmd (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010979164)
Location: drivers/scsi/scsi_lib.c:1498
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4cf2c)
Location: drivers/scsi/scsi_lib.c:1498
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a33918)
Location: drivers/scsi/scsi_lib.c:1498
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005e091c)
Location: drivers/scsi/scsi_lib.c:1498
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817296b0)
Location: drivers/scsi/scsi_lib.c:1498
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81702ac2)
Location: drivers/scsi/scsi_lib.c:1498
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81768480)
Location: drivers/scsi/scsi_lib.c:1498
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81783ba0)
Location: drivers/scsi/scsi_lib.c:1498
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
