# Function: <code>mipi_dsi_dcs_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8153ead0)
Location: drivers/gpu/drm/drm_mipi_dsi.c:576
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
```
**Symbols:**

```
ffffffff8153ead0-ffffffff8153eb43: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8163f7a0)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff8163f7a0-ffffffff8163f813: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81670870)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff81670870-ffffffff816708e3: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81684f5c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff81684d80-ffffffff81684df8: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff816ee7bc)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff816ee5e0-ffffffff816ee658: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8172afcc)
Location: drivers/gpu/drm/drm_mipi_dsi.c:736
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff8172adf0-ffffffff8172ae68: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8174d78c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:738
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff8174d5b0-ffffffff8174d628: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8178954c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:738
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff81789370-ffffffff817893e8: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817ad14c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff817acf70-ffffffff817acfe8: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81872d1c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:786
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff81873220-ffffffff818732c6: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff8188187c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:785
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff81881ea0-ffffffff81881f46: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff818640ec)
Location: drivers/gpu/drm/drm_mipi_dsi.c:785
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff81864710-ffffffff818647b6: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff818f342c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:785
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff818f3a50-ffffffff818f3af6: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81a45d4c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:866
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff81a46490-ffffffff81a4653d: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81bcca07)
Location: drivers/gpu/drm/drm_mipi_dsi.c:867
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness_large
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff81bcd170-ffffffff81bcd21d: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81c245e7)
Location: drivers/gpu/drm/drm_mipi_dsi.c:867
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness_large
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff81c24d60-ffffffff81c24e0d: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81cd6067)
Location: drivers/gpu/drm/drm_mipi_dsi.c:881
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness_large
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff81cd6700-ffffffff81cd67ad: mipi_dsi_dcs_read (STB_GLOBAL)
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffff8000109bf298)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffff8000109bf048-ffff8000109bf0dc: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (c0a8bd00)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
c0a8b78c-c0a8b818: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (c000000000a7ee9c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
c000000000a7e7f0-c000000000a7e888: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffe0006119be)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffe000611606-ffffffe000611674: mipi_dsi_dcs_read (STB_GLOBAL)
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
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81771c6c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff81771a90-ffffffff81771b08: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81751abc)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff817518e0-ffffffff81751958: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817a1fcc)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff817a1df0-ffffffff817a1e68: mipi_dsi_dcs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t mipi_dsi_dcs_read(struct mipi_dsi_device *dsi, u8 cmd, void *data, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff817bbe4c)
Location: drivers/gpu/drm/drm_mipi_dsi.c:733
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_display_brightness
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_pixel_format
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_dcs_get_power_mode
```
**Symbols:**

```
ffffffff817bbc70-ffffffff817bbce8: mipi_dsi_dcs_read (STB_GLOBAL)
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
