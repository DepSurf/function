# Function: <code>shpc_write_cmd</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153e640)
Location: drivers/pci/hotplug/shpchp_hpc.c:293
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff8153e640-ffffffff8153e970: shpc_write_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81555a10)
Location: drivers/pci/hotplug/shpchp_hpc.c:293
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff81555a10-ffffffff81555d40: shpc_write_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:293
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff81585a10-ffffffff81585c61: shpc_write_cmd (STB_LOCAL)
ffffffff815861a9-ffffffff8158627f: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:293
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff815a73f0-ffffffff815a7641: shpc_write_cmd (STB_LOCAL)
ffffffff815a7b89-ffffffff815a7c5f: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:293
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff816500f0-ffffffff8165034e: shpc_write_cmd (STB_LOCAL)
ffffffff8165093e-ffffffff81650a18: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:293
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff81673590-ffffffff816737ee: shpc_write_cmd (STB_LOCAL)
ffffffff81bfd268-ffffffff81bfd342: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:288
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff81655ab0-ffffffff81655d1e: shpc_write_cmd (STB_LOCAL)
ffffffff81bef057-ffffffff81bef131: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:288
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff816c7b90-ffffffff816c7cd8: shpc_write_cmd (STB_LOCAL)
ffffffff81cea226-ffffffff81cea2d5: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:288
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff817edaa0-ffffffff817edd58: shpc_write_cmd (STB_LOCAL)
ffffffff81eb1294-ffffffff81eb139a: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:288
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff81914ec0-ffffffff81915248: shpc_write_cmd (STB_LOCAL)
ffffffff8208fcdf-ffffffff8208fd10: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:288
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff819584e0-ffffffff81958864: shpc_write_cmd (STB_LOCAL)
ffffffff82110033-ffffffff82110063: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:288
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff819a1a50-ffffffff819a1dd4: shpc_write_cmd (STB_LOCAL)
ffffffff821edd5b-ffffffff821edd8b: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffff80001070faa8)
Location: drivers/pci/hotplug/shpchp_hpc.c:293
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffff80001070faa8-ffff80001070fe58: shpc_write_cmd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dc46c)
Location: drivers/pci/hotplug/shpchp_hpc.c:293
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffe0004dc46c-ffffffe0004dc78c: shpc_write_cmd (STB_LOCAL)
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
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:293
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff8159ac00-ffffffff8159ae51: shpc_write_cmd (STB_LOCAL)
ffffffff8159b399-ffffffff8159b46f: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:293
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff81589d90-ffffffff81589fe1: shpc_write_cmd (STB_LOCAL)
ffffffff8158a529-ffffffff8158a5ff: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:293
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff8159b140-ffffffff8159b391: shpc_write_cmd (STB_LOCAL)
ffffffff8159b8d9-ffffffff8159b9af: shpc_write_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int shpc_write_cmd(struct slot *slot, u8 t_slot, u8 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:293
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_blink
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_off
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_green_led_on
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_attention_status
```
**Symbols:**

```
ffffffff815b5580-ffffffff815b57c5: shpc_write_cmd (STB_LOCAL)
ffffffff815b5d09-ffffffff815b5ddf: shpc_write_cmd.cold (STB_LOCAL)
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
