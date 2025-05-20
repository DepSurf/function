# Function: <code>check_for_audio_disc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff815ff530)
Location: drivers/cdrom/cdrom.c:1201
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff815ff530-ffffffff815ff80a: check_for_audio_disc.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8165f480)
Location: drivers/cdrom/cdrom.c:1201
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff8165f480-ffffffff8165f723: check_for_audio_disc.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8168d270)
Location: drivers/cdrom/cdrom.c:1201
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff8168d270-ffffffff8168d513: check_for_audio_disc.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff816a25f0)
Location: drivers/cdrom/cdrom.c:1199
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff816a25f0-ffffffff816a289f: check_for_audio_disc.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8170d8d0)
Location: drivers/cdrom/cdrom.c:1199
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff8170d8d0-ffffffff8170db90: check_for_audio_disc.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8174cb20)
Location: drivers/cdrom/cdrom.c:1196
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff8174cb20-ffffffff8174cddf: check_for_audio_disc.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81770dc0)
Location: drivers/cdrom/cdrom.c:1196
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81770dc0-ffffffff8177107f: check_for_audio_disc.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817aec60)
Location: drivers/cdrom/cdrom.c:1197
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff817aec60-ffffffff817aef2e: check_for_audio_disc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817def60)
Location: drivers/cdrom/cdrom.c:1204
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff817def60-ffffffff817df22e: check_for_audio_disc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_for_audio_disc(struct cdrom_device_info *cdi, const struct cdrom_device_ops *cdo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818ab620)
Location: drivers/cdrom/cdrom.c:1207
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_audioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl_play_trkind
```
**Symbols:**

```
ffffffff818ab620-ffffffff818ab8fa: check_for_audio_disc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_for_audio_disc(struct cdrom_device_info *cdi, const struct cdrom_device_ops *cdo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818ba340)
Location: drivers/cdrom/cdrom.c:1207
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_audioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl_play_trkind
```
**Symbols:**

```
ffffffff818ba340-ffffffff818ba61a: check_for_audio_disc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_for_audio_disc(struct cdrom_device_info *cdi, const struct cdrom_device_ops *cdo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8189d710)
Location: drivers/cdrom/cdrom.c:1207
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff8189d710-ffffffff8189d9ea: check_for_audio_disc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_for_audio_disc(struct cdrom_device_info *cdi, const struct cdrom_device_ops *cdo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1207
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff819323a0-ffffffff81932689: check_for_audio_disc (STB_LOCAL)
ffffffff81d12b5f-ffffffff81d12c14: check_for_audio_disc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_for_audio_disc(struct cdrom_device_info *cdi, const struct cdrom_device_ops *cdo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1208
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81a89760-ffffffff81a89a65: check_for_audio_disc (STB_LOCAL)
ffffffff81edd8a3-ffffffff81edd95e: check_for_audio_disc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_for_audio_disc(struct cdrom_device_info *cdi, const struct cdrom_device_ops *cdo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1208
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81c0a640-ffffffff81c0a942: check_for_audio_disc (STB_LOCAL)
ffffffff8209df0d-ffffffff8209dfc8: check_for_audio_disc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_for_audio_disc(struct cdrom_device_info *cdi, const struct cdrom_device_ops *cdo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1200
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81c71570-ffffffff81c71872: check_for_audio_disc (STB_LOCAL)
ffffffff8211f485-ffffffff8211f540: check_for_audio_disc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_for_audio_disc(struct cdrom_device_info *cdi, const struct cdrom_device_ops *cdo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1200
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81d25e20-ffffffff81d26122: check_for_audio_disc (STB_LOCAL)
ffffffff82200c5b-ffffffff82200d16: check_for_audio_disc.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffff800010a0bba0)
Location: drivers/cdrom/cdrom.c:1204
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffff800010a0bba0-ffff800010a0be84: check_for_audio_disc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int check_for_audio_disc(struct cdrom_device_info *cdi, const struct cdrom_device_ops *cdo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c0ae3890)
Location: drivers/cdrom/cdrom.c:1204
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
c0ae3890-c0ae3bf8: check_for_audio_disc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (c000000000ac28f0)
Location: drivers/cdrom/cdrom.c:1204
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
c000000000ac28f0-c000000000ac2cf4: check_for_audio_disc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffe000632cb4)
Location: drivers/cdrom/cdrom.c:1204
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffe000632cb4-ffffffe000632f7a: check_for_audio_disc.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81797340)
Location: drivers/cdrom/cdrom.c:1204
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81797340-ffffffff8179760e: check_for_audio_disc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81789010)
Location: drivers/cdrom/cdrom.c:1204
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81789010-ffffffff817892de: check_for_audio_disc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817d3de0)
Location: drivers/cdrom/cdrom.c:1204
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff817d3de0-ffffffff817d40ae: check_for_audio_disc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817ee080)
Location: drivers/cdrom/cdrom.c:1204
Inline: True
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff817ee080-ffffffff817ee34e: check_for_audio_disc.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
