# Function: <code>agp_collect_device_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8151cd30)
Location: drivers/char/agp/generic.c:724
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_enable
```
**Symbols:**

```
ffffffff8151cd30-ffffffff8151d2ab: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8156fa70)
Location: drivers/char/agp/generic.c:724
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_enable
```
**Symbols:**

```
ffffffff8156fa70-ffffffff8156ffea: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8159c130)
Location: drivers/char/agp/generic.c:724
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_enable
```
**Symbols:**

```
ffffffff8159c130-ffffffff8159c6aa: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff815b0150)
Location: drivers/char/agp/generic.c:720
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_enable
```
**Symbols:**

```
ffffffff815b0150-ffffffff815b06f1: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81616cf0)
Location: drivers/char/agp/generic.c:720
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_enable
```
**Symbols:**

```
ffffffff81616cf0-ffffffff81617291: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:720
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_enable
```
**Symbols:**

```
ffffffff81651f55-ffffffff816521ea: agp_collect_device_status.cold.16 (STB_LOCAL)
ffffffff81650a10-ffffffff81650d8b: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:720
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_enable
```
**Symbols:**

```
ffffffff81670125-ffffffff816703be: agp_collect_device_status.cold.15 (STB_LOCAL)
ffffffff8166ebd0-ffffffff8166ef4b: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:720
Inline: False
```
**Symbols:**

```
ffffffff816a5ba5-ffffffff816a5ded: agp_collect_device_status.cold (STB_LOCAL)
ffffffff816a4790-ffffffff816a4aea: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:720
Inline: False
```
**Symbols:**

```
ffffffff816c88d5-ffffffff816c8b1d: agp_collect_device_status.cold (STB_LOCAL)
ffffffff816c74c0-ffffffff816c781a: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:721
Inline: False
```
**Symbols:**

```
ffffffff8177d631-ffffffff8177d644: agp_collect_device_status.cold (STB_LOCAL)
ffffffff8177c300-ffffffff8177c3f6: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:721
Inline: False
```
**Symbols:**

```
ffffffff81c090c1-ffffffff81c090d4: agp_collect_device_status.cold (STB_LOCAL)
ffffffff81795450-ffffffff81795546: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:721
Inline: False
```
**Symbols:**

```
ffffffff81bfac74-ffffffff81bfac87: agp_collect_device_status.cold (STB_LOCAL)
ffffffff81778100-ffffffff817781f6: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:721
Inline: False
```
**Symbols:**

```
ffffffff81cfb6c4-ffffffff81cfb6d7: agp_collect_device_status.cold (STB_LOCAL)
ffffffff817fdba0-ffffffff817fdc96: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:721
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_enable
```
**Symbols:**

```
ffffffff81ec3e42-ffffffff81ec3e55: agp_collect_device_status.cold (STB_LOCAL)
ffffffff8193ccc0-ffffffff8193cdc7: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81a9da90)
Location: drivers/char/agp/generic.c:721
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_enable
```
**Symbols:**

```
ffffffff81a9da90-ffffffff81a9dbac: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81ae9430)
Location: drivers/char/agp/generic.c:721
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_enable
```
**Symbols:**

```
ffffffff81ae9430-ffffffff81ae954c: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81b3c8c0)
Location: drivers/char/agp/generic.c:721
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_enable
```
**Symbols:**

```
ffffffff81b3c8c0-ffffffff81b3c9dc: agp_collect_device_status (STB_GLOBAL)
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (c000000000954840)
Location: drivers/char/agp/generic.c:720
Inline: False
```
**Symbols:**

```
c000000000954840-c000000000954eec: agp_collect_device_status (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:720
Inline: False
```
**Symbols:**

```
ffffffff8168e325-ffffffff8168e56d: agp_collect_device_status.cold (STB_LOCAL)
ffffffff8168cf10-ffffffff8168d26a: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:720
Inline: False
```
**Symbols:**

```
ffffffff8166bd15-ffffffff8166bf5d: agp_collect_device_status.cold (STB_LOCAL)
ffffffff8166a900-ffffffff8166ac5a: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:720
Inline: False
```
**Symbols:**

```
ffffffff816bc595-ffffffff816bc7dd: agp_collect_device_status.cold (STB_LOCAL)
ffffffff816bb180-ffffffff816bb4da: agp_collect_device_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
u32 agp_collect_device_status(struct agp_bridge_data *bridge, u32 requested_mode, u32 bridge_agpstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/agp/generic.c (0)
Location: drivers/char/agp/generic.c:720
Inline: False
```
**Symbols:**

```
ffffffff816d6b65-ffffffff816d6dad: agp_collect_device_status.cold (STB_LOCAL)
ffffffff816d5750-ffffffff816d5aaa: agp_collect_device_status (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
