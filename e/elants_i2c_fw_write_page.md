# Function: <code>elants_i2c_fw_write_page</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81700bfe)
Location: drivers/input/touchscreen/elants_i2c.c:585
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81716430)
Location: drivers/input/touchscreen/elants_i2c.c:585
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81787630)
Location: drivers/input/touchscreen/elants_i2c.c:586
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c8690)
Location: drivers/input/touchscreen/elants_i2c.c:585
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff817efd30)
Location: drivers/input/touchscreen/elants_i2c.c:586
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff818310d1)
Location: drivers/input/touchscreen/elants_i2c.c:581
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81862a01)
Location: drivers/input/touchscreen/elants_i2c.c:581
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int elants_i2c_fw_write_page(struct i2c_client *client, const void *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935ba9)
Location: drivers/input/touchscreen/elants_i2c.c:595
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
```
**Symbols:**

```
ffffffff81935ba9-ffffffff81935c87: elants_i2c_fw_write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int elants_i2c_fw_write_page(struct i2c_client *client, const void *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81c237eb)
Location: drivers/input/touchscreen/elants_i2c.c:603
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
```
**Symbols:**

```
ffffffff81c237eb-ffffffff81c238c9: elants_i2c_fw_write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81c15df9)
Location: drivers/input/touchscreen/elants_i2c.c:673
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d247fc)
Location: drivers/input/touchscreen/elants_i2c.c:686
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81ef065e)
Location: drivers/input/touchscreen/elants_i2c.c:686
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb653f)
Location: drivers/input/touchscreen/elants_i2c.c:686
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1dbd4)
Location: drivers/input/touchscreen/elants_i2c.c:686
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd38d4)
Location: drivers/input/touchscreen/elants_i2c.c:686
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81856b91)
Location: drivers/input/touchscreen/elants_i2c.c:581
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81871cc1)
Location: drivers/input/touchscreen/elants_i2c.c:581
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
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
</ul>
