# Function: <code>ncsi_stop_channel_monitor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8188eab0)
Location: net/ncsi/ncsi-manage.c:229
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_enable_hwa
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
**Symbols:**

```
ffffffff8188eab0-ffffffff8188eb07: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818c2da0)
Location: net/ncsi/ncsi-manage.c:248
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_enable_hwa
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
**Symbols:**

```
ffffffff818c2da0-ffffffff818c2df7: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818e9720)
Location: net/ncsi/ncsi-manage.c:248
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_enable_hwa
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
**Symbols:**

```
ffffffff818e9720-ffffffff818e9777: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8196eca0)
Location: net/ncsi/ncsi-manage.c:274
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_enable_hwa
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff8196eca0-ffffffff8196ecf7: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819c83a0)
Location: net/ncsi/ncsi-manage.c:155
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_enable_hwa
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff819c83a0-ffffffff819c83f7: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a002d0)
Location: net/ncsi/ncsi-manage.c:177
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81a002d0-ffffffff81a00327: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a6f520)
Location: net/ncsi/ncsi-manage.c:173
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81a6f520-ffffffff81a6f574: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81aa5d80)
Location: net/ncsi/ncsi-manage.c:172
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81aa5d80-ffffffff81aa5dd4: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba2b7e)
Location: net/ncsi/ncsi-manage.c:174
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81ba1ec0-ffffffff81ba1f14: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81bb23fe)
Location: net/ncsi/ncsi-manage.c:174
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81bb1750-ffffffff81bb17a4: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba141e)
Location: net/ncsi/ncsi-manage.c:180
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81ba0770-ffffffff81ba07c4: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:180
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
**Symbols:**

```
ffffffff81d426c9-ffffffff81d426de: ncsi_stop_channel_monitor.cold (STB_LOCAL)
ffffffff81c6ddc0-ffffffff81c6de35: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:180
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
**Symbols:**

```
ffffffff81f0f066-ffffffff81f0f083: ncsi_stop_channel_monitor.cold (STB_LOCAL)
ffffffff81e11870-ffffffff81e118fc: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:180
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
**Symbols:**

```
ffffffff820b59b0-ffffffff820b59cd: ncsi_stop_channel_monitor.cold (STB_LOCAL)
ffffffff81fe8220-ffffffff81fe82ac: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:180
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
**Symbols:**

```
ffffffff82136f33-ffffffff82136f50: ncsi_stop_channel_monitor.cold (STB_LOCAL)
ffffffff820644a0-ffffffff8206452c: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:180
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
```
**Symbols:**

```
ffffffff82218d95-ffffffff82218db2: ncsi_stop_channel_monitor.cold (STB_LOCAL)
ffffffff821375e0-ffffffff8213766c: ncsi_stop_channel_monitor (STB_GLOBAL)
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
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffff800010d78640)
Location: net/ncsi/ncsi-manage.c:172
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffff800010d78640-ffff800010d78710: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c0e74638)
Location: net/ncsi/ncsi-manage.c:172
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
c0e74638-c0e74690: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c000000000eb7fe0)
Location: net/ncsi/ncsi-manage.c:172
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
c000000000eb7fe0-c000000000eb8080: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffe0008a7b76)
Location: net/ncsi/ncsi-manage.c:172
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffe0008a7b76-ffffffe0008a7bde: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a45110)
Location: net/ncsi/ncsi-manage.c:172
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81a45110-ffffffff81a45164: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a01d00)
Location: net/ncsi/ncsi-manage.c:172
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81a01d00-ffffffff81a01d54: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ab0fc0)
Location: net/ncsi/ncsi-manage.c:172
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81ab0fc0-ffffffff81ab1014: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ncsi_stop_channel_monitor(struct ncsi_channel *nc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81abd370)
Location: net/ncsi/ncsi-manage.c:172
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_stop_dev
  - net/ncsi/ncsi-manage.c:ncsi_kick_channels
  - net/ncsi/ncsi-manage.c:ncsi_remove_package
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
  - net/ncsi/ncsi-manage.c:ncsi_channel_monitor
```
**Symbols:**

```
ffffffff81abd370-ffffffff81abd3c4: ncsi_stop_channel_monitor (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
