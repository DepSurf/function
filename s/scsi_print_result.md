# Function: <code>scsi_print_result</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff815b8970)
Location: drivers/scsi/scsi_logging.c:428
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff815b8970-ffffffff815b8c19: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816111f0)
Location: drivers/scsi/scsi_logging.c:428
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff816111f0-ffffffff81611499: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81640a80)
Location: drivers/scsi/scsi_logging.c:428
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81640a80-ffffffff81640d29: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81655450)
Location: drivers/scsi/scsi_logging.c:428
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff81655450-ffffffff8165569c: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816be9a0)
Location: drivers/scsi/scsi_logging.c:428
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff816be9a0-ffffffff816bebec: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff816faf80)
Location: drivers/scsi/scsi_logging.c:428
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff816faf80-ffffffff816fb1d7: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff8171d9a0)
Location: drivers/scsi/scsi_logging.c:428
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff8171d9a0-ffffffff8171dbf2: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:427
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff817592a7-ffffffff81759313: scsi_print_result.cold (STB_LOCAL)
ffffffff81758de0-ffffffff8175905d: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:385
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff8177cfde-ffffffff8177cffa: scsi_print_result.cold (STB_LOCAL)
ffffffff8177c740-ffffffff8177c963: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:385
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81840669-ffffffff818406ad: scsi_print_result.cold (STB_LOCAL)
ffffffff81840160-ffffffff818403db: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:381
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81c16c4f-ffffffff81c16c93: scsi_print_result.cold (STB_LOCAL)
ffffffff818507c0-ffffffff81850a3b: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:381
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81c08a98-ffffffff81c08ad9: scsi_print_result.cold (STB_LOCAL)
ffffffff81833850-ffffffff81833acb: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:383
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81d0cb7d-ffffffff81d0cbbe: scsi_print_result.cold (STB_LOCAL)
ffffffff818bf890-ffffffff818bfad4: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81a0bdc0)
Location: drivers/scsi/scsi_logging.c:382
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81a0bdc0-ffffffff81a0c063: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81b8b470)
Location: drivers/scsi/scsi_logging.c:382
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81b8b470-ffffffff81b8b6f0: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81bdf470)
Location: drivers/scsi/scsi_logging.c:382
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81bdf470-ffffffff81bdf6f0: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffff81c343c0)
Location: drivers/scsi/scsi_logging.c:382
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
```
**Symbols:**

```
ffffffff81c343c0-ffffffff81c3466d: scsi_print_result (STB_GLOBAL)
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
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffff8000109827b8)
Location: drivers/scsi/scsi_logging.c:385
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffff8000109827b8-ffff8000109829cc: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c0a551c8)
Location: drivers/scsi/scsi_logging.c:385
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
c0a551c8-c0a553f0: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (c000000000a3eed0)
Location: drivers/scsi/scsi_logging.c:385
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
c000000000a3eed0-c000000000a3f16c: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_logging.c (ffffffe0005e8028)
Location: drivers/scsi/scsi_logging.c:385
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffe0005e8028-ffffffe0005e8210: scsi_print_result (STB_GLOBAL)
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
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:385
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff817316ce-ffffffff817316ea: scsi_print_result.cold (STB_LOCAL)
ffffffff81730e30-ffffffff81731053: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:385
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff8170aaee-ffffffff8170ab0a: scsi_print_result.cold (STB_LOCAL)
ffffffff8170a250-ffffffff8170a473: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:385
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff8177049e-ffffffff817704ba: scsi_print_result.cold (STB_LOCAL)
ffffffff8176fc00-ffffffff8176fe23: scsi_print_result (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void scsi_print_result(const struct scsi_cmnd *cmd, const char *msg, int disposition);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_logging.c (0)
Location: drivers/scsi/scsi_logging.c:385
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_log_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion
```
**Symbols:**

```
ffffffff8178bc3e-ffffffff8178bc5a: scsi_print_result.cold (STB_LOCAL)
ffffffff8178b3a0-ffffffff8178b5c3: scsi_print_result (STB_GLOBAL)
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
