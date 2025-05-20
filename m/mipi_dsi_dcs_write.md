# Function: <code>mipi_dsi_dcs_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8153e670)
Location: drivers/gpu/drm/drm_mipi_dsi.c:536
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
```
**Symbols:**

```
ffffffff8153e670-ffffffff8153e717: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8163f756)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff8163f340-ffffffff8163f3e9: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81670826)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff816703b0-ffffffff81670459: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81684d36)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff816848e0-ffffffff81684989: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff816ee596)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff816ee140-ffffffff816ee1e9: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8172adc9)
Location: drivers/gpu/drm/drm_mipi_dsi.c:696
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff8172a940-ffffffff8172a9dd: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8174d589)
Location: drivers/gpu/drm/drm_mipi_dsi.c:698
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff8174d100-ffffffff8174d19d: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81789349)
Location: drivers/gpu/drm/drm_mipi_dsi.c:698
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff817895d0-ffffffff81789670: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817acf49)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff817ad1d0-ffffffff817ad270: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81873435)
Location: drivers/gpu/drm/drm_mipi_dsi.c:746
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
```
**Symbols:**

```
ffffffff818729a0-ffffffff81872a40: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81881ffc)
Location: drivers/gpu/drm/drm_mipi_dsi.c:745
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
```
**Symbols:**

```
ffffffff81881480-ffffffff81881575: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8186486c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:745
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
```
**Symbols:**

```
ffffffff81863d10-ffffffff81863def: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff818f3bac)
Location: drivers/gpu/drm/drm_mipi_dsi.c:745
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
```
**Symbols:**

```
ffffffff818f3050-ffffffff818f312f: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81a460c2)
Location: drivers/gpu/drm/drm_mipi_dsi.c:826
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff81a45730-ffffffff81a4582e: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81bccfb2)
Location: drivers/gpu/drm/drm_mipi_dsi.c:827
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness_large
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff81bcc110-ffffffff81bcc20e: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81c24ba2)
Location: drivers/gpu/drm/drm_mipi_dsi.c:827
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness_large
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff81c23c90-ffffffff81c23dce: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81cd64a2)
Location: drivers/gpu/drm/drm_mipi_dsi.c:841
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness_large
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_scanline
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff81cd5650-ffffffff81cd578e: mipi_dsi_dcs_write (STB_GLOBAL)
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffff8000109bf01c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffff8000109bea60-ffff8000109beb24: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (c0a8bc08)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
c0a8c428-c0a8c4d4: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (c000000000a7ed68)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
c000000000a7f840-c000000000a7f950: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffe000611924)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffe000611f06-ffffffe000611fa6: mipi_dsi_dcs_write (STB_GLOBAL)
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
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81771a69)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff81771cf0-ffffffff81771d90: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817518b9)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff81751b40-ffffffff81751be0: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817a1dc9)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff817a2050-ffffffff817a20f0: mipi_dsi_dcs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_write(struct mipi_dsi_device *dsi, u8 cmd, const void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817bbc49)
Location: drivers/gpu/drm/drm_mipi_dsi.c:693
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_off
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_exit_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_enter_sleep_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_soft_reset
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_nop
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_tear_on
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_page_address
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_set_column_address
```
**Symbols:**

```
ffffffff817bbed0-ffffffff817bbf70: mipi_dsi_dcs_write (STB_GLOBAL)
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
