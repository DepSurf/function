# Function: <code>ata_port_request_pm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815c8ac0)
Location: drivers/ata/libata-core.c:5309
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
**Symbols:**

```
ffffffff815c8ac0-ffffffff815c8bb0: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816210c0)
Location: drivers/ata/libata-core.c:5501
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff816210c0-ffffffff816211b0: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81651c40)
Location: drivers/ata/libata-core.c:5543
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81651c40-ffffffff81651d30: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81666290)
Location: drivers/ata/libata-core.c:5629
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81666290-ffffffff81666362: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816cf8f0)
Location: drivers/ata/libata-core.c:5660
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff816cf8f0-ffffffff816cf9c2: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8170c330)
Location: drivers/ata/libata-core.c:5676
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff8170c330-ffffffff8170c3fe: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8172e7b0)
Location: drivers/ata/libata-core.c:5680
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff8172e7b0-ffffffff8172e87e: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:5665
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81769f90-ffffffff8176a06f: ata_port_request_pm (STB_LOCAL)
ffffffff81770c6d-ffffffff81770c93: ata_port_request_pm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8178dff0)
Location: drivers/ata/libata-core.c:5689
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff8178dff0-ffffffff8178e0c2: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81853b90)
Location: drivers/ata/libata-core.c:4928
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81853b90-ffffffff81853c9f: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81863e60)
Location: drivers/ata/libata-core.c:4928
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81863e60-ffffffff81863f6f: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81846ac0)
Location: drivers/ata/libata-core.c:4928
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81846ac0-ffffffff81846bcf: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818d2ee0)
Location: drivers/ata/libata-core.c:4988
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff818d2ee0-ffffffff818d2fef: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81a23560)
Location: drivers/ata/libata-core.c:4972
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81a23560-ffffffff81a23685: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba5380)
Location: drivers/ata/libata-core.c:4978
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81ba5380-ffffffff81ba54a5: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfb9d0)
Location: drivers/ata/libata-core.c:5203
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81bfb9d0-ffffffff81bfbaf5: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c51500)
Location: drivers/ata/libata-core.c:5173
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81c51500-ffffffff81c51657: ata_port_request_pm (STB_LOCAL)
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
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff800010998f90)
Location: drivers/ata/libata-core.c:5689
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffff800010998f90-ffff8000109990d8: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a675f8)
Location: drivers/ata/libata-core.c:5689
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
c0a675f8-c0a67708: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a59de0)
Location: drivers/ata/libata-core.c:5689
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
c000000000a59de0-c000000000a59f50: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005f8402)
Location: drivers/ata/libata-core.c:5689
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffe0005f8402-ffffffe0005f84e8: ata_port_request_pm (STB_LOCAL)
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
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81753180)
Location: drivers/ata/libata-core.c:5689
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81753180-ffffffff81753252: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81733020)
Location: drivers/ata/libata-core.c:5689
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81733020-ffffffff817330f2: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81782e70)
Location: drivers/ata/libata-core.c:5689
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff81782e70-ffffffff81782f42: ata_port_request_pm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ata_port_request_pm(struct ata_port *ap, pm_message_t mesg, unsigned int action, unsigned int ehi_flags, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8179cd30)
Location: drivers/ata/libata-core.c:5689
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_sas_port_resume
  - drivers/ata/libata-core.c:ata_sas_port_suspend
  - drivers/ata/libata-core.c:ata_port_runtime_resume
  - drivers/ata/libata-core.c:ata_port_runtime_suspend
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-core.c:ata_port_pm_poweroff
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
**Symbols:**

```
ffffffff8179cd30-ffffffff8179ce02: ata_port_request_pm (STB_LOCAL)
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
