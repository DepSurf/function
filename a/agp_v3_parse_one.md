# Function: <code>agp_v3_parse_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8151cde6)
Location: drivers/char/agp/generic.c:585
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8156fb24)
Location: drivers/char/agp/generic.c:585
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8159c1e4)
Location: drivers/char/agp/generic.c:585
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
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
In drivers/char/agp/generic.c (ffffffff815b0200)
Location: drivers/char/agp/generic.c:581
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
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
In drivers/char/agp/generic.c (ffffffff81616da0)
Location: drivers/char/agp/generic.c:581
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
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
In drivers/char/agp/generic.c (ffffffff81650acd)
Location: drivers/char/agp/generic.c:581
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
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
In drivers/char/agp/generic.c (ffffffff8166ec8d)
Location: drivers/char/agp/generic.c:581
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
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
In drivers/char/agp/generic.c (ffffffff816a4854)
Location: drivers/char/agp/generic.c:581
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
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
In drivers/char/agp/generic.c (ffffffff816c7584)
Location: drivers/char/agp/generic.c:581
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void agp_v3_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:582
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff8177c050-ffffffff8177c16a: agp_v3_parse_one (STB_LOCAL)
ffffffff8177d40f-ffffffff8177d5c6: agp_v3_parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void agp_v3_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:582
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff817951a0-ffffffff817952ba: agp_v3_parse_one (STB_LOCAL)
ffffffff81c08e9f-ffffffff81c09056: agp_v3_parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void agp_v3_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:582
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff81777e50-ffffffff81777f6a: agp_v3_parse_one (STB_LOCAL)
ffffffff81bfaa52-ffffffff81bfac09: agp_v3_parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void agp_v3_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:582
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff817fd8f0-ffffffff817fda0a: agp_v3_parse_one (STB_LOCAL)
ffffffff81cfb4a2-ffffffff81cfb659: agp_v3_parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void agp_v3_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:582
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff8193c960-ffffffff8193ca88: agp_v3_parse_one (STB_LOCAL)
ffffffff81ec3c2b-ffffffff81ec3dd7: agp_v3_parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void agp_v3_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81a9d490)
Location: drivers/char/agp/generic.c:582
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff81a9d490-ffffffff81a9d7a5: agp_v3_parse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void agp_v3_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81ae8df0)
Location: drivers/char/agp/generic.c:582
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff81ae8df0-ffffffff81ae9105: agp_v3_parse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void agp_v3_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81b3c280)
Location: drivers/char/agp/generic.c:582
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff81b3c280-ffffffff81b3c595: agp_v3_parse_one (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (c000000000954934)
Location: drivers/char/agp/generic.c:581
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
</details>
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
In drivers/char/agp/generic.c (ffffffff8168cfd4)
Location: drivers/char/agp/generic.c:581
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8166a9c4)
Location: drivers/char/agp/generic.c:581
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816bb244)
Location: drivers/char/agp/generic.c:581
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
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
In drivers/char/agp/generic.c (ffffffff816d5814)
Location: drivers/char/agp/generic.c:581
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
