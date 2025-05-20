# Function: <code>__ata_port_freeze</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff815d4a60)
Location: drivers/ata/libata-eh.c:1125
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_eh_freeze_port
```
**Symbols:**

```
ffffffff815d4a60-ffffffff815d4aa7: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8162e4f0)
Location: drivers/ata/libata-eh.c:1125
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_freeze_port
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff8162e4f0-ffffffff8162e537: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8165f640)
Location: drivers/ata/libata-eh.c:1125
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_freeze_port
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff8165f640-ffffffff8165f687: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81674090)
Location: drivers/ata/libata-eh.c:1126
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81674090-ffffffff816740c4: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816dd6b0)
Location: drivers/ata/libata-eh.c:1124
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff816dd6b0-ffffffff816dd6e7: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81719e60)
Location: drivers/ata/libata-eh.c:1075
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81719e60-ffffffff81719e97: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8173c760)
Location: drivers/ata/libata-eh.c:1071
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff8173c760-ffffffff8173c797: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:1054
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81778300-ffffffff81778337: __ata_port_freeze (STB_LOCAL)
ffffffff8177de08-ffffffff8177de1f: __ata_port_freeze.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179c1b0)
Location: drivers/ata/libata-eh.c:1054
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff8179c1b0-ffffffff8179c1e7: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8185ff80)
Location: drivers/ata/libata-eh.c:1056
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
  - drivers/ata/libata-eh.c:ata_eh_unload
```
**Symbols:**

```
ffffffff8185ff80-ffffffff8185ffba: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8186eda0)
Location: drivers/ata/libata-eh.c:1056
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
  - drivers/ata/libata-eh.c:ata_eh_unload
```
**Symbols:**

```
ffffffff8186eda0-ffffffff8186edda: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818515b0)
Location: drivers/ata/libata-eh.c:1056
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff818515b0-ffffffff818515ea: __ata_port_freeze (STB_LOCAL)
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
In drivers/ata/libata-eh.c (ffffffff818e0ec5)
Location: drivers/ata/libata-eh.c:1064
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81a31a50)
Location: drivers/ata/libata-eh.c:1061
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81a31a50-ffffffff81a31ad8: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb6050)
Location: drivers/ata/libata-eh.c:1063
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81bb6050-ffffffff81bb60d8: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0d400)
Location: drivers/ata/libata-eh.c:1066
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff81c0d400-ffffffff81c0d488: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c62460)
Location: drivers/ata/libata-eh.c:1082
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
  - drivers/ata/libata-eh.c:ata_eh_unload
```
**Symbols:**

```
ffffffff81c62460-ffffffff81c624d7: __ata_port_freeze (STB_LOCAL)
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
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109a7080)
Location: drivers/ata/libata-eh.c:1054
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffff8000109a7080-ffff8000109a70d8: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a76fbc)
Location: drivers/ata/libata-eh.c:1054
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
c0a76fbc-c0a77024: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a6d310)
Location: drivers/ata/libata-eh.c:1054
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
c000000000a6d310-c000000000a6d384: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe000605758)
Location: drivers/ata/libata-eh.c:1054
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffe000605758-ffffffe000605792: __ata_port_freeze (STB_LOCAL)
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
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817612a0)
Location: drivers/ata/libata-eh.c:1054
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff817612a0-ffffffff817612d7: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81741100)
Location: drivers/ata/libata-eh.c:1054
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81741100-ffffffff81741137: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81791030)
Location: drivers/ata/libata-eh.c:1054
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81791030-ffffffff81791067: __ata_port_freeze (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __ata_port_freeze(struct ata_port *ap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817aae70)
Location: drivers/ata/libata-eh.c:1054
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff817aae70-ffffffff817aaea7: __ata_port_freeze (STB_LOCAL)
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
