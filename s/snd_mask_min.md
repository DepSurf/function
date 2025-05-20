# Function: <code>snd_mask_min</code>

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
In sound/core/pcm_native.c (c0c93980)
Location: include/sound/pcm_params.h:50
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_hw_params
  - sound/core/pcm_native.c:snd_pcm_hw_params
  - sound/core/pcm_native.c:snd_pcm_hw_params
```
```
In sound/core/pcm_lib.c (c0c9867c)
Location: include/sound/pcm_params.h:50
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:snd_pcm_lib_ioctl
  - sound/core/pcm_lib.c:snd_pcm_hw_param_first
```
```
In sound/core/pcm_iec958.c (c0c9c788)
Location: include/sound/pcm_params.h:50
Inline: True
Inline callers:
  - sound/core/pcm_iec958.c:snd_pcm_create_iec958_consumer_hw_params
```
```
In sound/core/pcm_dmaengine.c (c0c9cb20)
Location: include/sound/pcm_params.h:50
Inline: True
Inline callers:
  - sound/core/pcm_dmaengine.c:snd_hwparams_to_dma_slave_config
```
```
In sound/soc/soc-dapm.c (0)
Location: include/sound/pcm_params.h:50
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:snd_soc_dai_link_event
  - sound/soc/soc-dapm.c:snd_soc_dai_link_event
```
```
In sound/soc/soc-utils.c (c0cadd5c)
Location: include/sound/pcm_params.h:50
Inline: True
Inline callers:
  - sound/soc/soc-utils.c:snd_soc_params_to_frame_size
```
```
In sound/soc/soc-pcm.c (c0cb1518)
Location: include/sound/pcm_params.h:50
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
In sound/soc/codecs/sgtl5000.c (0)
Location: include/sound/pcm_params.h:50
Inline: True
Inline callers:
  - sound/soc/codecs/sgtl5000.c:sgtl5000_pcm_hw_params
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc1150)
Location: include/sound/pcm_params.h:50
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_params
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
