# Function: <code>cros_ec_cmd_xfer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff816e3a40)
Location: drivers/platform/chrome/cros_ec_proto.c:337
Inline: False
```
**Symbols:**

```
ffffffff816e3a40-ffffffff816e3b63: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81747d10)
Location: drivers/platform/chrome/cros_ec_proto.c:337
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff81747d10-ffffffff81747e24: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8177b690)
Location: drivers/platform/chrome/cros_ec_proto.c:380
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
**Symbols:**

```
ffffffff8177b690-ffffffff8177b7a4: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8179a0f0)
Location: drivers/platform/chrome/cros_ec_proto.c:441
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff8179a0f0-ffffffff8179a204: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81810490)
Location: drivers/platform/chrome/cros_ec_proto.c:443
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff81810490-ffffffff818105a4: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8185a330)
Location: drivers/platform/chrome/cros_ec_proto.c:445
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff8185a330-ffffffff8185a444: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818795d0)
Location: drivers/platform/chrome/cros_ec_proto.c:445
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff818795d0-ffffffff818796e4: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:455
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff818becb2-ffffffff818bed18: cros_ec_cmd_xfer.cold (STB_LOCAL)
ffffffff818be750-ffffffff818be81b: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:456
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff818f1802-ffffffff818f1868: cros_ec_cmd_xfer.cold (STB_LOCAL)
ffffffff818f12a0-ffffffff818f136b: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:499
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_sensor_count
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff819c6e26-ffffffff819c6e8c: cros_ec_cmd_xfer.cold (STB_LOCAL)
ffffffff819c6820-ffffffff819c68eb: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:584
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff81efd7ef-ffffffff81efd849: cros_ec_cmd_xfer.cold (STB_LOCAL)
ffffffff81bc8fa0-ffffffff81bc906b: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d721e0)
Location: drivers/platform/chrome/cros_ec_proto.c:607
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff81d721e0-ffffffff81d722fb: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81ddfed0)
Location: drivers/platform/chrome/cros_ec_proto.c:607
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff81ddfed0-ffffffff81ddffeb: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e95eb0)
Location: drivers/platform/chrome/cros_ec_proto.c:607
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff81e95eb0-ffffffff81e95fcb: cros_ec_cmd_xfer (STB_GLOBAL)
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
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b79318)
Location: drivers/platform/chrome/cros_ec_proto.c:456
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffff800010b79318-ffff800010b7944c: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (c0c5ecb0)
Location: drivers/platform/chrome/cros_ec_proto.c:456
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
c0c5ecb0-c0c5eddc: cros_ec_cmd_xfer (STB_GLOBAL)
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
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:456
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff81892b32-ffffffff81892b98: cros_ec_cmd_xfer.cold (STB_LOCAL)
ffffffff818925d0-ffffffff8189269b: cros_ec_cmd_xfer (STB_GLOBAL)
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
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:456
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff818e6632-ffffffff818e6698: cros_ec_cmd_xfer.cold (STB_LOCAL)
ffffffff818e60d0-ffffffff818e619b: cros_ec_cmd_xfer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cros_ec_cmd_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:456
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
```
**Symbols:**

```
ffffffff819032b2-ffffffff81903318: cros_ec_cmd_xfer.cold (STB_LOCAL)
ffffffff81902d50-ffffffff81902e1b: cros_ec_cmd_xfer (STB_GLOBAL)
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
