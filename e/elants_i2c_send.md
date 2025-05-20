# Function: <code>elants_i2c_send</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff816ffad0)
Location: drivers/input/touchscreen/elants_i2c.c:156
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff816ffad0-ffffffff816ffb3b: elants_i2c_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817153f0)
Location: drivers/input/touchscreen/elants_i2c.c:156
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff817153f0-ffffffff81715460: elants_i2c_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81786610)
Location: drivers/input/touchscreen/elants_i2c.c:157
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff81786610-ffffffff81786680: elants_i2c_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c76c0)
Location: drivers/input/touchscreen/elants_i2c.c:156
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff817c76c0-ffffffff817c772c: elants_i2c_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817eed60)
Location: drivers/input/touchscreen/elants_i2c.c:157
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff817eed60-ffffffff817eedcc: elants_i2c_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:152
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff8182f990-ffffffff8182f9cb: elants_i2c_send (STB_LOCAL)
ffffffff81830d6b-ffffffff81830d9f: elants_i2c_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:152
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff818612c0-ffffffff818612fb: elants_i2c_send (STB_LOCAL)
ffffffff8186269b-ffffffff818626cf: elants_i2c_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935a5c)
Location: drivers/input/touchscreen/elants_i2c.c:159
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_write_page
```
**Symbols:**

```
ffffffff819344e0-ffffffff8193451b: elants_i2c_send (STB_LOCAL)
ffffffff81935b00-ffffffff81935b34: elants_i2c_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193cb0c)
Location: drivers/input/touchscreen/elants_i2c.c:164
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_write_page
```
**Symbols:**

```
ffffffff8193b540-ffffffff8193b57b: elants_i2c_send (STB_LOCAL)
ffffffff81c23742-ffffffff81c23776: elants_i2c_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191fd3c)
Location: drivers/input/touchscreen/elants_i2c.c:177
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
```
**Symbols:**

```
ffffffff8191eaf0-ffffffff8191eb32: elants_i2c_send (STB_LOCAL)
ffffffff81c157fd-ffffffff81c15832: elants_i2c_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c30de)
Location: drivers/input/touchscreen/elants_i2c.c:190
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
```
**Symbols:**

```
ffffffff819c18a0-ffffffff819c18e2: elants_i2c_send (STB_LOCAL)
ffffffff81d2419e-ffffffff81d241d3: elants_i2c_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b2356a)
Location: drivers/input/touchscreen/elants_i2c.c:190
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
```
**Symbols:**

```
ffffffff81b21b90-ffffffff81b21be4: elants_i2c_send (STB_LOCAL)
ffffffff81eeffe2-ffffffff81ef0016: elants_i2c_send.cold (STB_LOCAL)
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb5ed7)
Location: drivers/input/touchscreen/elants_i2c.c:190
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1d567)
Location: drivers/input/touchscreen/elants_i2c.c:190
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd3267)
Location: drivers/input/touchscreen/elants_i2c.c:190
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
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
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:152
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff81855450-ffffffff8185548b: elants_i2c_send (STB_LOCAL)
ffffffff8185682b-ffffffff8185685f: elants_i2c_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int elants_i2c_send(struct i2c_client *client, const void *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:152
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_suspend
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_sw_reset
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_calibrate
```
**Symbols:**

```
ffffffff81870580-ffffffff818705bb: elants_i2c_send (STB_LOCAL)
ffffffff8187195b-ffffffff8187198f: elants_i2c_send.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
