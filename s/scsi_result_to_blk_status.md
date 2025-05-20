# Function: <code>scsi_result_to_blk_status</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816f03c0)
Location: drivers/scsi/scsi_lib.c:733
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff816f03c0-ffffffff816f045c: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81713b20)
Location: drivers/scsi/scsi_lib.c:640
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81713b20-ffffffff81713bde: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174f3a0)
Location: drivers/scsi/scsi_lib.c:633
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff8174f3a0-ffffffff8174f470: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81773580)
Location: drivers/scsi/scsi_lib.c:633
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81773580-ffffffff81773650: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81834280)
Location: drivers/scsi/scsi_lib.c:617
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81834280-ffffffff8183434d: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81844c00)
Location: drivers/scsi/scsi_lib.c:620
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81844c00-ffffffff81844ccd: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8182a510)
Location: drivers/scsi/scsi_lib.c:587
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff8182a510-ffffffff8182a5f8: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b4f80)
Location: drivers/scsi/scsi_lib.c:592
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff818b4f80-ffffffff818b5074: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff819fff10)
Location: drivers/scsi/scsi_lib.c:594
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff819fff10-ffffffff81a0003f: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7f6a0)
Location: drivers/scsi/scsi_lib.c:593
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81b7f6a0-ffffffff81b7f73f: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd29f0)
Location: drivers/scsi/scsi_lib.c:590
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81bd29f0-ffffffff81bd2a76: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c27660)
Location: drivers/scsi/scsi_lib.c:588
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81c27660-ffffffff81c276e6: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010976a20)
Location: drivers/scsi/scsi_lib.c:633
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffff800010976a20-ffff800010976b2c: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4b350)
Location: drivers/scsi/scsi_lib.c:633
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
c0a4b350-c0a4b44c: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a313e0)
Location: drivers/scsi/scsi_lib.c:633
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
c000000000a313e0-c000000000a31548: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005df024)
Location: drivers/scsi/scsi_lib.c:633
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffe0005df024-ffffffe0005df124: scsi_result_to_blk_status (STB_LOCAL)
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
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81727c70)
Location: drivers/scsi/scsi_lib.c:633
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81727c70-ffffffff81727d40: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817010a0)
Location: drivers/scsi/scsi_lib.c:633
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff817010a0-ffffffff81701170: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81766a40)
Location: drivers/scsi/scsi_lib.c:633
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81766a40-ffffffff81766b10: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
blk_status_t scsi_result_to_blk_status(struct scsi_cmnd *cmd, int result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81782150)
Location: drivers/scsi/scsi_lib.c:633
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81782150-ffffffff81782220: scsi_result_to_blk_status (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct scsi_cmnd *cmd</code>
</li>
<li>
<b>Param reordered. </b>
<code>cmd, result</code> ➡️ <code>result</code>
</li>
</ul>
</details>
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
