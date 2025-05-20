# Function: <code>gpiod_request_user</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168e1a6)
Location: drivers/gpio/gpiolib.h:139
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_create
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff816900f3)
Location: drivers/gpio/gpiolib.h:139
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:export_store
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
In drivers/gpio/gpiolib-cdev.c (ffffffff817ad65f)
Location: drivers/gpio/gpiolib.h:184
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff817af19b)
Location: drivers/gpio/gpiolib.h:184
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:export_store
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
In drivers/gpio/gpiolib-cdev.c (ffffffff818c6c3e)
Location: drivers/gpio/gpiolib.h:194
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c877b)
Location: drivers/gpio/gpiolib.h:194
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:export_store
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
In drivers/gpio/gpiolib-cdev.c (ffffffff81909cde)
Location: drivers/gpio/gpiolib.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190b72b)
Location: drivers/gpio/gpiolib.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:export_store
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
In drivers/gpio/gpiolib-cdev.c (ffffffff819510e0)
Location: drivers/gpio/gpiolib.h:194
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81953446)
Location: drivers/gpio/gpiolib.h:194
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:export_store
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
