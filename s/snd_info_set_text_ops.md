# Function: <code>snd_info_set_text_ops</code>

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
In sound/core/info.c (c0c89a08)
Location: include/sound/info.h:139
Inline: True
Inline callers:
  - sound/core/info.c:snd_info_card_create
```
```
In sound/core/pcm.c (c15b27e0)
Location: include/sound/info.h:139
Inline: True
Inline callers:
  - sound/core/pcm.c:alsa_pcm_init
  - sound/core/pcm.c:snd_pcm_new_stream
  - sound/core/pcm.c:snd_pcm_new_stream
  - sound/core/pcm.c:snd_pcm_new_stream
  - sound/core/pcm.c:snd_pcm_new_stream
  - sound/core/pcm.c:snd_pcm_new_stream
```
```
In sound/core/pcm_memory.c (c0c9b648)
Location: include/sound/info.h:139
Inline: True
Inline callers:
  - sound/core/pcm_memory.c:snd_pcm_lib_preallocate_pages1
  - sound/core/pcm_memory.c:snd_pcm_lib_preallocate_pages1
```
```
In sound/core/compress_offload.c (c0c9d064)
Location: include/sound/info.h:139
Inline: True
Inline callers:
  - sound/core/compress_offload.c:snd_compress_new
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
