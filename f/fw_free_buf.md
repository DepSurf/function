# Function: <code>fw_free_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fw_free_buf(struct firmware_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8155ef30)
Location: drivers/base/firmware_class.c:268
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:release_firmware
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff8155ef30-ffffffff8155ef6d: fw_free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fw_free_buf(struct firmware_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b3470)
Location: drivers/base/firmware_class.c:282
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
  - drivers/base/firmware_class.c:release_firmware
```
**Symbols:**

```
ffffffff815b3470-ffffffff815b34ad: fw_free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fw_free_buf(struct firmware_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e2800)
Location: drivers/base/firmware_class.c:359
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
  - drivers/base/firmware_class.c:release_firmware
```
**Symbols:**

```
ffffffff815e2800-ffffffff815e283d: fw_free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fw_free_buf(struct firmware_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f6b60)
Location: drivers/base/firmware_class.c:355
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff815f6b60-ffffffff815f6c72: fw_free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fw_free_buf(struct firmware_buf *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8165f4a0)
Location: drivers/base/firmware_class.c:359
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff8165f4a0-ffffffff8165f4e2: fw_free_buf (STB_LOCAL)
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
