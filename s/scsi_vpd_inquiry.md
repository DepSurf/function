# Function: <code>scsi_vpd_inquiry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a6430)
Location: drivers/scsi/scsi.c:685
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
```
**Symbols:**

```
ffffffff815a6430-ffffffff815a64eb: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815fe6c0)
Location: drivers/scsi/scsi.c:685
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff815fe6c0-ffffffff815fe77b: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162dcf0)
Location: drivers/scsi/scsi.c:688
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff8162dcf0-ffffffff8162ddb3: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81643130)
Location: drivers/scsi/scsi.c:329
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_attach_vpd
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff81643130-ffffffff816431dd: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816ac140)
Location: drivers/scsi/scsi.c:329
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff816ac140-ffffffff816ac1ed: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e8660)
Location: drivers/scsi/scsi.c:329
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff816e8660-ffffffff816e8715: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170c160)
Location: drivers/scsi/scsi.c:329
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff8170c160-ffffffff8170c215: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81747890)
Location: drivers/scsi/scsi.c:309
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff81747890-ffffffff81747945: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176b9e0)
Location: drivers/scsi/scsi.c:309
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff8176b9e0-ffffffff8176ba95: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182dcb0)
Location: drivers/scsi/scsi.c:295
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff8182dcb0-ffffffff8182dd65: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183ecf0)
Location: drivers/scsi/scsi.c:295
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff8183ecf0-ffffffff8183eda5: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81821f00)
Location: drivers/scsi/scsi.c:308
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff81821f00-ffffffff81821fb5: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818ac840)
Location: drivers/scsi/scsi.c:301
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff818ac840-ffffffff818ac8f5: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f7e87)
Location: drivers/scsi/scsi.c:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_size
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff819f7640-ffffffff819f7719: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b75797)
Location: drivers/scsi/scsi.c:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_size
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff81b74420-ffffffff81b744f9: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc90c6)
Location: drivers/scsi/scsi.c:292
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_size
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff81bc7c00-ffffffff81bc7cd1: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1c770)
Location: drivers/scsi/scsi.c:292
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_size
  - drivers/scsi/scsi.c:scsi_get_vpd_size
```
**Symbols:**

```
ffffffff81c1c770-ffffffff81c1c841: scsi_vpd_inquiry (STB_LOCAL)
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
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096d918)
Location: drivers/scsi/scsi.c:309
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffff80001096d918-ffff80001096da14: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a433ac)
Location: drivers/scsi/scsi.c:309
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
c0a433ac-c0a434ac: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a26c10)
Location: drivers/scsi/scsi.c:309
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
c000000000a26c10-c000000000a26d40: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d826c)
Location: drivers/scsi/scsi.c:309
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffe0005d826c-ffffffe0005d8310: scsi_vpd_inquiry (STB_LOCAL)
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
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff817200d0)
Location: drivers/scsi/scsi.c:309
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff817200d0-ffffffff81720185: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816f9500)
Location: drivers/scsi/scsi.c:309
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff816f9500-ffffffff816f95b5: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175eea0)
Location: drivers/scsi/scsi.c:309
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff8175eea0-ffffffff8175ef55: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_vpd_inquiry(struct scsi_device *sdev, unsigned char *buffer, u8 page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177a500)
Location: drivers/scsi/scsi.c:309
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_get_vpd_buf
  - drivers/scsi/scsi.c:scsi_get_vpd_page
  - drivers/scsi/scsi.c:scsi_get_vpd_page
```
**Symbols:**

```
ffffffff8177a500-ffffffff8177a5b5: scsi_vpd_inquiry (STB_LOCAL)
```
</details>
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
