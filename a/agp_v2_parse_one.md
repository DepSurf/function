# Function: <code>agp_v2_parse_one</code>

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
In drivers/char/agp/generic.c (ffffffff8151cef0)
Location: drivers/char/agp/generic.c:482
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
In drivers/char/agp/generic.c (ffffffff8156fc30)
Location: drivers/char/agp/generic.c:482
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
In drivers/char/agp/generic.c (ffffffff8159c2f0)
Location: drivers/char/agp/generic.c:482
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
In drivers/char/agp/generic.c (ffffffff815b0308)
Location: drivers/char/agp/generic.c:478
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
In drivers/char/agp/generic.c (ffffffff81616ea8)
Location: drivers/char/agp/generic.c:478
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
In drivers/char/agp/generic.c (ffffffff81650be0)
Location: drivers/char/agp/generic.c:478
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
In drivers/char/agp/generic.c (ffffffff8166eda0)
Location: drivers/char/agp/generic.c:478
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
In drivers/char/agp/generic.c (ffffffff816a494c)
Location: drivers/char/agp/generic.c:478
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
In drivers/char/agp/generic.c (ffffffff816c767c)
Location: drivers/char/agp/generic.c:478
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
void agp_v2_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:479
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff8177c170-ffffffff8177c2fa: agp_v2_parse_one (STB_LOCAL)
ffffffff8177d5c6-ffffffff8177d631: agp_v2_parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void agp_v2_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:479
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff817952c0-ffffffff8179544a: agp_v2_parse_one (STB_LOCAL)
ffffffff81c09056-ffffffff81c090c1: agp_v2_parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void agp_v2_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:479
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff81777f70-ffffffff817780fa: agp_v2_parse_one (STB_LOCAL)
ffffffff81bfac09-ffffffff81bfac74: agp_v2_parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void agp_v2_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:479
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff817fda10-ffffffff817fdb9a: agp_v2_parse_one (STB_LOCAL)
ffffffff81cfb659-ffffffff81cfb6c4: agp_v2_parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void agp_v2_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:479
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff8193ca90-ffffffff8193cc30: agp_v2_parse_one (STB_LOCAL)
ffffffff81ec3dd7-ffffffff81ec3e42: agp_v2_parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void agp_v2_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81a9d7c0)
Location: drivers/char/agp/generic.c:479
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff81a9d7c0-ffffffff81a9d9db: agp_v2_parse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void agp_v2_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81ae9120)
Location: drivers/char/agp/generic.c:479
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff81ae9120-ffffffff81ae937b: agp_v2_parse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void agp_v2_parse_one(u32 *requested_mode, u32 *bridge_agpstat, u32 *vga_agpstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81b3c5b0)
Location: drivers/char/agp/generic.c:479
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_collect_device_status
```
**Symbols:**

```
ffffffff81b3c5b0-ffffffff81b3c80b: agp_v2_parse_one (STB_LOCAL)
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
In drivers/char/agp/generic.c (c0000000009549e0)
Location: drivers/char/agp/generic.c:478
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
In drivers/char/agp/generic.c (ffffffff8168d0cc)
Location: drivers/char/agp/generic.c:478
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
In drivers/char/agp/generic.c (ffffffff8166aabc)
Location: drivers/char/agp/generic.c:478
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
In drivers/char/agp/generic.c (ffffffff816bb33c)
Location: drivers/char/agp/generic.c:478
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
In drivers/char/agp/generic.c (ffffffff816d590c)
Location: drivers/char/agp/generic.c:478
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
