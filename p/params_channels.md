# Function: <code>params_channels</code>

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
In sound/core/pcm_native.c (c0c939dc)
Location: include/sound/pcm.h:908
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_hw_params
```
```
In sound/core/pcm_lib.c (c0c99f0c)
Location: include/sound/pcm.h:908
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:snd_pcm_lib_ioctl
```
```
In sound/soc/soc-dapm.c (c0ca9010)
Location: include/sound/pcm.h:908
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:snd_soc_dai_link_event
  - sound/soc/soc-dapm.c:dapm_update_dai_unlocked
```
```
In sound/soc/soc-utils.c (c0cadd84)
Location: include/sound/pcm.h:908
Inline: True
Inline callers:
  - sound/soc/soc-utils.c:snd_soc_params_to_frame_size
```
```
In sound/soc/soc-pcm.c (c0cb1538)
Location: include/sound/pcm.h:908
Inline: True
Inline callers:
  - sound/soc/soc-pcm.c:dpcm_show_state
  - sound/soc/soc-pcm.c:dpcm_show_state
  - sound/soc/soc-pcm.c:dpcm_fe_dai_hw_params
  - sound/soc/soc-pcm.c:soc_pcm_hw_params
  - sound/soc/soc-pcm.c:soc_pcm_hw_params
  - sound/soc/soc-pcm.c:soc_pcm_hw_params
```
```
In sound/soc/codecs/sgtl5000.c (c0cbf28c)
Location: include/sound/pcm.h:908
Inline: True
Inline callers:
  - sound/soc/codecs/sgtl5000.c:sgtl5000_pcm_hw_params
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc1150)
Location: include/sound/pcm.h:908
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_params
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_bclk
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
