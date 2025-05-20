# Function: <code>disk_event_uevent</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void disk_event_uevent(struct gendisk *disk, unsigned int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff815ee8e0)
Location: block/disk-events.c:171
Inline: False
Direct callers:
  - block/disk-events.c:disk_check_events
```
**Symbols:**

```
ffffffff815ee8e0-ffffffff815ee973: disk_event_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void disk_event_uevent(struct gendisk *disk, unsigned int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8169f1d0)
Location: block/disk-events.c:171
Inline: False
Direct callers:
  - block/disk-events.c:disk_check_events
```
**Symbols:**

```
ffffffff8169f1d0-ffffffff8169f26f: disk_event_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void disk_event_uevent(struct gendisk *disk, unsigned int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8175dac0)
Location: block/disk-events.c:171
Inline: False
Direct callers:
  - block/disk-events.c:disk_check_events
```
**Symbols:**

```
ffffffff8175dac0-ffffffff8175db5f: disk_event_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void disk_event_uevent(struct gendisk *disk, unsigned int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff8179c9b0)
Location: block/disk-events.c:171
Inline: False
Direct callers:
  - block/disk-events.c:disk_check_events
```
**Symbols:**

```
ffffffff8179c9b0-ffffffff8179ca52: disk_event_uevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disk_event_uevent(struct gendisk *disk, unsigned int events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/disk-events.c (ffffffff817e0430)
Location: block/disk-events.c:171
Inline: False
Direct callers:
  - block/disk-events.c:disk_force_media_change
  - block/disk-events.c:disk_check_events
```
**Symbols:**

```
ffffffff817e0430-ffffffff817e04d2: disk_event_uevent (STB_LOCAL)
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
