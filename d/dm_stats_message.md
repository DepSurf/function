# Function: <code>dm_stats_message</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff816ad600)
Location: drivers/md/dm-stats.c:1165
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff816ad600-ffffffff816ae5c3: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff8170db70)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff8170db70-ffffffff8170eb32: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81740030)
Location: drivers/md/dm-stats.c:1165
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81740030-ffffffff81740b47: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81759dc0)
Location: drivers/md/dm-stats.c:1160
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81759dc0-ffffffff8175a8e8: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff817cc000)
Location: drivers/md/dm-stats.c:1161
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff817cc000-ffffffff817ccb1b: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81814dd0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81814dd0-ffffffff818158d8: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81840de0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81840de0-ffffffff818418d6: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81884721-ffffffff8188472a: dm_stats_message.cold (STB_LOCAL)
ffffffff81883ff0-ffffffff81884670: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff818b6616-ffffffff818b661f: dm_stats_message.cold (STB_LOCAL)
ffffffff818b5f10-ffffffff818b6590: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81986f4e-ffffffff81986f56: dm_stats_message.cold (STB_LOCAL)
ffffffff81986b30-ffffffff81986ecd: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81c286d9-ffffffff81c286e1: dm_stats_message.cold (STB_LOCAL)
ffffffff8198ab80-ffffffff8198af1d: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81c1a8b8-ffffffff81c1a8c0: dm_stats_message.cold (STB_LOCAL)
ffffffff8196f140-ffffffff8196f607: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81d2a7b4-ffffffff81d2a7bc: dm_stats_message.cold (STB_LOCAL)
ffffffff81a17a60-ffffffff81a17f48: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:1199
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81ef6999-ffffffff81ef69a2: dm_stats_message.cold (STB_LOCAL)
ffffffff81b80880-ffffffff81b80c17: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81d1eb40)
Location: drivers/md/dm-stats.c:1199
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81d1eb40-ffffffff81d1eeb5: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81d87d20)
Location: drivers/md/dm-stats.c:1211
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81d87d20-ffffffff81d88095: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81e3f430)
Location: drivers/md/dm-stats.c:1220
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81e3f430-ffffffff81e3f7a5: dm_stats_message (STB_GLOBAL)
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
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffff800010b0dec0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffff800010b0dec0-ffff800010b0e518: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (c0bec288)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
c0bec288-c0bec9e8: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (c000000000c00af0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
c000000000c00af0-c000000000c01534: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffe0006fafb4)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffe0006fafb4-ffffffe0006fb8c8: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff8185c496-ffffffff8185c49f: dm_stats_message.cold (STB_LOCAL)
ffffffff8185bd90-ffffffff8185c410: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff81823a66-ffffffff81823a6f: dm_stats_message.cold (STB_LOCAL)
ffffffff81823360-ffffffff818239e0: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff818abac6-ffffffff818abacf: dm_stats_message.cold (STB_LOCAL)
ffffffff818ab3c0-ffffffff818aba40: dm_stats_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dm_stats_message(struct mapped_device *md, unsigned int argc, char **argv, char *result, unsigned int maxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:1164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
```
**Symbols:**

```
ffffffff818c7d06-ffffffff818c7d0f: dm_stats_message.cold (STB_LOCAL)
ffffffff818c7600-ffffffff818c7c80: dm_stats_message (STB_GLOBAL)
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
