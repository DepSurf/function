# Function: <code>sx150x_i2c_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
s32 sx150x_i2c_write(struct i2c_client *client, u8 reg, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-sx150x.c (ffffffff8142ae00)
Location: drivers/gpio/gpio-sx150x.c:168
Inline: False
Direct callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_write_cfg
  - drivers/gpio/gpio-sx150x.c:sx150x_init_io
  - drivers/gpio/gpio-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff8142ae00-ffffffff8142ae5e: sx150x_i2c_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
s32 sx150x_i2c_write(struct i2c_client *client, u8 reg, u8 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-sx150x.c (ffffffff81475d10)
Location: drivers/gpio/gpio-sx150x.c:250
Inline: False
Direct callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_init_io
  - drivers/gpio/gpio-sx150x.c:sx150x_irq_thread_fn
  - drivers/gpio/gpio-sx150x.c:sx150x_gpio_set
  - drivers/gpio/gpio-sx150x.c:sx150x_write_cfg
```
**Symbols:**

```
ffffffff81475d10-ffffffff81475d6e: sx150x_i2c_write (STB_LOCAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
