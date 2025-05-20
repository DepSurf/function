# Function: <code>snd_pcm_action</code>

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
int snd_pcm_action(const struct action_ops *ops, struct snd_pcm_substream *substream, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In sound/core/pcm_native.c (c0c92728)
Location: sound/core/pcm_native.c:1149
Inline: False
Direct callers:
  - sound/core/pcm_native.c:snd_pcm_drop
  - sound/core/pcm_native.c:snd_pcm_drop
  - sound/core/pcm_native.c:snd_pcm_drain
  - sound/core/pcm_native.c:snd_pcm_drain
  - sound/core/pcm_native.c:snd_pcm_drain
  - sound/core/pcm_native.c:snd_pcm_prepare
  - sound/core/pcm_native.c:snd_pcm_prepare
  - sound/core/pcm_native.c:snd_pcm_start
  - sound/core/pcm_native.c:snd_pcm_action_lock_irq
```
**Symbols:**

```
c0c92728-c0c927a0: snd_pcm_action (STB_LOCAL)
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
