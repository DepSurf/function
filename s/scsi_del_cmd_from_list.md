# Function: <code>scsi_del_cmd_from_list</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164c2b0)
Location: drivers/scsi/scsi_lib.c:1137
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff8164c2b0-ffffffff8164c313: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b4cc0)
Location: drivers/scsi/scsi_lib.c:1175
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff816b4cc0-ffffffff816b4d23: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816f1830)
Location: drivers/scsi/scsi_lib.c:1211
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff816f1830-ffffffff816f1892: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81714550)
Location: drivers/scsi/scsi_lib.c:1142
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff81714550-ffffffff817145b2: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174feb0)
Location: drivers/scsi/scsi_lib.c:1107
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff8174feb0-ffffffff8174ff16: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817740a0)
Location: drivers/scsi/scsi_lib.c:1119
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff817740a0-ffffffff81774106: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010978080)
Location: drivers/scsi/scsi_lib.c:1119
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffff800010978080-ffff800010978168: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4bf08)
Location: drivers/scsi/scsi_lib.c:1119
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
c0a4bf08-c0a4bf7c: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a32500)
Location: drivers/scsi/scsi_lib.c:1119
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
c000000000a32500-c000000000a325b8: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005dfba8)
Location: drivers/scsi/scsi_lib.c:1119
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffe0005dfba8-ffffffe0005dfc18: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81728790)
Location: drivers/scsi/scsi_lib.c:1119
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff81728790-ffffffff817287f6: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81701bc0)
Location: drivers/scsi/scsi_lib.c:1119
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff81701bc0-ffffffff81701c26: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81767560)
Location: drivers/scsi/scsi_lib.c:1119
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff81767560-ffffffff817675c6: scsi_del_cmd_from_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void scsi_del_cmd_from_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81782c80)
Location: drivers/scsi/scsi_lib.c:1119
Inline: True
Direct callers:
  - drivers/scsi/scsi.c:scsi_put_command
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
**Symbols:**

```
ffffffff81782c80-ffffffff81782ce6: scsi_del_cmd_from_list (STB_GLOBAL)
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
