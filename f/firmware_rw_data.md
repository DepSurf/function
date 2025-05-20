# Function: <code>firmware_rw_data</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void firmware_rw_data(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8169b360)
Location: drivers/base/firmware_loader/fallback.c:329
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff8169b360-ffffffff8169b392: firmware_rw_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void firmware_rw_data(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816bbbe0)
Location: drivers/base/firmware_loader/fallback.c:324
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff816bbbe0-ffffffff816bbc12: firmware_rw_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void firmware_rw_data(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816f6390)
Location: drivers/base/firmware_loader/fallback.c:304
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff816f6390-ffffffff816f63c2: firmware_rw_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void firmware_rw_data(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8171a790)
Location: drivers/base/firmware_loader/fallback.c:304
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff8171a790-ffffffff8171a7c2: firmware_rw_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff817d67b0)
Location: drivers/base/firmware_loader/fallback.c:307
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff817d67b0-ffffffff817d67de: firmware_rw_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff817eb1e0)
Location: drivers/base/firmware_loader/fallback.c:307
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff817eb1e0-ffffffff817eb20e: firmware_rw_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff817cf960)
Location: drivers/base/firmware_loader/fallback.c:305
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff817cf960-ffffffff817cf98e: firmware_rw_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8185a170)
Location: drivers/base/firmware_loader/fallback.c:305
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff8185a170-ffffffff8185a19e: firmware_rw_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void firmware_rw_data(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/sysfs.c (ffffffff819a11a0)
Location: drivers/base/firmware_loader/sysfs.c:232
Inline: False
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_read
```
**Symbols:**

```
ffffffff819a11a0-ffffffff819a11f4: firmware_rw_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void firmware_rw_data(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b12f90)
Location: drivers/base/firmware_loader/sysfs.c:231
Inline: False
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_read
```
**Symbols:**

```
ffffffff81b12f90-ffffffff81b12fe4: firmware_rw_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void firmware_rw_data(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b612a0)
Location: drivers/base/firmware_loader/sysfs.c:231
Inline: False
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_read
```
**Symbols:**

```
ffffffff81b612a0-ffffffff81b612f4: firmware_rw_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void firmware_rw_data(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb4d30)
Location: drivers/base/firmware_loader/sysfs.c:231
Inline: False
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_read
```
**Symbols:**

```
ffffffff81bb4d30-ffffffff81bb4d84: firmware_rw_data (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffff80001090e3c0)
Location: drivers/base/firmware_loader/fallback.c:304
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (c09f7090)
Location: drivers/base/firmware_loader/fallback.c:304
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (c0000000009aed60)
Location: drivers/base/firmware_loader/fallback.c:304
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffe000592906)
Location: drivers/base/firmware_loader/fallback.c:304
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
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
void firmware_rw_data(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816e0ac0)
Location: drivers/base/firmware_loader/fallback.c:304
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff816e0ac0-ffffffff816e0af2: firmware_rw_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void firmware_rw_data(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816bb100)
Location: drivers/base/firmware_loader/fallback.c:304
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff816bb100-ffffffff816bb132: firmware_rw_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void firmware_rw_data(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8170e190)
Location: drivers/base/firmware_loader/fallback.c:304
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff8170e190-ffffffff8170e1c2: firmware_rw_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void firmware_rw_data(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff81728db0)
Location: drivers/base/firmware_loader/fallback.c:304
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff81728db0-ffffffff81728de2: firmware_rw_data (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
