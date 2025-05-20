# Function: <code>scsi_add_cmd_to_list</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164c250)
Location: drivers/scsi/scsi_lib.c:1123
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff8164c250-ffffffff8164c2ad: scsi_add_cmd_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b4c60)
Location: drivers/scsi/scsi_lib.c:1161
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff816b4c60-ffffffff816b4cbd: scsi_add_cmd_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816f17c0)
Location: drivers/scsi/scsi_lib.c:1197
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff816f17c0-ffffffff816f1824: scsi_add_cmd_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817144e0)
Location: drivers/scsi/scsi_lib.c:1128
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff817144e0-ffffffff81714544: scsi_add_cmd_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174fe40)
Location: drivers/scsi/scsi_lib.c:1093
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff8174fe40-ffffffff8174fea5: scsi_add_cmd_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81774030)
Location: drivers/scsi/scsi_lib.c:1105
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81774030-ffffffff81774095: scsi_add_cmd_to_list (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010977fa8)
Location: drivers/scsi/scsi_lib.c:1105
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffff800010977fa8-ffff800010978080: scsi_add_cmd_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4bea4)
Location: drivers/scsi/scsi_lib.c:1105
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
c0a4bea4-c0a4bf08: scsi_add_cmd_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a32450)
Location: drivers/scsi/scsi_lib.c:1105
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
c000000000a32450-c000000000a324fc: scsi_add_cmd_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005dfb2e)
Location: drivers/scsi/scsi_lib.c:1105
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffe0005dfb2e-ffffffe0005dfba8: scsi_add_cmd_to_list (STB_GLOBAL)
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
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81728720)
Location: drivers/scsi/scsi_lib.c:1105
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81728720-ffffffff81728785: scsi_add_cmd_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81701b50)
Location: drivers/scsi/scsi_lib.c:1105
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81701b50-ffffffff81701bb5: scsi_add_cmd_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817674f0)
Location: drivers/scsi/scsi_lib.c:1105
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff817674f0-ffffffff81767555: scsi_add_cmd_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_add_cmd_to_list(struct scsi_cmnd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81782c10)
Location: drivers/scsi/scsi_lib.c:1105
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81782c10-ffffffff81782c75: scsi_add_cmd_to_list (STB_GLOBAL)
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
