# Function: <code>frames_to_bytes</code>

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
In sound/core/pcm_native.c (c0c94948)
Location: include/sound/pcm.h:691
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_writev
  - sound/core/pcm_native.c:snd_pcm_readv
  - sound/core/pcm_native.c:snd_pcm_read
```
```
In sound/core/pcm_lib.c (c0c996e8)
Location: include/sound/pcm.h:691
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:snd_pcm_playback_silence
  - sound/core/pcm_lib.c:snd_pcm_playback_silence
```
```
In sound/core/pcm_dmaengine.c (c0c9cac8)
Location: include/sound/pcm.h:691
Inline: True
Inline callers:
  - sound/core/pcm_dmaengine.c:snd_dmaengine_pcm_pointer
  - sound/core/pcm_dmaengine.c:snd_dmaengine_pcm_trigger
  - sound/core/pcm_dmaengine.c:snd_dmaengine_pcm_trigger
  - sound/core/pcm_dmaengine.c:dmaengine_pcm_dma_complete
  - sound/core/pcm_dmaengine.c:dmaengine_pcm_dma_complete
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
