# Function: <code>snd_soc_dai_stream_valid</code>

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
bool snd_soc_dai_stream_valid(struct snd_soc_dai *dai, int dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In sound/soc/soc-dai.c (c0cae570)
Location: sound/soc/soc-dai.c:396
Inline: False
Direct callers:
  - sound/soc/soc-pcm.c:dpcm_state_read_file
  - sound/soc/soc-pcm.c:dpcm_state_read_file
  - sound/soc/soc-pcm.c:soc_new_pcm
  - sound/soc/soc-pcm.c:soc_new_pcm
  - sound/soc/soc-pcm.c:soc_new_pcm
  - sound/soc/soc-pcm.c:soc_new_pcm
  - sound/soc/soc-pcm.c:dpcm_fe_dai_open
  - sound/soc/soc-pcm.c:dpcm_fe_dai_open
  - sound/soc/soc-pcm.c:soc_pcm_hw_free
  - sound/soc/soc-pcm.c:soc_pcm_hw_params
  - sound/soc/soc-pcm.c:soc_pcm_hw_params
  - sound/soc/soc-pcm.c:soc_pcm_open
  - sound/soc/soc-compress.c:snd_soc_new_compress
  - sound/soc/soc-compress.c:snd_soc_new_compress
  - sound/soc/soc-compress.c:snd_soc_new_compress
  - sound/soc/soc-compress.c:snd_soc_new_compress
  - sound/soc/soc-compress.c:snd_soc_new_compress
```
**Symbols:**

```
c0cae570-c0cae5a4: snd_soc_dai_stream_valid (STB_GLOBAL)
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
