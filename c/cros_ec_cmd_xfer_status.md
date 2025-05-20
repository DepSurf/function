# Function: <code>cros_ec_cmd_xfer_status</code>

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
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81747e30)
Location: drivers/platform/chrome/cros_ec_proto.c:384
Inline: False
```
**Symbols:**

```
ffffffff81747e30-ffffffff81747eaa: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8177b7b0)
Location: drivers/platform/chrome/cros_ec_proto.c:427
Inline: False
```
**Symbols:**

```
ffffffff8177b7b0-ffffffff8177b82a: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8179a210)
Location: drivers/platform/chrome/cros_ec_proto.c:488
Inline: False
```
**Symbols:**

```
ffffffff8179a210-ffffffff8179a291: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818105b0)
Location: drivers/platform/chrome/cros_ec_proto.c:490
Inline: False
```
**Symbols:**

```
ffffffff818105b0-ffffffff81810631: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8185a450)
Location: drivers/platform/chrome/cros_ec_proto.c:492
Inline: False
```
**Symbols:**

```
ffffffff8185a450-ffffffff8185a4cc: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818796f0)
Location: drivers/platform/chrome/cros_ec_proto.c:492
Inline: False
```
**Symbols:**

```
ffffffff818796f0-ffffffff8187976c: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:502
Inline: False
```
**Symbols:**

```
ffffffff818bed18-ffffffff818bed36: cros_ec_cmd_xfer_status.cold (STB_LOCAL)
ffffffff818be820-ffffffff818be87e: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:503
Inline: False
```
**Symbols:**

```
ffffffff818f1868-ffffffff818f1886: cros_ec_cmd_xfer_status.cold (STB_LOCAL)
ffffffff818f1370-ffffffff818f13ce: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:561
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_check_features
```
**Symbols:**

```
ffffffff819c6e8c-ffffffff819c6eaa: cros_ec_cmd_xfer_status.cold (STB_LOCAL)
ffffffff819c68f0-ffffffff819c6983: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:566
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_sensor_count
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_check_features
```
**Symbols:**

```
ffffffff81c2d896-ffffffff81c2d8f9: cros_ec_cmd_xfer_status.cold (STB_LOCAL)
ffffffff819c6760-ffffffff819c687c: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:566
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_sensor_count
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_check_features
```
**Symbols:**

```
ffffffff81c1fafc-ffffffff81c1fb5f: cros_ec_cmd_xfer_status.cold (STB_LOCAL)
ffffffff819ab6b0-ffffffff819ab7cc: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:575
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_sensor_count
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_check_features
```
**Symbols:**

```
ffffffff81d3138d-ffffffff81d313f0: cros_ec_cmd_xfer_status.cold (STB_LOCAL)
ffffffff81a59180-ffffffff81a592ee: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81bc9070)
Location: drivers/platform/chrome/cros_ec_proto.c:644
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_command
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_sensor_count
```
**Symbols:**

```
ffffffff81bc9070-ffffffff81bc9144: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d72310)
Location: drivers/platform/chrome/cros_ec_proto.c:667
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_sensor_count
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event
```
**Symbols:**

```
ffffffff81d72310-ffffffff81d723c8: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81de0000)
Location: drivers/platform/chrome/cros_ec_proto.c:667
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_sensor_count
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event
```
**Symbols:**

```
ffffffff81de0000-ffffffff81de00b8: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e95fe0)
Location: drivers/platform/chrome/cros_ec_proto.c:667
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_sensor_count
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event
```
**Symbols:**

```
ffffffff81e95fe0-ffffffff81e96098: cros_ec_cmd_xfer_status (STB_GLOBAL)
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
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b79450)
Location: drivers/platform/chrome/cros_ec_proto.c:503
Inline: False
```
**Symbols:**

```
ffff800010b79450-ffff800010b794e8: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (c0c5eddc)
Location: drivers/platform/chrome/cros_ec_proto.c:503
Inline: False
```
**Symbols:**

```
c0c5eddc-c0c5ee64: cros_ec_cmd_xfer_status (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:503
Inline: False
```
**Symbols:**

```
ffffffff81892b98-ffffffff81892bb6: cros_ec_cmd_xfer_status.cold (STB_LOCAL)
ffffffff818926a0-ffffffff818926fe: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:503
Inline: False
```
**Symbols:**

```
ffffffff818e6698-ffffffff818e66b6: cros_ec_cmd_xfer_status.cold (STB_LOCAL)
ffffffff818e61a0-ffffffff818e61fe: cros_ec_cmd_xfer_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer_status(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:503
Inline: False
```
**Symbols:**

```
ffffffff81903318-ffffffff81903336: cros_ec_cmd_xfer_status.cold (STB_LOCAL)
ffffffff81902e20-ffffffff81902e7e: cros_ec_cmd_xfer_status (STB_GLOBAL)
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
