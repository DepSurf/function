# Function: <code>i2c_parse_timing</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void i2c_parse_timing(struct device *dev, char *prop_name, u32 *cur_val_p, u32 def_val, bool use_def);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819406d0)
Location: drivers/i2c/i2c-core-base.c:1576
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
**Symbols:**

```
ffffffff819406d0-ffffffff8194073e: i2c_parse_timing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void i2c_parse_timing(struct device *dev, char *prop_name, u32 *cur_val_p, u32 def_val, bool use_def);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81946aa0)
Location: drivers/i2c/i2c-core-base.c:1706
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
**Symbols:**

```
ffffffff81946aa0-ffffffff81946b0e: i2c_parse_timing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void i2c_parse_timing(struct device *dev, char *prop_name, u32 *cur_val_p, u32 def_val, bool use_def);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192a3a0)
Location: drivers/i2c/i2c-core-base.c:1766
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
**Symbols:**

```
ffffffff8192a3a0-ffffffff8192a40e: i2c_parse_timing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void i2c_parse_timing(struct device *dev, char *prop_name, u32 *cur_val_p, u32 def_val, bool use_def);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cd540)
Location: drivers/i2c/i2c-core-base.c:1767
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
**Symbols:**

```
ffffffff819cd540-ffffffff819cd5ab: i2c_parse_timing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void i2c_parse_timing(struct device *dev, char *prop_name, u32 *cur_val_p, u32 def_val, bool use_def);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b2f650)
Location: drivers/i2c/i2c-core-base.c:1770
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
**Symbols:**

```
ffffffff81b2f650-ffffffff81b2f6dd: i2c_parse_timing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void i2c_parse_timing(struct device *dev, char *prop_name, u32 *cur_val_p, u32 def_val, bool use_def);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc3570)
Location: drivers/i2c/i2c-core-base.c:1764
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
**Symbols:**

```
ffffffff81cc3570-ffffffff81cc35fd: i2c_parse_timing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void i2c_parse_timing(struct device *dev, char *prop_name, u32 *cur_val_p, u32 def_val, bool use_def);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2bcc0)
Location: drivers/i2c/i2c-core-base.c:1877
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
**Symbols:**

```
ffffffff81d2bcc0-ffffffff81d2bd4d: i2c_parse_timing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void i2c_parse_timing(struct device *dev, char *prop_name, u32 *cur_val_p, u32 def_val, bool use_def);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de1b80)
Location: drivers/i2c/i2c-core-base.c:1892
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
  - drivers/i2c/i2c-core-base.c:i2c_parse_fw_timings
```
**Symbols:**

```
ffffffff81de1b80-ffffffff81de1c0d: i2c_parse_timing (STB_LOCAL)
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
