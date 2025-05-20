# Function: <code>get_next_event_xfer</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_next_event_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg, int version, uint32_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81879770)
Location: drivers/platform/chrome/cros_ec_proto.c:509
Inline: False
```
**Symbols:**

```
ffffffff81879770-ffffffff818797c6: get_next_event_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_next_event_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg, int version, uint32_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818be880)
Location: drivers/platform/chrome/cros_ec_proto.c:519
Inline: False
```
**Symbols:**

```
ffffffff818be880-ffffffff818be8d6: get_next_event_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_next_event_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg, int version, uint32_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818f13d0)
Location: drivers/platform/chrome/cros_ec_proto.c:520
Inline: False
```
**Symbols:**

```
ffffffff818f13d0-ffffffff818f1426: get_next_event_xfer (STB_LOCAL)
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c6c41)
Location: drivers/platform/chrome/cros_ec_proto.c:582
Inline: True
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c6b11)
Location: drivers/platform/chrome/cros_ec_proto.c:621
Inline: True
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819aba61)
Location: drivers/platform/chrome/cros_ec_proto.c:621
Inline: True
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81a595a0)
Location: drivers/platform/chrome/cros_ec_proto.c:630
Inline: True
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81bc94b9)
Location: drivers/platform/chrome/cros_ec_proto.c:664
Inline: True
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d72776)
Location: drivers/platform/chrome/cros_ec_proto.c:687
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81de0516)
Location: drivers/platform/chrome/cros_ec_proto.c:687
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e964d6)
Location: drivers/platform/chrome/cros_ec_proto.c:687
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:get_next_event
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
int get_next_event_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg, int version, uint32_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b794e8)
Location: drivers/platform/chrome/cros_ec_proto.c:520
Inline: False
```
**Symbols:**

```
ffff800010b794e8-ffff800010b79564: get_next_event_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_next_event_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg, int version, uint32_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (c0c5ee64)
Location: drivers/platform/chrome/cros_ec_proto.c:520
Inline: False
```
**Symbols:**

```
c0c5ee64-c0c5eec0: get_next_event_xfer (STB_LOCAL)
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
int get_next_event_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg, int version, uint32_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81892700)
Location: drivers/platform/chrome/cros_ec_proto.c:520
Inline: False
```
**Symbols:**

```
ffffffff81892700-ffffffff81892756: get_next_event_xfer (STB_LOCAL)
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
int get_next_event_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg, int version, uint32_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818e6200)
Location: drivers/platform/chrome/cros_ec_proto.c:520
Inline: False
```
**Symbols:**

```
ffffffff818e6200-ffffffff818e6256: get_next_event_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_next_event_xfer(struct cros_ec_device *ec_dev, struct cros_ec_command *msg, int version, uint32_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81902e80)
Location: drivers/platform/chrome/cros_ec_proto.c:520
Inline: False
```
**Symbols:**

```
ffffffff81902e80-ffffffff81902ed6: get_next_event_xfer (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
