# Function: <code>use_hpet_alarm</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff817d1b72)
Location: drivers/rtc/rtc-cmos.c:170
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
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
In drivers/rtc/rtc-cmos.c (ffffffff817f8cc4)
Location: drivers/rtc/rtc-cmos.c:183
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
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
In drivers/rtc/rtc-cmos.c (ffffffff818398da)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
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
In drivers/rtc/rtc-cmos.c (ffffffff8186b24a)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int use_hpet_alarm();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff8193ef62)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8193db60-ffffffff8193db7c: use_hpet_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int use_hpet_alarm();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff81944af2)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81943be0-ffffffff81943bfc: use_hpet_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int use_hpet_alarm();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff819282b5)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81927410-ffffffff8192742c: use_hpet_alarm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int use_hpet_alarm();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff819cba6b)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff819ca320-ffffffff819ca34d: use_hpet_alarm (STB_LOCAL)
ffffffff81d251b7-ffffffff81d251d2: use_hpet_alarm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int use_hpet_alarm();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff81b2d2d9)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81b2c040-ffffffff81b2c07d: use_hpet_alarm (STB_LOCAL)
ffffffff81ef0fec-ffffffff81ef1007: use_hpet_alarm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff81cc0bb9)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff81d2858a)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-cmos.c (ffffffff81dde3aa)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm_callback
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/rtc/rtc-cmos.c (ffffffff8181defa)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
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
In drivers/rtc/rtc-cmos.c (ffffffff817e55aa)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
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
In drivers/rtc/rtc-cmos.c (ffffffff8185f3da)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
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
In drivers/rtc/rtc-cmos.c (ffffffff8187a25a)
Location: drivers/rtc/rtc-cmos.c:179
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_resume
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_suspend
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_interrupt
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_procfs
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_irq_disable
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
  - drivers/rtc/rtc-cmos.c:cmos_checkintr
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
