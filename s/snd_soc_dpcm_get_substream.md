# Function: <code>snd_soc_dpcm_get_substream</code>

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
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct snd_pcm_substream *snd_soc_dpcm_get_substream(struct snd_soc_pcm_runtime *be, int stream);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In sound/soc/soc-pcm.c (c0cb3aec)
Location: sound/soc/soc-pcm.c:3045
Inline: True
Inline callers:
  - sound/soc/soc-pcm.c:dpcm_fe_dai_close
  - sound/soc/soc-pcm.c:dpcm_fe_dai_open
  - sound/soc/soc-pcm.c:dpcm_fe_dai_open
  - sound/soc/soc-pcm.c:dpcm_fe_dai_open
  - sound/soc/soc-pcm.c:dpcm_run_old_update
  - sound/soc/soc-pcm.c:dpcm_run_old_update
  - sound/soc/soc-pcm.c:dpcm_run_new_update
  - sound/soc/soc-pcm.c:dpcm_run_new_update
  - sound/soc/soc-pcm.c:dpcm_fe_dai_prepare
  - sound/soc/soc-pcm.c:dpcm_be_dai_prepare
  - sound/soc/soc-pcm.c:dpcm_be_dai_trigger
  - sound/soc/soc-pcm.c:dpcm_fe_dai_hw_params
  - sound/soc/soc-pcm.c:dpcm_be_dai_hw_params
  - sound/soc/soc-pcm.c:dpcm_be_dai_hw_params
  - sound/soc/soc-pcm.c:dpcm_fe_dai_hw_free
  - sound/soc/soc-pcm.c:dpcm_be_dai_hw_free
  - sound/soc/soc-pcm.c:dpcm_be_dai_shutdown
  - sound/soc/soc-pcm.c:dpcm_be_dai_startup
  - sound/soc/soc-pcm.c:dpcm_be_dai_startup
  - sound/soc/soc-pcm.c:dpcm_be_disconnect
  - sound/soc/soc-pcm.c:dpcm_be_disconnect
```
**Symbols:**

```
c0caf504-c0caf52c: snd_soc_dpcm_get_substream (STB_GLOBAL)
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
