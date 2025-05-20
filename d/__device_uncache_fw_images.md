# Function: <code>__device_uncache_fw_images</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8155f08f)
Location: drivers/base/firmware_class.c:1544
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b3707)
Location: drivers/base/firmware_class.c:1592
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
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
In drivers/base/firmware_class.c (ffffffff815e2a97)
Location: drivers/base/firmware_class.c:1627
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
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
In drivers/base/firmware_class.c (ffffffff815f77d7)
Location: drivers/base/firmware_class.c:1627
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
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
In drivers/base/firmware_class.c (ffffffff8165f767)
Location: drivers/base/firmware_class.c:1634
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffffffff8169a50b)
Location: drivers/base/firmware_loader/main.c:1051
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffffffff816baceb)
Location: drivers/base/firmware_loader/main.c:1060
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffffffff816f522b)
Location: drivers/base/firmware_loader/main.c:1250
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffffffff8171962b)
Location: drivers/base/firmware_loader/main.c:1250
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __device_uncache_fw_images();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d5420)
Location: drivers/base/firmware_loader/main.c:1281
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff817d5420-ffffffff817d55a6: __device_uncache_fw_images (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __device_uncache_fw_images();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817e9cf0)
Location: drivers/base/firmware_loader/main.c:1354
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff817e9cf0-ffffffff817e9e76: __device_uncache_fw_images (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (ffffffff817ce437)
Location: drivers/base/firmware_loader/main.c:1358
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffffffff81858ce7)
Location: drivers/base/firmware_loader/main.c:1356
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffffffff8199fa2a)
Location: drivers/base/firmware_loader/main.c:1381
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffffffff81b114da)
Location: drivers/base/firmware_loader/main.c:1381
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffffffff81b5f76a)
Location: drivers/base/firmware_loader/main.c:1436
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffffffff81bb317a)
Location: drivers/base/firmware_loader/main.c:1437
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffff80001090cc24)
Location: drivers/base/firmware_loader/main.c:1250
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (c09f5df0)
Location: drivers/base/firmware_loader/main.c:1250
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (c0000000009ac944)
Location: drivers/base/firmware_loader/main.c:1250
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/base/firmware_loader/main.c (ffffffff816df95b)
Location: drivers/base/firmware_loader/main.c:1250
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffffffff816b9f9b)
Location: drivers/base/firmware_loader/main.c:1250
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffffffff8170d07b)
Location: drivers/base/firmware_loader/main.c:1250
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
In drivers/base/firmware_loader/main.c (ffffffff81727d37)
Location: drivers/base/firmware_loader/main.c:1250
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
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
