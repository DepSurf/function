# Function: <code>rtc_tm_to_time64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff816732c0)
Location: drivers/rtc/rtc-lib.c:119
Inline: False
Direct callers:
  - drivers/rtc/rtc-lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_show
  - drivers/rtc/rtc-sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
```
**Symbols:**

```
ffffffff816732c0-ffffffff816732ef: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff816d3ab0)
Location: drivers/rtc/rtc-lib.c:119
Inline: False
Direct callers:
  - drivers/rtc/rtc-lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_show
  - drivers/rtc/rtc-sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
```
**Symbols:**

```
ffffffff816d3ab0-ffffffff816d3adf: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff81703790)
Location: drivers/rtc/rtc-lib.c:119
Inline: False
Direct callers:
  - drivers/rtc/rtc-lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_show
  - drivers/rtc/rtc-sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81703790-ffffffff817037bf: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff81718f70)
Location: drivers/rtc/rtc-lib.c:119
Inline: False
Direct callers:
  - drivers/rtc/rtc-lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_show
  - drivers/rtc/rtc-sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81718f70-ffffffff81718f9f: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff8178a150)
Location: drivers/rtc/rtc-lib.c:119
Inline: False
Direct callers:
  - drivers/rtc/rtc-lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_show
  - drivers/rtc/rtc-sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff8178a150-ffffffff8178a17f: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-lib.c (ffffffff817cb260)
Location: drivers/rtc/rtc-lib.c:117
Inline: False
Direct callers:
  - drivers/rtc/rtc-lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_store
  - drivers/rtc/rtc-sysfs.c:wakealarm_show
  - drivers/rtc/rtc-sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff817cb260-ffffffff817cb28f: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff817f2910)
Location: drivers/rtc/lib.c:117
Inline: False
Direct callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff817f2910-ffffffff817f293f: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff818335f0)
Location: drivers/rtc/lib.c:115
Inline: False
Direct callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff818335f0-ffffffff81833620: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81864f30)
Location: drivers/rtc/lib.c:115
Inline: False
Direct callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81864f30-ffffffff81864f60: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81938515)
Location: drivers/rtc/lib.c:115
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
Direct callers:
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff819384e0-ffffffff81938510: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff8193e849)
Location: drivers/rtc/lib.c:115
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
Direct callers:
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff8193e810-ffffffff8193e840: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81922049)
Location: drivers/rtc/lib.c:115
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81922010-ffffffff81922040: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff819c5239)
Location: drivers/rtc/lib.c:168
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff819c5170-ffffffff819c51a0: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81b25819)
Location: drivers/rtc/lib.c:168
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
Direct callers:
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/interface.c:rtc_valid_range
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81b25710-ffffffff81b2574f: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81cb8dc9)
Location: drivers/rtc/lib.c:168
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/interface.c:rtc_valid_range
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81cb8ca0-ffffffff81cb8cdf: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81d204f9)
Location: drivers/rtc/lib.c:168
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/interface.c:rtc_valid_range
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81d20400-ffffffff81d2043f: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81dd6229)
Location: drivers/rtc/lib.c:168
Inline: True
Inline callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
Direct callers:
  - arch/x86/kernel/rtc.c:mach_get_cmos_time
  - drivers/rtc/class.c:__devm_rtc_register_device
  - drivers/rtc/class.c:rtc_resume
  - drivers/rtc/class.c:rtc_suspend
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/interface.c:rtc_valid_range
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_check_wkalrm
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81dd6130-ffffffff81dd616f: rtc_tm_to_time64 (STB_GLOBAL)
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
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffff800010aa6768)
Location: drivers/rtc/lib.c:115
Inline: False
Direct callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setalarm
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_setalarm
  - drivers/rtc/rtc-xgene.c:xgene_rtc_set_alarm
  - drivers/rtc/rtc-xgene.c:xgene_rtc_set_time
```
**Symbols:**

```
ffff800010aa6768-ffff800010aa67a4: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (c0b85220)
Location: drivers/rtc/lib.c:115
Inline: False
Direct callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-omap.c:omap_rtc_power_off_program
  - drivers/rtc/rtc-pl031.c:pl031_set_alarm
  - drivers/rtc/rtc-pl031.c:pl031_set_time
  - drivers/rtc/rtc-pl031.c:pl031_stv2_tm_to_time
```
**Symbols:**

```
c0b85220-c0b85270: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (c000000000b87300)
Location: drivers/rtc/lib.c:115
Inline: False
Direct callers:
  - arch/powerpc/kernel/time.c:read_persistent_clock64
  - arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
```
**Symbols:**

```
c000000000b87300-c000000000b8735c: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffe0006b2abc)
Location: drivers/rtc/lib.c:115
Inline: False
Direct callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
```
**Symbols:**

```
ffffffe0006b2abc-ffffffe0006b2af6: rtc_tm_to_time64 (STB_GLOBAL)
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
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff81817be0)
Location: drivers/rtc/lib.c:115
Inline: False
Direct callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff81817be0-ffffffff81817c10: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff817df2d0)
Location: drivers/rtc/lib.c:115
Inline: False
Direct callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff817df2d0-ffffffff817df300: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff818590c0)
Location: drivers/rtc/lib.c:115
Inline: False
Direct callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff818590c0-ffffffff818590f0: rtc_tm_to_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time *tm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/lib.c (ffffffff818741a0)
Location: drivers/rtc/lib.c:115
Inline: False
Direct callers:
  - drivers/rtc/lib.c:rtc_tm_to_ktime
  - drivers/rtc/hctosys.c:rtc_hctosys
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:__rtc_set_alarm
  - drivers/rtc/interface.c:rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:__rtc_read_alarm
  - drivers/rtc/interface.c:rtc_read_time
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_store
  - drivers/rtc/sysfs.c:wakealarm_show
  - drivers/rtc/sysfs.c:since_epoch_show
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_aie_poweroff
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
  - drivers/rtc/rtc-cmos.c:cmos_validate_alarm
```
**Symbols:**

```
ffffffff818741a0-ffffffff818741d0: rtc_tm_to_time64 (STB_GLOBAL)
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
