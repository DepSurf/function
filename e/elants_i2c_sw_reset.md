# Function: <code>elants_i2c_sw_reset</code>

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
int elants_i2c_sw_reset(struct i2c_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff816ffb40)
Location: drivers/input/touchscreen/elants_i2c.c:275
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff816ffb40-ffffffff816ffbc4: elants_i2c_sw_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int elants_i2c_sw_reset(struct i2c_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81715460)
Location: drivers/input/touchscreen/elants_i2c.c:275
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff81715460-ffffffff817154db: elants_i2c_sw_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int elants_i2c_sw_reset(struct i2c_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81786680)
Location: drivers/input/touchscreen/elants_i2c.c:276
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff81786680-ffffffff817866fb: elants_i2c_sw_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int elants_i2c_sw_reset(struct i2c_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c7730)
Location: drivers/input/touchscreen/elants_i2c.c:275
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff817c7730-ffffffff817c77ab: elants_i2c_sw_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int elants_i2c_sw_reset(struct i2c_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817eedd0)
Location: drivers/input/touchscreen/elants_i2c.c:276
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff817eedd0-ffffffff817eee4b: elants_i2c_sw_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int elants_i2c_sw_reset(struct i2c_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:271
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff8182f9d0-ffffffff8182fa3c: elants_i2c_sw_reset (STB_LOCAL)
ffffffff81830d9f-ffffffff81830db6: elants_i2c_sw_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int elants_i2c_sw_reset(struct i2c_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:271
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff81861300-ffffffff8186136c: elants_i2c_sw_reset (STB_LOCAL)
ffffffff818626cf-ffffffff818626e6: elants_i2c_sw_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935a47)
Location: drivers/input/touchscreen/elants_i2c.c:308
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193caf7)
Location: drivers/input/touchscreen/elants_i2c.c:313
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191fd27)
Location: drivers/input/touchscreen/elants_i2c.c:326
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c30c9)
Location: drivers/input/touchscreen/elants_i2c.c:339
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b23555)
Location: drivers/input/touchscreen/elants_i2c.c:339
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb5ec2)
Location: drivers/input/touchscreen/elants_i2c.c:339
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1d552)
Location: drivers/input/touchscreen/elants_i2c.c:339
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd3252)
Location: drivers/input/touchscreen/elants_i2c.c:339
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
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
int elants_i2c_sw_reset(struct i2c_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:271
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff81855490-ffffffff818554fc: elants_i2c_sw_reset (STB_LOCAL)
ffffffff8185685f-ffffffff81856876: elants_i2c_sw_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int elants_i2c_sw_reset(struct i2c_client *client);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:271
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_resume
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_do_update_firmware
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_initialize
```
**Symbols:**

```
ffffffff818705c0-ffffffff8187062c: elants_i2c_sw_reset (STB_LOCAL)
ffffffff8187198f-ffffffff818719a6: elants_i2c_sw_reset.cold (STB_LOCAL)
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
