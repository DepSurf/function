# Function: <code>get_next_event</code>

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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8177b841)
Location: drivers/platform/chrome/cros_ec_proto.c:444
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8179a366)
Location: drivers/platform/chrome/cros_ec_proto.c:505
Inline: True
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81810706)
Location: drivers/platform/chrome/cros_ec_proto.c:507
Inline: True
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8185a596)
Location: drivers/platform/chrome/cros_ec_proto.c:509
Inline: True
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8187988e)
Location: drivers/platform/chrome/cros_ec_proto.c:529
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818beb7e)
Location: drivers/platform/chrome/cros_ec_proto.c:539
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818f16ce)
Location: drivers/platform/chrome/cros_ec_proto.c:540
Inline: True
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c6c12)
Location: drivers/platform/chrome/cros_ec_proto.c:603
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c6ae2)
Location: drivers/platform/chrome/cros_ec_proto.c:642
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819aba32)
Location: drivers/platform/chrome/cros_ec_proto.c:642
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81a59562)
Location: drivers/platform/chrome/cros_ec_proto.c:651
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
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81bc946d)
Location: drivers/platform/chrome/cros_ec_proto.c:685
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int get_next_event(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:708
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
```
**Symbols:**

```
ffffffff81d72700-ffffffff81d7282d: get_next_event (STB_LOCAL)
ffffffff820aa1a5-ffffffff820aa1ba: get_next_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int get_next_event(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:708
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
```
**Symbols:**

```
ffffffff81de04a0-ffffffff81de05cd: get_next_event (STB_LOCAL)
ffffffff8212b6a4-ffffffff8212b6b9: get_next_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int get_next_event(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: drivers/platform/chrome/cros_ec_proto.c:708
Inline: False
Direct callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_next_event
```
**Symbols:**

```
ffffffff81e96460-ffffffff81e9658d: get_next_event (STB_LOCAL)
ffffffff8220d2b6-ffffffff8220d2cb: get_next_event.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b798bc)
Location: drivers/platform/chrome/cros_ec_proto.c:540
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (c0c5f240)
Location: drivers/platform/chrome/cros_ec_proto.c:540
Inline: True
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818929fe)
Location: drivers/platform/chrome/cros_ec_proto.c:540
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818e64fe)
Location: drivers/platform/chrome/cros_ec_proto.c:540
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8190317e)
Location: drivers/platform/chrome/cros_ec_proto.c:540
Inline: True
```
</details>
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
