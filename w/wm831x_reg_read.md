# Function: <code>wm831x_reg_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81582490)
Location: drivers/mfd/wm831x-core.c:517
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff81582490-ffffffff815824d9: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff815d9075)
Location: drivers/mfd/wm831x-core.c:517
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff815d8560-ffffffff815d85a8: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81605d65)
Location: drivers/mfd/wm831x-core.c:517
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff81605250-ffffffff81605298: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81619b45)
Location: drivers/mfd/wm831x-core.c:519
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff81619120-ffffffff81619169: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81682215)
Location: drivers/mfd/wm831x-core.c:519
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff816817c0-ffffffff81681809: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff816be275)
Location: drivers/mfd/wm831x-core.c:519
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff816bd820-ffffffff816bd869: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff816df635)
Location: drivers/mfd/wm831x-core.c:519
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff816deab0-ffffffff816deaf9: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81718733)
Location: drivers/mfd/wm831x-core.c:515
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff817182c0-ffffffff81718308: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff8173ca43)
Location: drivers/mfd/wm831x-core.c:515
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff8173c5d0-ffffffff8173c618: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff817fa3e1)
Location: drivers/mfd/wm831x-core.c:515
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_show
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff817f9eb0-ffffffff817f9ef8: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff8180cd61)
Location: drivers/mfd/wm831x-core.c:519
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_show
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff8180c830-ffffffff8180c878: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff817f1531)
Location: drivers/mfd/wm831x-core.c:519
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_show
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff817f10d0-ffffffff817f1118: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81879bd1)
Location: drivers/mfd/wm831x-core.c:519
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/mfd/wm831x-otp.c:unique_id_show
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff81879760-ffffffff818797a8: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff819c2331)
Location: drivers/mfd/wm831x-core.c:519
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/mfd/wm831x-otp.c:unique_id_show
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff819c1f00-ffffffff819c1f5a: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81b384ca)
Location: drivers/mfd/wm831x-core.c:519
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/mfd/wm831x-otp.c:unique_id_show
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff81b37920-ffffffff81b3797a: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81b8b933)
Location: drivers/mfd/wm831x-core.c:519
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/mfd/wm831x-otp.c:unique_id_show
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff81b8ad70-ffffffff81b8adca: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81bdf833)
Location: drivers/mfd/wm831x-core.c:518
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/mfd/wm831x-otp.c:unique_id_show
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff81bdec70-ffffffff81bdecca: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffff800010938264)
Location: drivers/mfd/wm831x-core.c:515
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffff800010937650-ffff8000109376c0: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (c0a20728)
Location: drivers/mfd/wm831x-core.c:515
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
c0a1f978-c0a1f9dc: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (c0000000009decc0)
Location: drivers/mfd/wm831x-core.c:515
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
c0000000009ddc40-c0000000009ddcb0: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffe0005ad01a)
Location: drivers/mfd/wm831x-core.c:515
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffe0005ac6b0-ffffffe0005ac6f0: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff81700523)
Location: drivers/mfd/wm831x-core.c:515
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff817000b0-ffffffff817000f8: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff816d4333)
Location: drivers/mfd/wm831x-core.c:515
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff816d3ec0-ffffffff816d3f08: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff8172ff03)
Location: drivers/mfd/wm831x-core.c:515
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff8172fa90-ffffffff8172fad8: wm831x_reg_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int wm831x_reg_read(struct wm831x *wm831x, short unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/wm831x-core.c (ffffffff8174b343)
Location: drivers/mfd/wm831x-core.c:515
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_suspend
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
  - drivers/mfd/wm831x-core.c:wm831x_device_init
Direct callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-irq.c:wm831x_irq_thread
  - drivers/mfd/wm831x-otp.c:wm831x_unique_id_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_polled
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_irq
```
**Symbols:**

```
ffffffff8174aed0-ffffffff8174af18: wm831x_reg_read (STB_GLOBAL)
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
