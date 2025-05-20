# Function: <code>drm_seq_file_printer</code>

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
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7a0ca)
Location: include/drm/drm_print.h:195
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_state_info
```
```
In drivers/gpu/drm/drm_client.c (ffffffff81c81a16)
Location: include/drm/drm_print.h:195
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client.c:drm_client_debugfs_internal_clients
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c96f06)
Location: include/drm/drm_print.h:195
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_show_fdinfo
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9b456)
Location: include/drm/drm_print.h:195
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:drm_framebuffer_info
```
```
In drivers/gpu/drm/drm_debugfs.c (ffffffff81cba7f8)
Location: include/drm/drm_print.h:195
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs.c:bridges_show
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
