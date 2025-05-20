# Function: <code>scsi_get_vpd_buf</code>

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
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816ac2b0)
Location: drivers/scsi/scsi.c:421
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
ffffffff816ac2b0-ffffffff816ac34a: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e87e0)
Location: drivers/scsi/scsi.c:421
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
ffffffff816e87e0-ffffffff816e887a: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170c2e0)
Location: drivers/scsi/scsi.c:421
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
ffffffff8170c2e0-ffffffff8170c37a: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81747a10)
Location: drivers/scsi/scsi.c:401
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
ffffffff81747a10-ffffffff81747a9e: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176bb60)
Location: drivers/scsi/scsi.c:401
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
ffffffff8176bb60-ffffffff8176bbee: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182de30)
Location: drivers/scsi/scsi.c:387
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff8182de30-ffffffff8182debe: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183ee70)
Location: drivers/scsi/scsi.c:387
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff8183ee70-ffffffff8183eefe: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81822080)
Location: drivers/scsi/scsi.c:400
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff81822080-ffffffff8182210e: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818ac9c0)
Location: drivers/scsi/scsi.c:393
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff818ac9c0-ffffffff818aca4e: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: drivers/scsi/scsi.c:400
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff819f7fe0-ffffffff819f809e: scsi_get_vpd_buf (STB_LOCAL)
ffffffff81ed4d14-ffffffff81ed4d5e: scsi_get_vpd_buf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: drivers/scsi/scsi.c:400
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff81b75950-ffffffff81b75a3f: scsi_get_vpd_buf (STB_LOCAL)
ffffffff8209b9f3-ffffffff8209ba0e: scsi_get_vpd_buf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: drivers/scsi/scsi.c:410
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff81bc9280-ffffffff81bc936f: scsi_get_vpd_buf (STB_LOCAL)
ffffffff8211c88a-ffffffff8211c8a5: scsi_get_vpd_buf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: drivers/scsi/scsi.c:428
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff81c1d6b0-ffffffff81c1d79f: scsi_get_vpd_buf (STB_LOCAL)
ffffffff821fa719-ffffffff821fa734: scsi_get_vpd_buf.cold (STB_LOCAL)
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
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096db08)
Location: drivers/scsi/scsi.c:401
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
ffff80001096db08-ffff80001096dbac: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a43584)
Location: drivers/scsi/scsi.c:401
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
c0a43584-c0a4360c: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a26e80)
Location: drivers/scsi/scsi.c:401
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
c000000000a26e80-c000000000a26f78: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d83d2)
Location: drivers/scsi/scsi.c:401
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
ffffffe0005d83d2-ffffffe0005d8462: scsi_get_vpd_buf (STB_LOCAL)
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
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81720250)
Location: drivers/scsi/scsi.c:401
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
ffffffff81720250-ffffffff817202de: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816f9680)
Location: drivers/scsi/scsi.c:401
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
ffffffff816f9680-ffffffff816f970e: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175f020)
Location: drivers/scsi/scsi.c:401
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
ffffffff8175f020-ffffffff8175f0ae: scsi_get_vpd_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct scsi_vpd *scsi_get_vpd_buf(struct scsi_device *sdev, u8 page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177a680)
Location: drivers/scsi/scsi.c:401
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_update_vpd_page
```
**Symbols:**

```
ffffffff8177a680-ffffffff8177a70e: scsi_get_vpd_buf (STB_LOCAL)
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
