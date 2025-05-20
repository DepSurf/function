# Function: <code>fw_copy_to_prealloc_buf</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8169a8c5)
Location: drivers/base/firmware_loader/main.c:100
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff816bb125)
Location: drivers/base/firmware_loader/main.c:100
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff816f599c)
Location: drivers/base/firmware_loader/main.c:101
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff81719d9c)
Location: drivers/base/firmware_loader/main.c:101
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff817d5710)
Location: drivers/base/firmware_loader/main.c:101
Inline: True
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
In drivers/base/firmware_loader/main.c (ffffffff817ea24f)
Location: drivers/base/firmware_loader/main.c:102
Inline: True
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
In drivers/base/firmware_loader/main.c (ffffffff817ce94f)
Location: drivers/base/firmware_loader/main.c:103
Inline: True
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
In drivers/base/firmware_loader/main.c (ffffffff818597a8)
Location: drivers/base/firmware_loader/main.c:103
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/builtin/main.c (ffffffff819a1af7)
Location: drivers/base/firmware_loader/builtin/main.c:19
Inline: True
Inline callers:
  - drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fw_copy_to_prealloc_buf(struct firmware *fw, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff81b137f0)
Location: drivers/base/firmware_loader/builtin/main.c:19
Inline: False
Direct callers:
  - drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf
```
**Symbols:**

```
ffffffff81b137f0-ffffffff81b13844: fw_copy_to_prealloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fw_copy_to_prealloc_buf(struct firmware *fw, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff81b62520)
Location: drivers/base/firmware_loader/builtin/main.c:19
Inline: False
Direct callers:
  - drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf
```
**Symbols:**

```
ffffffff81b62520-ffffffff81b62574: fw_copy_to_prealloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fw_copy_to_prealloc_buf(struct firmware *fw, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff81bb6030)
Location: drivers/base/firmware_loader/builtin/main.c:19
Inline: False
Direct callers:
  - drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf
```
**Symbols:**

```
ffffffff81bb6030-ffffffff81bb6084: fw_copy_to_prealloc_buf (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (ffff80001090d514)
Location: drivers/base/firmware_loader/main.c:101
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (c09f6524)
Location: drivers/base/firmware_loader/main.c:101
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (c0000000009ada44)
Location: drivers/base/firmware_loader/main.c:101
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffe000591fb2)
Location: drivers/base/firmware_loader/main.c:101
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816e00cc)
Location: drivers/base/firmware_loader/main.c:101
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816ba70c)
Location: drivers/base/firmware_loader/main.c:101
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170d646)
Location: drivers/base/firmware_loader/main.c:101
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
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
In drivers/base/firmware_loader/main.c (ffffffff8172840b)
Location: drivers/base/firmware_loader/main.c:101
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
