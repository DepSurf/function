# Function: <code>cros_ec_get_host_command_version_mask</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8177b419)
Location: drivers/platform/chrome/cros_ec_proto.c:238
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81799df1)
Location: drivers/platform/chrome/cros_ec_proto.c:288
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81810191)
Location: drivers/platform/chrome/cros_ec_proto.c:290
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8185a11d)
Location: drivers/platform/chrome/cros_ec_proto.c:292
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818793bd)
Location: drivers/platform/chrome/cros_ec_proto.c:292
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818be2e0)
Location: drivers/platform/chrome/cros_ec_proto.c:296
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff818be2e0-ffffffff818be36e: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818f0e30)
Location: drivers/platform/chrome/cros_ec_proto.c:297
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff818f0e30-ffffffff818f0ebe: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c6420)
Location: drivers/platform/chrome/cros_ec_proto.c:320
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff819c6420-ffffffff819c64ae: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c6310)
Location: drivers/platform/chrome/cros_ec_proto.c:363
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff819c6310-ffffffff819c639e: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819ab1c0)
Location: drivers/platform/chrome/cros_ec_proto.c:363
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff819ab1c0-ffffffff819ab24e: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81a58ca0)
Location: drivers/platform/chrome/cros_ec_proto.c:372
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff81a58ca0-ffffffff81a58d2e: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81bc8a90)
Location: drivers/platform/chrome/cros_ec_proto.c:374
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff81bc8a90-ffffffff81bc8b25: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d71a10)
Location: drivers/platform/chrome/cros_ec_proto.c:446
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff81d71a10-ffffffff81d71b01: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81ddf6f0)
Location: drivers/platform/chrome/cros_ec_proto.c:446
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff81ddf6f0-ffffffff81ddf7e1: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e95620)
Location: drivers/platform/chrome/cros_ec_proto.c:446
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff81e95620-ffffffff81e9573f: cros_ec_get_host_command_version_mask (STB_LOCAL)
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
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b78e68)
Location: drivers/platform/chrome/cros_ec_proto.c:297
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffff800010b78e68-ffff800010b78f00: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (c0c5e79c)
Location: drivers/platform/chrome/cros_ec_proto.c:297
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
c0c5e79c-c0c5e830: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81892160)
Location: drivers/platform/chrome/cros_ec_proto.c:297
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff81892160-ffffffff818921ee: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818e5c60)
Location: drivers/platform/chrome/cros_ec_proto.c:297
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff818e5c60-ffffffff818e5cee: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cros_ec_get_host_command_version_mask(struct cros_ec_device *ec_dev, u16 cmd, u32 *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819028e0)
Location: drivers/platform/chrome/cros_ec_proto.c:297
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff819028e0-ffffffff8190296e: cros_ec_get_host_command_version_mask (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
