# Function: <code>cros_ec_get_next_event</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8177b830)
Location: drivers/platform/chrome/cros_ec_proto.c:484
Inline: False
```
**Symbols:**

```
ffffffff8177b830-ffffffff8177b910: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8179a2a0)
Location: drivers/platform/chrome/cros_ec_proto.c:550
Inline: True
```
**Symbols:**

```
ffffffff8179a2a0-ffffffff8179a428: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81810640)
Location: drivers/platform/chrome/cros_ec_proto.c:552
Inline: True
```
**Symbols:**

```
ffffffff81810640-ffffffff818107c8: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8185a4d0)
Location: drivers/platform/chrome/cros_ec_proto.c:554
Inline: True
```
**Symbols:**

```
ffffffff8185a4d0-ffffffff8185a662: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818797d0)
Location: drivers/platform/chrome/cros_ec_proto.c:576
Inline: True
```
**Symbols:**

```
ffffffff818797d0-ffffffff81879954: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818beac0)
Location: drivers/platform/chrome/cros_ec_proto.c:586
Inline: True
```
**Symbols:**

```
ffffffff818beac0-ffffffff818bec44: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818f1610)
Location: drivers/platform/chrome/cros_ec_proto.c:587
Inline: True
```
**Symbols:**

```
ffffffff818f1610-ffffffff818f1794: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event, bool *has_more_events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c6bc0)
Location: drivers/platform/chrome/cros_ec_proto.c:664
Inline: True
```
**Symbols:**

```
ffffffff819c6bc0-ffffffff819c6db4: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event, bool *has_more_events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c6a90)
Location: drivers/platform/chrome/cros_ec_proto.c:703
Inline: True
```
**Symbols:**

```
ffffffff819c6a90-ffffffff819c6c92: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event, bool *has_more_events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819ab9e0)
Location: drivers/platform/chrome/cros_ec_proto.c:703
Inline: True
```
**Symbols:**

```
ffffffff819ab9e0-ffffffff819abbe3: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event, bool *has_more_events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81a59562)
Location: drivers/platform/chrome/cros_ec_proto.c:712
Inline: True
```
**Symbols:**

```
ffffffff81d31434-ffffffff81d3146e: cros_ec_get_next_event.cold (STB_LOCAL)
ffffffff81a59510-ffffffff81a59744: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event, bool *has_more_events);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81bc946d)
Location: drivers/platform/chrome/cros_ec_proto.c:746
Inline: True
```
**Symbols:**

```
ffffffff81efd887-ffffffff81efd8bd: cros_ec_get_next_event.cold (STB_LOCAL)
ffffffff81bc9420-ffffffff81bc9667: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event, bool *has_more_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d72840)
Location: drivers/platform/chrome/cros_ec_proto.c:769
Inline: False
```
**Symbols:**

```
ffffffff81d72840-ffffffff81d72a70: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event, bool *has_more_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81de05e0)
Location: drivers/platform/chrome/cros_ec_proto.c:769
Inline: False
```
**Symbols:**

```
ffffffff81de05e0-ffffffff81de0810: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event, bool *has_more_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e965a0)
Location: drivers/platform/chrome/cros_ec_proto.c:769
Inline: False
```
**Symbols:**

```
ffffffff81e965a0-ffffffff81e967d0: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b79818)
Location: drivers/platform/chrome/cros_ec_proto.c:587
Inline: True
```
**Symbols:**

```
ffff800010b79818-ffff800010b799b4: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (c0c5f154)
Location: drivers/platform/chrome/cros_ec_proto.c:587
Inline: True
```
**Symbols:**

```
c0c5f154-c0c5f330: cros_ec_get_next_event (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81892940)
Location: drivers/platform/chrome/cros_ec_proto.c:587
Inline: True
```
**Symbols:**

```
ffffffff81892940-ffffffff81892ac4: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818e6440)
Location: drivers/platform/chrome/cros_ec_proto.c:587
Inline: True
```
**Symbols:**

```
ffffffff818e6440-ffffffff818e65c4: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int cros_ec_get_next_event(struct cros_ec_device *ec_dev, bool *wake_event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819030c0)
Location: drivers/platform/chrome/cros_ec_proto.c:587
Inline: True
```
**Symbols:**

```
ffffffff819030c0-ffffffff81903244: cros_ec_get_next_event (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *wake_event</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *has_more_events</code>
</li>
</ul>
</details>
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
