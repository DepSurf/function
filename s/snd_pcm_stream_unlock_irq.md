# Function: <code>snd_pcm_stream_unlock_irq</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
void snd_pcm_stream_unlock_irq(struct snd_pcm_substream *substream);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In sound/core/pcm_native.c (c0c91fdc)
Location: sound/core/pcm_native.c:145
Inline: False
Direct callers:
  - sound/core/pcm.c:snd_pcm_dev_disconnect
  - sound/core/pcm_native.c:snd_pcm_poll
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
  - sound/core/pcm_native.c:snd_pcm_rewind_ioctl
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_sync_ptr
  - sound/core/pcm_native.c:snd_pcm_delay
  - sound/core/pcm_native.c:snd_pcm_delay
  - sound/core/pcm_native.c:snd_pcm_drop
  - sound/core/pcm_native.c:snd_pcm_drain
  - sound/core/pcm_native.c:snd_pcm_drain
  - sound/core/pcm_native.c:snd_pcm_prepare
  - sound/core/pcm_native.c:snd_pcm_action_lock_irq
  - sound/core/pcm_native.c:snd_pcm_status
  - sound/core/pcm_native.c:snd_pcm_sw_params
  - sound/core/pcm_native.c:snd_pcm_sw_params
  - sound/core/pcm_native.c:snd_pcm_sw_params
  - sound/core/pcm_native.c:snd_pcm_hw_params
  - sound/core/pcm_native.c:snd_pcm_hw_params
  - sound/core/pcm_native.c:snd_pcm_set_state
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - sound/soc/soc-pcm.c:dpcm_fe_dai_close
  - sound/soc/soc-pcm.c:dpcm_fe_dai_open
  - sound/soc/soc-pcm.c:dpcm_run_old_update
  - sound/soc/soc-pcm.c:dpcm_run_new_update
  - sound/soc/soc-pcm.c:dpcm_fe_dai_prepare
  - sound/soc/soc-pcm.c:dpcm_fe_dai_hw_params
  - sound/soc/soc-pcm.c:dpcm_fe_dai_hw_free
```
**Symbols:**

```
c0c91fdc-c0c92018: snd_pcm_stream_unlock_irq (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
