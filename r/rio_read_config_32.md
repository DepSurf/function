# Function: <code>rio_read_config_32</code>

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
In drivers/rapidio/rio.c (ffffffff81458d0a)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_set_port_lockout
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
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
In drivers/rapidio/rio-sysfs.c (ffffffff8145bedb)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff814a87b2)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff814aa064)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff814ca8c2)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff814cc174)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff814d667a)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff814d7ccc)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff81516b65)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81517eac)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff8154bdc0)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8154daad)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff81563150)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8156501f)
Location: include/linux/rio_drv.h:149
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff81593510)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815953be)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff815b4790)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815b663e)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff8165f00f)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_chk_dev_route
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81660753)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff816803b9)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_chk_dev_route
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81681a13)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff8166294b)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81664718)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff816d579c)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff816d75f8)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff817ff7a2)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81801099)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff8192cadc)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8192e6e9)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff81970d70)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81972979)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff819bade0)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff819bc9e9)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffff80001073c894)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffff80001073ecf0)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (c08c265c)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (c08c3928)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (c000000000896404)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (c0000000008986d0)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffe0004ec62a)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffe0004ee340)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff815a8a00)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815aa8ae)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff81597ba0)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81599a4e)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff815a8f90)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815aae3e)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
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
In drivers/rapidio/rio.c (ffffffff815c3410)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_clr_err_stopped
  - drivers/rapidio/rio.c:rio_set_port_lockout
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815c47ce)
Location: include/linux/rio_drv.h:145
Inline: True
Inline callers:
  - drivers/rapidio/rio-sysfs.c:rio_read_config
```
</details>
</li>
</ul>

## Differences
