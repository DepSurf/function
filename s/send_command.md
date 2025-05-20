# Function: <code>send_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff816e3370)
Location: drivers/platform/chrome/cros_ec_proto.c:58
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
```
**Symbols:**

```
ffffffff816e3370-ffffffff816e3450: send_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81747660)
Location: drivers/platform/chrome/cros_ec_proto.c:58
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff81747660-ffffffff8174773f: send_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8177af70)
Location: drivers/platform/chrome/cros_ec_proto.c:59
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff8177af70-ffffffff8177b04f: send_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81799920)
Location: drivers/platform/chrome/cros_ec_proto.c:59
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff81799920-ffffffff81799a01: send_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8180fcc0)
Location: drivers/platform/chrome/cros_ec_proto.c:59
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff8180fcc0-ffffffff8180fda8: send_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81859b50)
Location: drivers/platform/chrome/cros_ec_proto.c:59
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff81859b50-ffffffff81859c41: send_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81878df0)
Location: drivers/platform/chrome/cros_ec_proto.c:59
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff81878df0-ffffffff81878ee1: send_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:50
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff818be0c0-ffffffff818be218: send_command (STB_LOCAL)
ffffffff818bec44-ffffffff818bec65: send_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:51
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff818f0c10-ffffffff818f0d68: send_command (STB_LOCAL)
ffffffff818f1794-ffffffff818f17b5: send_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:51
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query_v2
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff819c6050-ffffffff819c628e: send_command (STB_LOCAL)
ffffffff819c6dcf-ffffffff819c6df1: send_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:88
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query_v2
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff819c5f90-ffffffff819c6174: send_command (STB_LOCAL)
ffffffff81c2d83f-ffffffff81c2d861: send_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:88
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff819aaf10-ffffffff819ab0f4: send_command (STB_LOCAL)
ffffffff81c1fa8d-ffffffff81c1faaf: send_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:88
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer_status
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff81a589e0-ffffffff81a58bcc: send_command (STB_LOCAL)
ffffffff81d31309-ffffffff81d31340: send_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:88
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff81bc8700-ffffffff81bc8962: send_command (STB_LOCAL)
ffffffff81efd771-ffffffff81efd7a2: send_command.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b78be8)
Location: drivers/platform/chrome/cros_ec_proto.c:51
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffff800010b78be8-ffff800010b78d88: send_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (c0c5e51c)
Location: drivers/platform/chrome/cros_ec_proto.c:51
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
c0c5e51c-c0c5e6d8: send_command (STB_LOCAL)
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
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:51
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff81891f40-ffffffff81892098: send_command (STB_LOCAL)
ffffffff81892ac4-ffffffff81892ae5: send_command.cold (STB_LOCAL)
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
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:51
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff818e5a40-ffffffff818e5b98: send_command (STB_LOCAL)
ffffffff818e65c4-ffffffff818e65e5: send_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:51
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_host_command_proto_query
```
**Symbols:**

```
ffffffff819026a0-ffffffff81902814: send_command (STB_LOCAL)
ffffffff81903244-ffffffff81903265: send_command.cold (STB_LOCAL)
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
