# Function: <code>ata_eh_freeze_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff815d5d50)
Location: drivers/ata/libata-eh.c:1245
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff815d5d50-ffffffff815d5d93: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8162f7b0)
Location: drivers/ata/libata-eh.c:1245
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff8162f7b0-ffffffff8162f7f3: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81660900)
Location: drivers/ata/libata-eh.c:1245
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff81660900-ffffffff81660943: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81677394)
Location: drivers/ata/libata-eh.c:1246
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff81674f00-ffffffff81674f34: ata_eh_freeze_port.part.10 (STB_LOCAL)
ffffffff81675960-ffffffff81675980: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816e09cb)
Location: drivers/ata/libata-eh.c:1244
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff816de560-ffffffff816de594: ata_eh_freeze_port.part.10 (STB_LOCAL)
ffffffff816defd0-ffffffff816deff0: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8171d26f)
Location: drivers/ata/libata-eh.c:1195
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff8171ade0-ffffffff8171ae14: ata_eh_freeze_port.part.13 (STB_LOCAL)
ffffffff8171b7d0-ffffffff8171b7ef: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8173fb4f)
Location: drivers/ata/libata-eh.c:1191
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff8173d6e0-ffffffff8173d714: ata_eh_freeze_port.part.14 (STB_LOCAL)
ffffffff8173e0a0-ffffffff8173e0bf: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8177b97f)
Location: drivers/ata/libata-eh.c:1174
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff817791e0-ffffffff81779214: ata_eh_freeze_port.part.0 (STB_LOCAL)
ffffffff81779c10-ffffffff81779c2f: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179f4ef)
Location: drivers/ata/libata-eh.c:1174
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff8179d050-ffffffff8179d084: ata_eh_freeze_port.part.0 (STB_LOCAL)
ffffffff8179da70-ffffffff8179da8f: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81861949)
Location: drivers/ata/libata-eh.c:1104
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
```
**Symbols:**

```
ffffffff81861060-ffffffff818610a3: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8187075b)
Location: drivers/ata/libata-eh.c:1104
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
```
**Symbols:**

```
ffffffff8186fe80-ffffffff8186fec3: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81852f7b)
Location: drivers/ata/libata-eh.c:1104
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
```
**Symbols:**

```
ffffffff81852690-ffffffff818526d3: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e0ed0)
Location: drivers/ata/libata-eh.c:1112
Inline: True
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
```
**Symbols:**

```
ffffffff818e0ed0-ffffffff818e0f32: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81a32060)
Location: drivers/ata/libata-eh.c:1109
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
Direct callers:
  - drivers/ata/libata-core.c:ata_host_start
```
**Symbols:**

```
ffffffff81a31ae0-ffffffff81a31b37: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb6570)
Location: drivers/ata/libata-eh.c:1108
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
Direct callers:
  - drivers/ata/libata-core.c:ata_host_start
```
**Symbols:**

```
ffffffff81bb60f0-ffffffff81bb6147: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0d920)
Location: drivers/ata/libata-eh.c:1111
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
Direct callers:
  - drivers/ata/libata-core.c:ata_host_start
```
**Symbols:**

```
ffffffff81c0d4a0-ffffffff81c0d4f7: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c62b84)
Location: drivers/ata/libata-eh.c:1123
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_suspend
  - drivers/ata/libata-eh.c:ata_eh_reset
Direct callers:
  - drivers/ata/libata-core.c:ata_host_start
```
**Symbols:**

```
ffffffff81c624f0-ffffffff81c6252e: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109aaf54)
Location: drivers/ata/libata-eh.c:1174
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffff8000109a8058-ffff8000109a80f8: ata_eh_freeze_port.part.0 (STB_LOCAL)
ffff8000109a8f08-ffff8000109a8f40: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (c0a7a848)
Location: drivers/ata/libata-eh.c:1174
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
c0a77fb4-c0a77ff0: ata_eh_freeze_port.part.0 (STB_LOCAL)
c0a78bf8-c0a78c24: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a720e4)
Location: drivers/ata/libata-eh.c:1174
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
c000000000a6e850-c000000000a6e8b4: ata_eh_freeze_port.part.0 (STB_LOCAL)
c000000000a6f830-c000000000a6f854: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe000608a7e)
Location: drivers/ata/libata-eh.c:1174
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffe000606594-ffffffe0006065da: ata_eh_freeze_port.part.0 (STB_LOCAL)
ffffffe000606ff0-ffffffe000607020: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817645df)
Location: drivers/ata/libata-eh.c:1174
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff81762140-ffffffff81762174: ata_eh_freeze_port.part.0 (STB_LOCAL)
ffffffff81762b60-ffffffff81762b7f: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8174443f)
Location: drivers/ata/libata-eh.c:1174
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff81741fa0-ffffffff81741fd4: ata_eh_freeze_port.part.0 (STB_LOCAL)
ffffffff817429c0-ffffffff817429df: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179436f)
Location: drivers/ata/libata-eh.c:1174
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff81791ed0-ffffffff81791f04: ata_eh_freeze_port.part.0 (STB_LOCAL)
ffffffff817928f0-ffffffff8179290f: ata_eh_freeze_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ata_eh_freeze_port(struct ata_port *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817ae1df)
Location: drivers/ata/libata-eh.c:1174
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff817abd10-ffffffff817abd44: ata_eh_freeze_port.part.0 (STB_LOCAL)
ffffffff817ac730-ffffffff817ac74f: ata_eh_freeze_port (STB_GLOBAL)
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
