# Function: <code>elants_i2c_fw_update</code>

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
In drivers/input/touchscreen/elants_i2c.c (ffffffff8170093c)
Location: drivers/input/touchscreen/elants_i2c.c:720
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff8171619b)
Location: drivers/input/touchscreen/elants_i2c.c:720
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff8178739b)
Location: drivers/input/touchscreen/elants_i2c.c:721
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c846c)
Location: drivers/input/touchscreen/elants_i2c.c:720
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff817efb0c)
Location: drivers/input/touchscreen/elants_i2c.c:721
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff8183045f)
Location: drivers/input/touchscreen/elants_i2c.c:716
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861d8f)
Location: drivers/input/touchscreen/elants_i2c.c:716
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int elants_i2c_fw_update(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:784
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff81935530-ffffffff819355a5: elants_i2c_fw_update (STB_LOCAL)
ffffffff8193648d-ffffffff819365d4: elants_i2c_fw_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int elants_i2c_fw_update(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:792
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff8193c5a0-ffffffff8193c615: elants_i2c_fw_update (STB_LOCAL)
ffffffff81c240cf-ffffffff81c24216: elants_i2c_fw_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int elants_i2c_fw_update(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:862
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff8191fde0-ffffffff8191fe55: elants_i2c_fw_update (STB_LOCAL)
ffffffff81c16228-ffffffff81c1636f: elants_i2c_fw_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int elants_i2c_fw_update(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:906
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff819c2a80-ffffffff819c2af5: elants_i2c_fw_update (STB_LOCAL)
ffffffff81d24bac-ffffffff81d24cf3: elants_i2c_fw_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int elants_i2c_fw_update(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:906
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff81b22e90-ffffffff81b22f19: elants_i2c_fw_update (STB_LOCAL)
ffffffff81ef0a07-ffffffff81ef0b38: elants_i2c_fw_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int elants_i2c_fw_update(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb66e0)
Location: drivers/input/touchscreen/elants_i2c.c:906
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff81cb66e0-ffffffff81cb68bd: elants_i2c_fw_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int elants_i2c_fw_update(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1dd80)
Location: drivers/input/touchscreen/elants_i2c.c:906
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff81d1dd80-ffffffff81d1df5d: elants_i2c_fw_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int elants_i2c_fw_update(struct elants_data *ts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd3a80)
Location: drivers/input/touchscreen/elants_i2c.c:906
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff81dd3a80-ffffffff81dd3c5d: elants_i2c_fw_update (STB_LOCAL)
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff81855f1f)
Location: drivers/input/touchscreen/elants_i2c.c:716
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff8187104f)
Location: drivers/input/touchscreen/elants_i2c.c:716
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
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
