# Function: <code>firmware_rw_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b2eb7)
Location: drivers/base/firmware_class.c:715
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_data_read
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
In drivers/base/firmware_class.c (ffffffff815e22b7)
Location: drivers/base/firmware_class.c:776
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_data_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void firmware_rw_buf(struct firmware_buf *buf, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f6dd0)
Location: drivers/base/firmware_class.c:806
Inline: True
Direct callers:
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_data_read
```
**Symbols:**

```
ffffffff815f6dd0-ffffffff815f6e02: firmware_rw_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void firmware_rw_buf(struct firmware_buf *buf, char *buffer, loff_t offset, size_t count, bool read);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8165ed00)
Location: drivers/base/firmware_class.c:810
Inline: True
Direct callers:
  - drivers/base/firmware_class.c:firmware_data_write
  - drivers/base/firmware_class.c:firmware_data_read
```
**Symbols:**

```
ffffffff8165ed00-ffffffff8165ed32: firmware_rw_buf (STB_LOCAL)
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
