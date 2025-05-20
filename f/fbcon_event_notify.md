# Function: <code>fbcon_event_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fbcon_event_notify(struct notifier_block *self, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814659f0)
Location: drivers/video/console/fbcon.c:3251
Inline: False
```
**Symbols:**

```
ffffffff814659f0-ffffffff81466139: fbcon_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fbcon_event_notify(struct notifier_block *self, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814b3ca0)
Location: drivers/video/console/fbcon.c:3249
Inline: False
```
**Symbols:**

```
ffffffff814b3ca0-ffffffff814b4433: fbcon_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fbcon_event_notify(struct notifier_block *self, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814d5cd0)
Location: drivers/video/console/fbcon.c:3260
Inline: False
```
**Symbols:**

```
ffffffff814d5cd0-ffffffff814d6463: fbcon_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fbcon_event_notify(struct notifier_block *self, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814e0e00)
Location: drivers/video/console/fbcon.c:3258
Inline: False
```
**Symbols:**

```
ffffffff814e0e00-ffffffff814e1571: fbcon_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fbcon_event_notify(struct notifier_block *self, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8152aab0)
Location: drivers/video/fbdev/core/fbcon.c:3274
Inline: False
```
**Symbols:**

```
ffffffff8152aab0-ffffffff8152b227: fbcon_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fbcon_event_notify(struct notifier_block *self, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3282
Inline: False
```
**Symbols:**

```
ffffffff8155fa10-ffffffff815600bb: fbcon_event_notify (STB_LOCAL)
ffffffff81560d24-ffffffff81560dd6: fbcon_event_notify.cold.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fbcon_event_notify(struct notifier_block *self, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (0)
Location: drivers/video/fbdev/core/fbcon.c:3323
Inline: False
```
**Symbols:**

```
ffffffff81577ed0-ffffffff81578689: fbcon_event_notify (STB_LOCAL)
ffffffff81578747-ffffffff815787f9: fbcon_event_notify.cold.35 (STB_LOCAL)
```
</details>
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
</ul>
