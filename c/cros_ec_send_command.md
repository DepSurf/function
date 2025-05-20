# Function: <code>cros_ec_send_command</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cros_ec_send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d71910)
Location: drivers/platform/chrome/cros_ec_proto.c:181
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info_legacy
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info
```
**Symbols:**

```
ffffffff81d71910-ffffffff81d719f9: cros_ec_send_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cros_ec_send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81ddf5f0)
Location: drivers/platform/chrome/cros_ec_proto.c:181
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info_legacy
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info
```
**Symbols:**

```
ffffffff81ddf5f0-ffffffff81ddf6d9: cros_ec_send_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cros_ec_send_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e95520)
Location: drivers/platform/chrome/cros_ec_proto.c:181
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_cmd_xfer
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info_legacy
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info
```
**Symbols:**

```
ffffffff81e95520-ffffffff81e95609: cros_ec_send_command (STB_LOCAL)
```
</details>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
