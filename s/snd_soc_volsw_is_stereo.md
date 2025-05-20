# Function: <code>snd_soc_volsw_is_stereo</code>

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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In sound/soc/soc-dapm.c (c0caab50)
Location: include/sound/soc.h:1224
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:snd_soc_dapm_put_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_put_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_put_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_put_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_put_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_put_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_get_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_get_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_get_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_get_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_get_volsw
  - sound/soc/soc-dapm.c:snd_soc_dapm_get_volsw
```
```
In sound/soc/soc-ops.c (c0cb659c)
Location: include/sound/soc.h:1224
Inline: True
Inline callers:
  - sound/soc/soc-ops.c:snd_soc_get_volsw_range
  - sound/soc/soc-ops.c:snd_soc_get_volsw_range
  - sound/soc/soc-ops.c:snd_soc_put_volsw_range
  - sound/soc/soc-ops.c:snd_soc_put_volsw_range
  - sound/soc/soc-ops.c:snd_soc_info_volsw_range
  - sound/soc/soc-ops.c:snd_soc_info_volsw_range
  - sound/soc/soc-ops.c:snd_soc_put_volsw_sx
  - sound/soc/soc-ops.c:snd_soc_put_volsw_sx
  - sound/soc/soc-ops.c:snd_soc_get_volsw_sx
  - sound/soc/soc-ops.c:snd_soc_get_volsw_sx
  - sound/soc/soc-ops.c:snd_soc_put_volsw
  - sound/soc/soc-ops.c:snd_soc_put_volsw
  - sound/soc/soc-ops.c:snd_soc_get_volsw
  - sound/soc/soc-ops.c:snd_soc_get_volsw
  - sound/soc/soc-ops.c:snd_soc_info_volsw
  - sound/soc/soc-ops.c:snd_soc_info_volsw
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
