# Function: <code>alloc_tty_driver</code>

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
In drivers/tty/vt/vt.c (ffffffff81fa69c6)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff814fdff7)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81501721)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8151032c)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
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
In drivers/tty/vt/vt.c (ffffffff81fd2d68)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8154eb27)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81551c02)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8156289a)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
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
In drivers/tty/vt/vt.c (ffffffff82010728)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8157b3a7)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff8157e797)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8158f00a)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
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
In drivers/tty/vt/vt.c (ffffffff820f2203)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8158fa4d)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81592ee8)
Location: include/linux/tty_driver.h:349
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff815a312a)
Location: include/linux/tty_driver.h:349
Inline: True
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
In drivers/tty/vt/vt.c (ffffffff826fb9fc)
Location: include/linux/tty_driver.h:352
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff815f454d)
Location: include/linux/tty_driver.h:352
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f7a18)
Location: include/linux/tty_driver.h:352
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8160885a)
Location: include/linux/tty_driver.h:352
Inline: True
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
In drivers/tty/vt/vt.c (ffffffff82725d1b)
Location: include/linux/tty_driver.h:352
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d31c)
Location: include/linux/tty_driver.h:352
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff816340bc)
Location: include/linux/tty_driver.h:352
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81641f6a)
Location: include/linux/tty_driver.h:352
Inline: True
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
In drivers/tty/vt/vt.c (ffffffff828ddee0)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164b44c)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff816522ec)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816600ca)
Location: include/linux/tty_driver.h:355
Inline: True
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
In drivers/tty/vt/vt.c (ffffffff828f87c9)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8168044c)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81683cea)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81695c5c)
Location: include/linux/tty_driver.h:355
Inline: True
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
In drivers/tty/vt/vt.c (ffffffff829016ca)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a2afc)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a639a)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816b87ec)
Location: include/linux/tty_driver.h:355
Inline: True
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
In drivers/tty/vt/vt.c (ffffffff82d189e8)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81754775)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff817583ee)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176ca95)
Location: include/linux/tty_driver.h:355
Inline: True
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
In drivers/tty/vt/vt.c (ffffffff83006661)
Location: include/linux/tty_driver.h:346
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176fa75)
Location: include/linux/tty_driver.h:346
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_init
```
```
In drivers/tty/serial/serial_core.c (ffffffff817734ae)
Location: include/linux/tty_driver.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81787555)
Location: include/linux/tty_driver.h:346
Inline: True
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
In drivers/tty/vt/vt.c (ffffffff832111e4)
Location: include/linux/tty_driver.h:346
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8175358c)
Location: include/linux/tty_driver.h:346
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff81756f0e)
Location: include/linux/tty_driver.h:346
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8176aeec)
Location: include/linux/tty_driver.h:346
Inline: True
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/tty/vt/vt.c (ffff8000114937b4)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffff800010879c9c)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffff80001087df14)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffff8000108a82dc)
Location: include/linux/tty_driver.h:355
Inline: True
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
In drivers/tty/vt/vt.c (c1594430)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (c097cec4)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (c097feac)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (c09a4e4c)
Location: include/linux/tty_driver.h:355
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
In drivers/tty/vt/vt.c (c0000000013a6124)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvsi.c (c0000000013a6784)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi.c:hvsi_init
```
```
In drivers/tty/hvc/hvc_console.c (c0000000009222b8)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (c000000000925c78)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (c00000000093f0b4)
Location: include/linux/tty_driver.h:355
Inline: True
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
In drivers/tty/vt/vt.c (ffffffe00002e8b8)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffe00054ad58)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054d362)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
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
In drivers/tty/vt/vt.c (ffffffff828e8eb1)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8166855c)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166bdfa)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8167e24c)
Location: include/linux/tty_driver.h:355
Inline: True
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
In drivers/tty/vt/vt.c (ffffffff828e0614)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816488dc)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164af5a)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff8165d33c)
Location: include/linux/tty_driver.h:355
Inline: True
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
In drivers/tty/vt/vt.c (ffffffff828fc9ed)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8169693c)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169a1da)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816ac62c)
Location: include/linux/tty_driver.h:355
Inline: True
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
In drivers/tty/vt/vt.c (ffffffff8290271e)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vty_init
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0eec)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b4dda)
Location: include/linux/tty_driver.h:355
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_register_driver
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff816c6a8c)
Location: include/linux/tty_driver.h:355
Inline: True
```
</details>
</li>
</ul>

## Differences
