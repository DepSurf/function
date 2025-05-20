# Function: <code>firmware_rw</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void firmware_rw(struct firmware_buf *buf, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b27c0)
Location: drivers/base/firmware_class.c:724
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_data_read
```
**Symbols:**

```
ffffffff815b27c0-ffffffff815b2992: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void firmware_rw(struct firmware_buf *buf, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e1be0)
Location: drivers/base/firmware_class.c:785
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_data_read
```
**Symbols:**

```
ffffffff815e1be0-ffffffff815e1dac: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void firmware_rw(struct firmware_buf *buf, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f6860)
Location: drivers/base/firmware_class.c:815
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_data_read
```
**Symbols:**

```
ffffffff815f6860-ffffffff815f6a2d: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void firmware_rw(struct firmware_buf *buf, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8165e7c0)
Location: drivers/base/firmware_class.c:819
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_data_read
```
**Symbols:**

```
ffffffff8165e7c0-ffffffff8165e98d: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8169b190)
Location: drivers/base/firmware_loader/fallback.c:338
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff8169b190-ffffffff8169b35d: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816bba10)
Location: drivers/base/firmware_loader/fallback.c:333
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff816bba10-ffffffff816bbbdd: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816f61c0)
Location: drivers/base/firmware_loader/fallback.c:313
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff816f61c0-ffffffff816f638e: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8171a5c0)
Location: drivers/base/firmware_loader/fallback.c:313
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff8171a5c0-ffffffff8171a78e: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff817d65e0)
Location: drivers/base/firmware_loader/fallback.c:316
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff817d65e0-ffffffff817d67ae: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff817eb010)
Location: drivers/base/firmware_loader/fallback.c:316
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff817eb010-ffffffff817eb1de: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff817cf790)
Location: drivers/base/firmware_loader/fallback.c:314
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff817cf790-ffffffff817cf95f: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff81859ef0)
Location: drivers/base/firmware_loader/fallback.c:314
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff81859ef0-ffffffff8185a0bf: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/sysfs.c (ffffffff819a1200)
Location: drivers/base/firmware_loader/sysfs.c:241
Inline: False
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_read
```
**Symbols:**

```
ffffffff819a1200-ffffffff819a13e0: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b13000)
Location: drivers/base/firmware_loader/sysfs.c:240
Inline: False
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_read
```
**Symbols:**

```
ffffffff81b13000-ffffffff81b131ac: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b61310)
Location: drivers/base/firmware_loader/sysfs.c:240
Inline: False
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_read
```
**Symbols:**

```
ffffffff81b61310-ffffffff81b614bc: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb4da0)
Location: drivers/base/firmware_loader/sysfs.c:240
Inline: False
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_read
```
**Symbols:**

```
ffffffff81bb4da0-ffffffff81bb4f4c: firmware_rw (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffff80001090e150)
Location: drivers/base/firmware_loader/fallback.c:313
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffff80001090e150-ffff80001090e22c: firmware_rw.isra.0 (STB_LOCAL)
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
In drivers/base/firmware_loader/fallback.c (c09f70fc)
Location: drivers/base/firmware_loader/fallback.c:313
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (c0000000009ae6a0)
Location: drivers/base/firmware_loader/fallback.c:313
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
c0000000009ae6a0-c0000000009ae7dc: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffe0005926c0)
Location: drivers/base/firmware_loader/fallback.c:313
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffe0005926c0-ffffffe00059279a: firmware_rw (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816e08f0)
Location: drivers/base/firmware_loader/fallback.c:313
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff816e08f0-ffffffff816e0abe: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816baf30)
Location: drivers/base/firmware_loader/fallback.c:313
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff816baf30-ffffffff816bb0fe: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8170dfc0)
Location: drivers/base/firmware_loader/fallback.c:313
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff8170dfc0-ffffffff8170e18e: firmware_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void firmware_rw(struct fw_priv *fw_priv, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff81728c30)
Location: drivers/base/firmware_loader/fallback.c:313
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
```
**Symbols:**

```
ffffffff81728c30-ffffffff81728da2: firmware_rw (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fw_priv *fw_priv</code>
</li>
<li>
<b>Param removed. </b>
<code>struct firmware_buf *buf</code>
</li>
</ul>
</details>
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
