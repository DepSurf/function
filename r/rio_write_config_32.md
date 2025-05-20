# Function: <code>rio_write_config_32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81458d54)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8145bc4f)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814a884a)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff814a9dd4)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814ca95a)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff814cbee4)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814d6716)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff814d7a2b)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81516c01)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81517c0b)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8154be5f)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8154d846)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815631ef)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81564daf)
Location: include/linux/rio_drv.h:165
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815935af)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8159515a)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815b482f)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815b63da)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8165f0b4)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff816604ea)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81680461)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff816817aa)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81662815)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff816644f2)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff816d5666)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff816d73d2)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff817ff868)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81800dac)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8192cc49)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8192e3ec)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81970edd)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8197267c)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff819baf4d)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff819bc6ec)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffff80001073c91c)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffff80001073eae0)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (c08c27d0)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (c08c40e8)
Location: include/linux/rio_drv.h:161
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (c00000000089649c)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (c0000000008983f0)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffe0004ec724)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffe0004ee138)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815a8a9f)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815aa64a)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81597c3f)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815997ea)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815a902f)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815aabda)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815c34af)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815c456a)
Location: include/linux/rio_drv.h:161
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_write_config
```
</details>
</li>
</ul>

## Differences
