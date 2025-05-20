# Function: <code>cros_ec_xfer_command</code>

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
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cros_ec_xfer_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d718ba)
Location: drivers/platform/chrome/cros_ec_proto.c:110
Inline: True
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command
```
**Symbols:**

```
ffffffff81d717e0-ffffffff81d718f5: cros_ec_xfer_command (STB_LOCAL)
ffffffff820aa177-ffffffff820aa18c: cros_ec_xfer_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cros_ec_xfer_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81ddf59a)
Location: drivers/platform/chrome/cros_ec_proto.c:110
Inline: True
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command
```
**Symbols:**

```
ffffffff81ddf4c0-ffffffff81ddf5d5: cros_ec_xfer_command (STB_LOCAL)
ffffffff8212b653-ffffffff8212b668: cros_ec_xfer_command.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cros_ec_xfer_command(struct cros_ec_device *ec_dev, struct cros_ec_command *msg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e954ca)
Location: drivers/platform/chrome/cros_ec_proto.c:110
Inline: True
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_send_command
```
**Symbols:**

```
ffffffff81e953f0-ffffffff81e95505: cros_ec_xfer_command (STB_LOCAL)
ffffffff8220d288-ffffffff8220d29d: cros_ec_xfer_command.cold (STB_LOCAL)
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
