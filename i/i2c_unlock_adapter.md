# Function: <code>i2c_unlock_adapter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void i2c_unlock_adapter(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff81678dc0)
Location: drivers/i2c/i2c-core.c:993
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
  - drivers/i2c/i2c-core.c:i2c_unlock_adapter
  - drivers/i2c/i2c-core.c:i2c_transfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
  - drivers/i2c/i2c-core.c:i2c_smbus_xfer
```
**Symbols:**

```
ffffffff81678dc0-ffffffff81678df7: i2c_unlock_adapter (STB_GLOBAL)
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
In drivers/mfd/88pm860x-i2c.c (ffffffff815d051a)
Location: include/linux/i2c.h:622
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
```
In drivers/i2c/i2c-core.c (ffffffff816da690)
Location: include/linux/i2c.h:622
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_slave_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff815fd127)
Location: include/linux/i2c.h:658
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff81610ec7)
Location: include/linux/i2c.h:673
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/88pm860x-i2c.c (ffffffff8167974d)
Location: include/linux/i2c.h:675
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_bulk_read
  - drivers/mfd/88pm860x-i2c.c:pm860x_page_reg_write
```
</details>
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
</ul>
