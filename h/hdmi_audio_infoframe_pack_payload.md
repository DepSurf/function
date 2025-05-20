# Function: <code>hdmi_audio_infoframe_pack_payload</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hdmi_audio_infoframe_pack_payload(const struct hdmi_audio_infoframe *frame, u8 *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:392
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_audio_infoframe_pack_for_dp
  - drivers/video/hdmi.c:hdmi_audio_infoframe_pack_only
```
**Symbols:**

```
ffffffff8192f690-ffffffff8192f726: hdmi_audio_infoframe_pack_payload (STB_LOCAL)
ffffffff820902ea-ffffffff820902ff: hdmi_audio_infoframe_pack_payload.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hdmi_audio_infoframe_pack_payload(const struct hdmi_audio_infoframe *frame, u8 *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:392
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_audio_infoframe_pack_for_dp
  - drivers/video/hdmi.c:hdmi_audio_infoframe_pack_only
```
**Symbols:**

```
ffffffff81973b00-ffffffff81973b9a: hdmi_audio_infoframe_pack_payload (STB_LOCAL)
ffffffff8211064a-ffffffff8211065f: hdmi_audio_infoframe_pack_payload.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hdmi_audio_infoframe_pack_payload(const struct hdmi_audio_infoframe *frame, u8 *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:392
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_audio_infoframe_pack_for_dp
  - drivers/video/hdmi.c:hdmi_audio_infoframe_pack_only
```
**Symbols:**

```
ffffffff819bdb70-ffffffff819bdc0a: hdmi_audio_infoframe_pack_payload (STB_LOCAL)
ffffffff821ee447-ffffffff821ee45c: hdmi_audio_infoframe_pack_payload.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
