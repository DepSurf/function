# Function: <code>scsi_update_vpd_page</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816ac350)
Location: drivers/scsi/scsi.c:447
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff816ac350-ffffffff816ac3ae: scsi_update_vpd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e8880)
Location: drivers/scsi/scsi.c:447
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff816e8880-ffffffff816e88de: scsi_update_vpd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170c380)
Location: drivers/scsi/scsi.c:447
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff8170c380-ffffffff8170c3de: scsi_update_vpd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81747aa0)
Location: drivers/scsi/scsi.c:427
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff81747aa0-ffffffff81747afe: scsi_update_vpd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176bbf0)
Location: drivers/scsi/scsi.c:427
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff8176bbf0-ffffffff8176bc4e: scsi_update_vpd_page (STB_LOCAL)
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
In drivers/scsi/scsi.c (ffffffff8182eacf)
Location: drivers/scsi/scsi.c:413
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
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
In drivers/scsi/scsi.c (ffffffff8183fb0f)
Location: drivers/scsi/scsi.c:413
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
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
In drivers/scsi/scsi.c (ffffffff81822d8f)
Location: drivers/scsi/scsi.c:426
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
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
In drivers/scsi/scsi.c (ffffffff818ad6af)
Location: drivers/scsi/scsi.c:419
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
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
In drivers/scsi/scsi.c (ffffffff819f83f5)
Location: drivers/scsi/scsi.c:437
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
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
In drivers/scsi/scsi.c (ffffffff81b75de2)
Location: drivers/scsi/scsi.c:437
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
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
In drivers/scsi/scsi.c (ffffffff81bc9702)
Location: drivers/scsi/scsi.c:447
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
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
In drivers/scsi/scsi.c (ffffffff81c1e2f2)
Location: drivers/scsi/scsi.c:465
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096dbb0)
Location: drivers/scsi/scsi.c:427
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffff80001096dbb0-ffff80001096dc24: scsi_update_vpd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a4360c)
Location: drivers/scsi/scsi.c:427
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
c0a4360c-c0a4366c: scsi_update_vpd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a26f80)
Location: drivers/scsi/scsi.c:427
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
c000000000a26f80-c000000000a27018: scsi_update_vpd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d8462)
Location: drivers/scsi/scsi.c:427
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffe0005d8462-ffffffe0005d84d6: scsi_update_vpd_page (STB_LOCAL)
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
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff817202e0)
Location: drivers/scsi/scsi.c:427
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff817202e0-ffffffff8172033e: scsi_update_vpd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816f9710)
Location: drivers/scsi/scsi.c:427
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff816f9710-ffffffff816f976e: scsi_update_vpd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175f0b0)
Location: drivers/scsi/scsi.c:427
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff8175f0b0-ffffffff8175f10e: scsi_update_vpd_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_update_vpd_page(struct scsi_device *sdev, u8 page, struct scsi_vpd **sdev_vpd_buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177a710)
Location: drivers/scsi/scsi.c:427
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff8177a710-ffffffff8177a76e: scsi_update_vpd_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
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
